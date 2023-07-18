# BookStoreApi

La BookStoreApi es una API web desarrollada en .NET Core que permite realizar operaciones de creación, lectura, actualización y eliminación (CRUD) en una base de datos NoSQL de MongoDB. Este proyecto forma parte del curso de Desarrollo web en .NET Core y constituye la séptima entrega.

## Funcionalidades

La API ofrece las siguientes funcionalidades:

- Creación de libros: Permite agregar nuevos libros a la base de datos especificando el título, autor, género y año de publicación.
- Lectura de libros: Permite obtener la información de los libros almacenados en la base de datos. Se pueden obtener todos los libros o filtrarlos por título, autor o género.
- Actualización de libros: Permite actualizar la información de un libro existente en la base de datos.
- Eliminación de libros: Permite eliminar un libro de la base de datos.

## Tecnologías utilizadas

La BookStoreApi se ha desarrollado utilizando las siguientes tecnologías:

- .NET Core: Framework de desarrollo utilizado para la implementación de la API.
- MongoDB: Base de datos NoSQL utilizada para almacenar los libros y su información.
- C#: Lenguaje de programación utilizado para desarrollar la lógica de la API.

## Configuración

Para ejecutar la BookStoreApi en tu entorno de desarrollo, sigue los siguientes pasos:

1. Asegúrate de tener instalado .NET Core en tu sistema.
2. Clona o descarga este repositorio en tu máquina local.
3. Abre el proyecto en tu entorno de desarrollo preferido.
4. Configura la cadena de conexión a tu base de datos MongoDB en el archivo `appsettings.json`.
5. Ejecuta la API utilizando el comando `dotnet run`.
6. La API estará disponible en `http://localhost:5000`.

## Endpoints

La BookStoreApi expone los siguientes endpoints:

- `GET /api/books`: Obtiene todos los libros.
- `GET /api/books/{id}`: Obtiene un libro específico por su ID.
- `POST /api/books`: Crea un nuevo libro.
- `PUT /api/books/{id}`: Actualiza un libro existente.
- `DELETE /api/books/{id}`: Elimina un libro.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, asegúrate de seguir estas pautas:

1. Realiza un fork del repositorio.
2. Crea una rama nueva para tu contribución.
3. Realiza los cambios y mejoras deseadas.
4. Asegúrate de que los tests pasen correctamente.
5. Realiza un pull request a la rama principal del repositorio original.

## Licencia

Este proyecto está bajo la Licencia MIT. Para más información, consulta el archivo [LICENSE](LICENSE).

## Contacto

Si tienes alguna pregunta o sugerencia relacionada con este proyecto, no dudes en ponerte en contacto con el equipo de desarrollo enviando un correo electrónico a [isidro.aguilar94@gmail.com](mailto:isidro.aguilar94@gmail.com).

¡Gracias por tu interés en la BookStoreApi! Esperamos que sea útil para tus necesidades de desarrollo web.
