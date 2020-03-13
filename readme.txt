How to run this application:

After download and extract file master, then put to your work directories.
Open your CMD or other CLI Service, then copy paste these steps below:
1. composer update
2. copy .env.example .env
3. php artisan key:generate
4. create database 'mylibrary' in your mysql dbms
5. setting .env file, set as your system database
6. php artisan migrate
7. php artisan db:seed
8. php artisan serve

User and admin included in file application.