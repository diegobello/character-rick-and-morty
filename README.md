# Rick and Morty App - Laravel

Esta aplicación consume la API de Rick and Morty y permite visualizar y guardar los primeros 100 personajes.

## Características

- Consumo de la API externa con capa de servicio.
- Guardado de personajes en base de datos con repositorio.
- Interfaz moderna usando AJAX para cargar y mostrar detalles.
- Estilos y JavaScript separados.
- Arquitectura limpia: controlador, servicio, repositorio, request.

## Instalación

1. Clona el repositorio o descomprime este archivo.
2. Ejecuta `composer install`
3. Copia el `.env.example` a `.env` y configura la base de datos.
4. Ejecuta `php artisan migrate`
5. Levanta el servidor: `php artisan serve`
6. Visita `http://localhost:8000/characters`

## Créditos

- API: https://rickandmortyapi.com
