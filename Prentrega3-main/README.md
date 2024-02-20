# Preentrega 3
# Nombre
Erwin Gonzalez
# Resumen del proyecto
El objetivo es desarrollar una aplicación web en Django utilizando la herencia de plantillas. La aplicación incluirá un modelo con al menos 3 clases, un formulario para ingresar datos a estos modelos, y un listado que mostrará los registros almacenados en la base de datos.

# Pasos para ejecutar el proyecto
Crear un entorno virtual:

python -m venv .venv
Activar el entorno virtual (Windows Powershell):

.\.venv\Scripts\activate
Crear y gestionar las dependencias utilizando un archivo requirements.txt:

pip freeze >> requirements.txt
Para instalar las dependencias:

pip install -r requirements.txt
Instalación de Django:

pip install django
Crear un proyecto Django:

md project
cd project
django-admin startproject config .
Ejecutar el servidor:

python manage.py runserver
Crear una aplicación:

Estar ubicado dentro de la carpeta project, pero fuera de config:

python manage.py makemigrations
python manage.py migrate
Crear un superusuario:

python manage.py createsuperuser
Estos pasos proporcionan una guía paso a paso para la configuración del entorno y la creación del proyecto Django, junto con la aplicación y el superusuario necesario para iniciar el desarrollo del proyecto.

