# LaravelSyntax
run laravel project: php artisan serve <br>
create new project: composer create-project laravel/laravel NameProject.<br>
create a controller: php artisan make:controller NameController (VD: php artisan make:controller PostController-adjust code in the PostController to viewable)<br>
create view: create mannual(table-tr-th)<br>
set up route for viewing<br><br>

How to create new table in laravel? <br>
create migration: php artisan make:migration create_post_table <br>
add code to file migration then run php artisan migrate <br><br>

create model : php artisan make:model Post then configure file model <br><br>

create factory: php artisan make:factory PostFactory --model=post then configure <br><br>

create seeder: php artisan make:seeder StudentSeeder then configure <br>
open databaseseeder file to call StudentSeeder then run command php artisan db:seed <br><br>

function:show first 5 database<br>
- In web.php, Add route for view 
- If haven't create a controller for the model
- In PostController add new function: index
- create view: view/posts/index.blade.php

<br>
function:show detail<br>
- In web.php, add 1 more route <br>
- In PostController, add function: show beside index <br>
- create view: view/posts/show.blade.php <br>



