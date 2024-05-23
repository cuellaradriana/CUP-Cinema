# Aplicación de Tarjetas de Películas - Proyecto Full Stack
Este proyecto es una aplicación full stack donde se almacenan tarjetas con información de películas. La información se toma de un formulario y se almacena en una base de datos MongoDB. Posteriormente, esta información se renderiza en la sección principal de la aplicación.

## Tecnologías Utilizadas
### Backend
- Node.js: Utilizado para el desarrollo del servidor.
- Express.js: Framework de Node.js utilizado para la creación de rutas y manejo de peticiones HTTP.
- Mongoose: ODM (Object Data Modeling) de MongoDB utilizado para interactuar con la base de datos desde Node.js.
### Frontend
- JavaScript: Lenguaje de programación utilizado en el frontend.
- Webpack: Utilizado para el empaquetado de módulos y assets.
- Axios: Biblioteca utilizada para realizar solicitudes CRUD (Crear, Leer, Actualizar, Eliminar) al servidor desde el frontend.

## Estructura del Proyecto
- back/: Contiene el código del servidor backend.
- front/: Contiene el código del frontend de la aplicación.
- package.json: Archivo de configuración de Node.js que incluye las dependencias del proyecto y los scripts de ejecución, está presente en ambas aplicaciones (front y back).

## Instalación
- Clona este repositorio en tu máquina local.
- Instala las dependencias del backend:

```bash
cd backend
npm install
```
- Instala las dependencias del frontend:

```bash
cd frontend
npm install
```
## Uso
- Inicia el servidor backend:

```bash
cd backend
npm start
```
-Inicia el servidor frontend (en una nueva terminal):

```bash
cd frontend
npm start
```
- Abre tu navegador y navega a http://localhost:3000 para ver la aplicación en funcionamiento.

## Contribución
Si deseas contribuir a este proyecto, sigue estos pasos:

- Haz un fork del proyecto.
- Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
- Realiza tus cambios y haz commit (git commit -m 'Agrega una nueva característica').
- Haz push a la rama (git push origin feature/nueva-caracteristica).
- Abre un Pull Request.
