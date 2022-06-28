# DemoEmmanuel-LuisDaniel
Este repositorio contiene el demo realizado en visual studio code

El link del tutorial corresponde a [Using Django in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-django). 

Para la utilización de este demo es indispensable clonar primeramente el repositorio a su almacenamiento local.

>NOTA: Es necesario instalar la versión de Visual Studio Code más reciente debido a que pueden presentarse errores en el debug.

Posteriormente es necesario seguir los siguientes pasos:

1. Crear un entorno virtual que contendrá los requerimientos necesarios y que no sean instalados de manera global 

`python3 -m venv .venv`

2. Activar el entorno 

`source .venv/bin/activate`

3. Actualizar pip en el entorno virtual 

`python3 -m pip install --upgrade pip`

4. Es necesario instalar django en el entorno virtual 

`python3 -m pip install django`

5. Instalar los recursos necesarios para el proyecto contenidos en el archivo requierements.txt.

`pip3 install -r requirements.txt`

12. Activate the virtual environment by running `source env/bin/activate` (Linux/MacOS) or `env\scripts\activate` (Windows).
13. Create and initialize the database by running `python manage.py migrate`.
14. Create a superuser as described at the end of the tutorial.

