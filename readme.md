#api authentication using Passport in laravel 5.8
Laravel introduce Passport package for api authentication. Passport package through you can make authentication using OAuth2, JWT etc.
 In this example we have used Passport Package for user auth via api.

You have to just follow few step to get following web services.

1)Login API

2)Register API

3)Details API

#Step 1 :
write command on git cmd or cmd 

git clone https://github.com/infokmsohel/laravelPassport.git

or download the project

#Step 2 : composer install

#Step 3 : create .env file(copy .env.example paste into .env file)

#Step 4 :setup database and connect

#Step 5 :Run Migration and Install
php artisan migrate

#Step 6 : Now we are ready to run the project
php artisan serve

Here is Routes URL with Verb:

1) Register: Verb:POST, URL:http://localhost:8000/api/v1/register
2) Login: Verb:POST, URL:http://localhost:8000/api/v1/login

 

