# Libro-de-Temas

Sistema de gestión académica para la digitalización del libro de temas.

Este proyecto busca eliminar el uso de papel en los libros de temas y digitalizar el proceso de registro y control de la información académica en la **Escuela Normal Superior Dalmacio Vélez Sarsfield**.

### Stack Tecnológico

El proyecto utiliza la arquitectura *Modelo-Vista-Controlador (MVC)* y el stack **PERN**:

* **Frontend:** React.js con Vite.
* **Backend:** Node.js con Express.
* **Base de Datos:** PostgreSQL.

### Equipo de Desarrollo

Proyecto desarrollado por los alumnos de 3er año de Desarrollo de Software:

* Alanis Camila
* Alanis Jimena
* Almada Pablo
* Manera Micaela
* Marchetti Marianela
* Martina Valentin
* Paz Enzo
* Rossi Ivo

## Instalación y Configuración

Sigue estos pasos para configurar el proyecto en tu entorno local.

### Prerrequisitos
* Tener instalado *Node.js* y *npm*.
 
* Tener instalado **PostgreSQL** y crear una base de datos llamada `libro_de_temas_db`.

### 1. Clonar el repositorio

git clone https://github.com/Ivorossi66/Libro-de-Temas.git

cd LIBRO_DE_TEMAS

### 2. Configurar Backend

* cd backend
 
* npm install
 
* Crear archivo .env dentro de /backend y agregar:

DB_HOST=localhost

DB_PORT=5432

DB_USER=tu_usuario

DB_PASSWORD=tu_password

DB_NAME=libro_de_temas_db

PORT=3001

-En la terminal correr el backend: 
*npm run dev*

### 3. Configurar Frontend 

-cmd 

cd ../frontend

npm install

npm run dev

-La app se iniciara en:
*http://localhost:5173*
 
