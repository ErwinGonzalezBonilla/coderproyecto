# Preentrega 3 Comisión 56060

## Nombre ##

- Luis Gonzalez Bonilla

## Resumen del proyecto

Crea una web en Django utilizando Herencia de plantillas, con un modelo de por lo menos 3 clases, un formulario para ingresar datos a los 3  modelosclases y un listado de los registro ingresados en la base de datos


## Pasos para ejecutar el proyecto


- creación del entorno virtual

- instalar las dependencias con pip requirements


## ¿Cómo crear un entorno virtual? 

python -m venv .venv 

## ¿Cómo activar el entorno virtual?

.\.venv\Scripts\activate (Windows Powershell)


## ¿Cómo crear requirements.txt?

pip freeze >> requirements.txt

¿Cómo instalar paquetes desde requirements.txt?

pip install -r requirements.txt
Instalación Django
pip install django
Crear un proyecto
Crear una carpeta para el proyecto en la raiz:

md project
Acceder a la carpeta project

cd project
Crear las carpetas y archivos necesarios

django-admin startproject config .
Ejecutar el servidor:

python manage.py runserver


Crear una aplicación:
Estar ubicado dentro de project pero fuera de config


python manage.py makemigrations
Crear SQL y modificar base de datos:

python manage.py migrate
Crear superusuario
python manage.py createsuperuser