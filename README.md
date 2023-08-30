# back_ASLS
Backend of ASLS (Laravel) 
# initiate server using cmd
PHP artisan serve

# run migrations 
php artisan migrate

#make a controller
php artisan make:controller colorcontroller

#make a model
php artisan make:model tema -s
php artisan make:model color -m

#run server 
php -S localhost:3000

#Es importante tener abierto xampp e importar la base de datos para correr el servidor en el puerto indicado que en este caso, es el puerto 3000
