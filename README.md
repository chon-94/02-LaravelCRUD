# 02-LaravelCRUD
 CRUD

# Creaciones

 Para crear el proyecto laravel utilizamos este codigo

     composer create-project --prefer-dist laravel/laravel proyecto-0 "10.*"

 hace lo siguiente:

     Usa Composer para crear un nuevo proyecto.
     Prefiere descargar archivos comprimidos en lugar de clonar repositorios.
     Utiliza el paquete laravel/laravel como plantilla.
     Crea una nueva carpeta llamada proyecto-0 y coloca allí todos los archivos del proyecto.
     Asegura que la versión de Laravel instalada sea la 10 (cualquier versión menor de la 10).

 Este comando es muy útil para iniciar rápidamente un nuevo proyecto Laravel con una configuración inicial estándar.

## Autenticacion

     composer require laravel/breeze --dev

     php artisan breeze:install -h

     php artisan breeze:install blade --dark

     