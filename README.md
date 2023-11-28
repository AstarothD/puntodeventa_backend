# puntodeventa_backend
 Backend del punto de venta usando fastAPI un framework de Python

 Primero instalamos lo necesario para el entorno virtual con:  pip install virtualenv
 Creamos el entorno virtual con : python -m venv venv 
 Despues de crear el entorno virtual lo activamos con: venv\Scripts\activate 

# Instalamos FASTAPI

Primero instalamos fastAPI con: pip install fastapi  sobre el que nos basaremos para crear nuestra Api

# Instalamos Uvicorn

Uvicorn es un servidor ASGI que nos permite ejecutar aplicaciones FastAPI de manera eficiente, usamos pip install uvicorn para instalarlo.

Despues podemos iniciar el servidor de nuestra Api con : uvicorn main:app --reload

# Instalacion de libreria .env

Para instalar lo necesario usamos pip install python-dotenv  el cual nos permite crear un archivo .env para configurar la coneccion con la base de datos.

# Instalacion biblioteca databases

Instalamos usando: pip install databases

Es una biblioteca que proporciona una interfaz para interactuar de manera asíncrona con bases de datos relacionales. En el contexto de FastAPI, es común usar esta biblioteca para manejar operaciones de base de datos de forma asíncrona.

# Instalar libreria para usar PostgreSQL

Instala usando: pip install psycopg2-binary

PostgreSQL es un sistema de gestión de bases de datos relacional, y psycopg2 es un adaptador de base de datos para PostgreSQL. Estos son necesarios para interactuar con una base de datos PostgreSQL desde tu aplicación FastAPI.

# Instala ORM SQLAlchemy
SQLAlchemy es el ORM que te permite interactuar con la base de datos desde FastAPI

Instala usando: pip install SQLAlchemy

# Instala Alembic para migraciones de base de datos

Alembic es una herramienta de migración de bases de datos que funciona bien con SQLAlchemy.

Instala usando: pip install alembic

# Instalar Pydantic  para validación de datos
Es una biblioteca en Python que se utiliza para la validación de datos. Proporciona una forma declarativa de definir modelos de datos y especificar las restricciones y características de esos modelos.

Instala usando: pip install pydantic
