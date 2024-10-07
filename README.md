# LaravelSyntax
run laravel project: php artisan serve <br>
create new project: composer create-project laravel/laravel NameProject.<br>
create a controller: php artisan make:controller NameController (VD: php artisan make:controller StudentController-adjust code in the StudentController to viewable)<br>
create view: create mannual(table-tr-th)<br>
set up route for viewing<br><br>

How to create new table in laravel? <br>
create migration: php artisan make:migration create_users_table <br>
add code to file migration then run php artisan migrate <br><br>

create model : php artisan make:model Student then configure file model <br><br>

create factory: php artisan make:factory StudentFactory --model=Student then configure <br><br>

create seeder: php artisan make:seeder StudentSeeder then configure <br>
open databaseseeder file to call StudentSeeder then run command php artisan db:seed <br><br>




