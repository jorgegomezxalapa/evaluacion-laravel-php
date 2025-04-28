# Evaluación Laravel PHP
Este proyecto es una evaluación técnica usando Laravel 11.

# Requisitos previos
1. Instalar composer en su última versión en el entorno local.
2. Instalar node js en su última versión en el entorno local.
3. Instalar y configurar PostgreSQL en su última versión en el entorno local.

## Instalación
1. Clona el repositorio https://github.com/jorgegomezxalapa/evaluacion-laravel-php.git
2. Dirígete a la carpeta del proyecto, por ejemplo C:\laragon\www\evaluacion-tenica-php
3. Crea un archivo .env en la raíz del proyecto, la información de dicho archivo la puedes clonar del archivo `.env.example`.
4. Abre la consola en la carpeta del proyecto, y ejecuta el comando `composer install`.
5. En base de datos postgresql, crear una base de datos llamada `laravel` y el usuario `postgres`.
6. Abre la consola en la carpeta del proyecto, y ejecuta el comando `php artisan migrate:fresh --seed`.
7. Abre la consola en la carpeta del proyecto, y ejecuta el comando `npm install`.

## Uso
Ejecuta `php artisan serve` para iniciar el servidor local.
Ejecuta `npm run dev` para compilar los assets del proyecto en el servidor local.