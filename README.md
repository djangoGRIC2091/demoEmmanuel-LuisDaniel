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

6. Activar el servidor para utilizar el demo y verimificar su funcionamiento a través del navegador en el puerto 8000 (por defecto).

`python3 manage.py runserver`

`http//127.0.0.1:8000/`

7. Agregar los usuarios necesarios para administrar a django mediante el siguiente comando:

`python manage.py createsuperuser --username=<username> --email=<email>`

8. En el navegador se puede ingresar al menú de administración de django en la ruta /admin

`http//127.0.0.1:8000/admin`

# CONTRIBUIDORES

- López García Emmanuel
- Sánchez Cabrera Luis Daniel
