

pip install --upgrade pip
pip install django==2.1.7
django-admin startproject proyecto1
cd proyecto1
python manage.py runserver

# En el navegador escribirmos localhost:8000    

#Esto es lo que se hizo en el proyecto para que 1 pagina 
-----django instalado----
django-admin startproject pagweb
sttings.py -> templates -> se anexa a dirs la direccion de la carpeta, pero con los "/" de dividir (esta direccion se consigue dando click en guardar como y luego en links)
Creamos views.py ->  importamos de django http, HttpResponse ,template, context , template.loader, get_template
views.py -> crea la def (request) , se pone la direccion del get_template('miplantilla.html') 
views.py -> se renderisa la variable plantillarender=plantilla.render() y se retorna la variable en HttpResponse
Crear la plantilla html
url -> importar funciones asi "from nombreproyecto.views import saludo" y en urlpatterns -> path('saludo/', saludo),
probar


#Otros comandos
python manage.py createsuperuser 
python manage.py makemigrations
python manage.py migrate


Sebastian Guevara Sanchez
sebasguesa@hotmail.com
https://github.com/guevaraStian




