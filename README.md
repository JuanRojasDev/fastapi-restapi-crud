# Python con FastApi creando APIREST
simple ApiREST utilizando FastApi y Uvicorn

## Descripción

Esta API permite la gestión de publicaciones (posts). Las funcionalidades principales incluyen:

- Crear una nueva publicación
- Leer todas las publicaciones
- Leer una publicación específica por su ID
- Actualizar una publicación existente
- Eliminar una publicación existente

## Requisitos

- Python 3.7+
- FastAPI
- Uvicorn

## Instalación

1. Clona este reposi
2. Instala las dependencias: ("Pip install FastApi", "Pip install Uvicorn")

## Uso

1. Ejecuta la aplicación:
2. Visita [http://localhost:8000](http://localhost:8000) en tu navegador o utiliza herramientas como cURL o Postman para interactuar con la API.
   
## Endpoints

### GET /

- Descripción: Devuelve un mensaje de bienvenida.
- Ejemplo de respuesta:

`json
{"welcome": "Welcome to my API"}

### POST /posts
Descripción: Crea una nueva publicación.

`json
{
  "title": "Título de la publicación",
  "author": "Autor de la publicación",
  "recived": "2024-02-17",
  "content": "Contenido de la publicación"
}
`
### GET /posts/{post_id}
Descripción: Devuelve una publicación específica por su ID.
Ejemplo de respuesta:
`json
{
  "id": "1",
  "title": "Título de la publicación",
  "author": "Autor de la publicación",
  "recived": "2024-02-17",
  "content": "Contenido de la publicación",
  "created_at": "2024-02-17T12:00:00",
  "published_at": null,
  "published": false
}
`
###DELETE /posts/{post_id}
Descripción: Elimina una publicación existente por su ID.
Ejemplo de respuesta:
`json
{"message": "Post has been deleted successfully"}
`
#### PUT /posts/{post_id}
Descripción: Actualiza una publicación existente por su ID.
Ejemplo de solicitud:
`json
{
  "title": "Nuevo título de la publicación",
  "author": "Nuevo autor de la publicación",
  "recived": "2024-02-17",
  "content": "Nuevo contenido de la publicación"
}
`
Ejemplo de respuesta:
`json
{"message": "Post has been updated successfully"}
`
### Contribuyendo
Si deseas contribuir a este proyecto, puedes hacerlo libre de código

### Go
Copy code






