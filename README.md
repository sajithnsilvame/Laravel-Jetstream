# Laravel 9 Authentication using Jetstream

## Install Laravel 9:
Here we need to install laravel 9 application using composer command

```
composer create-project laravel/laravel example-app
```
## Install Jetstream
Now, in this step, we need to use the composer command to install jetstream, so let's run bellow command and install bellow library

```
composer require laravel/jetstream
```

## Create Auth with Livewire
Now, we need to create authentication using the bellow command. you can create basic login, register, and email verification. if you want to create team management then you have to pass the addition parameter. you can see bellow commands

```
php artisan jetstream:install livewire

OR

php artisan jetstream:install livewire --teams
```
## Now let's run node js package
```
npm install
```
## Let's run package
```
npm run dev
```

## Now we need to run migration command to create database table
```
php artisan migrate
```

## All the required steps have been done, now you have to type the given below command and hit enter to run the Laravel app
```
php artisan serve
```

### ***Now, you can run and check. they installed all views, actions, and all in your laravel 9 application***