#Django sample project

El proyecto está preparado para ser clonado y ejecutado en **Visual Studio Code**

##Clonación

Abre Visual Studio Code y desde la paleta de comandos (F1) invoca el comando "Git: clonar" y seguimos el flujo de clonación indicando la url del repositorio -> https://github.com/diegoandradecanosa/django

Una vez clonado probablemente debemos indicar que Confiamos en el código del repositorio y nos darán la opción de crear un contenedor en base a los ficheros del repositorio.

##Arrancado del servidor

Una vez tengamos el repositorio clonado y arrancado dentro del contenedor, dentro del terminal del contenedor (CTRL+ñ) debemos ejecutar los siguientes comandos para arrancar el contenedor

'cd myciao
python manage.py runserver
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver'
