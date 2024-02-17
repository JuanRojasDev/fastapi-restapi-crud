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

```json
{"welcome": "Welcome to my API"}
