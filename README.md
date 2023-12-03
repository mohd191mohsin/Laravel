# Laravel
<!-- Tut1 start -->
install composer : https://getcomposer.org/doc/00-intro.md

create laravel project through composer 

open terminal and run below commands

1.composer create-project laravel/laravel tut1
2.cd tut1
3.php artisan serve

open http://127.0.0.1:8000/ link in your browser.

A.first of all we learn about routes.
    1.Goto routes folder and open web.php file.
        a. 1 route is present in this file that call a function and return view function that call  welcome.blade.php file that is present in resources/views/ .
    2.You can create all routes of your project in this file.
    3.We have several method to define the routes.
    4.Lets create home route that return index template.
    5.Update route by replace welcome to index.
    5.Route::get('/', function () {
        return view('index');
    });
B.learn about views.
    1.Create a new template in resouces/views/index.blade.php
    2.Write your HTML here of your project.like <h1>Hello World!!!</h1>

<!-- Tut1 End -->