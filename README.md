<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Instalacion

 enseñare como instalar la aplicacion en su pc de forma local

creamos una carpeta  en nuestro xammp: 
esta carpeta debe estar en la siguiente ruta: C:\xampp\htdocs



## instalar con comandos git
luego abrimos un cmd o git  de la carpeta creada.
colocamos el siguiente comando y en esa misma linea el link del repositorio.
como veremos a continuación.

## Comandos de Instalacion
git clone https://github.com/damircaro/pruebaTecnica
----------------------------------------------------------
luego de que se descargue la application.abrimos nuestro visual code
dentro de nuestro visual code ,ejecutamos la terminal para continuar con la instalacion.

### Comando dentro de la terminal
En laterminal colocamos los sigueintes Comandos:
composer install
npm install
--------------------------------------------------------------
luego de la intalacion,buscamos en el proyecto  el siguente documento: .env.example
este se encuentra afuera de las carpetas
luego de encontrarlo lo selecionas y lo copias y lo pegas en ese mismo lugar
luego de est solo le cambias el nombre a .env
------------------------------------------------------------------
despues de todos estos paso colocamos este comoando en la terminal para generar la llave:
php artisan key:generate
por ultimo modificamos el nombre de la base de datos que ya debes tener creada.

## Migracion de tablas a la Base de datos
en este ultimo paso ejecutamos el comando para migrar las tablas a la base de datos:
php artisan migrate
## Dentro de la aplicacion
cuanto terminemos todos estos pasos  en nuestra terminal ejecutamos:
php artisan serve
-------------------------------------------------------------------
debemos tener el XAMPP activado con el mysql y apache.
luego ingresamos a la url que nos muestra la terminal.
-------------------------------------------------------------------
al ingresar a esta url nos enviara a loguiarnos vamos a la parte de registrar y nos registramos y con ello podremos ingresar  a la aplicacion.





