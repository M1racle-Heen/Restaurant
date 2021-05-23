# M1racle-Heen-HostingOnHeroku2
# GENERAL DESCRIPTION OF THE PROJECT

Created Single Page Restaurant Web Application.Based on PHP Laravel.
In this application anyone can see various types of dishes, ratings of dishes and prices for them, as well as register and book a table and select a date and time, and can also provide a coupon.

Also i uploaded website on internet check it [here](http://hostingonherokuyes.herokuapp.com/).

# KEY PROJECT FILES

Routing is implemented in the file: routes \ web.php

The developed controllers are located in the folder: app \ Http \ Controllers


Request validation rules are specified in the class: App \ Http \ Requests 

The migration files are located in the directory: database \ migrations

Template files: resources \ views \ site

Model class: app \ UserAddress.php

Resource files are located in the directory: public \
# INSTALLATION

Clone the project to the server directory:

`git clone https: // github.com / pkrotkikh / laravel-project-example.git`

Then, opening the console from the project folder, enter the command to install the laravel packages:

`composer install`

Create a database on the server and fill in the fields of the .env file located in the project folder as follows:

`DB_CONNECTION = mysql`

`DB_HOST = 127.0.0.1`

`DB_PORT = 3306`

`DB_DATABASE = larticles`

`DB_USERNAME = root`

`DB_PASSWORD = null`

In the open console of the project directory, enter the command to generate the database tables:

`php artisan migrate`

In the same console, to launch the site at `http: // localhost: 8000`, enter the command:

`php artisan serve`

Open the site in a browser at `http: // localhost: 8000`
