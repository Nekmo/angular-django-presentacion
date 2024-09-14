.. image:: https://raw.githubusercontent.com/Nekmo/angular-django-presentacion/master/logo.png
    :width: 100%

|

.. image:: https://img.shields.io/github/actions/workflow/status/Nekmo/angular-django-presentacion/build.yml?style=flat-square&branch=master
  :target: https://github.com/Nekmo/angular-django-presentacion/actions?query=workflow%3ABuild
  :alt: Latest CI build status


===========================
Angular-django presentación
===========================
Los mundos de Angular y Django pueden parecer muy dispares, pero ambos comparten lo que les define: su filosofía.
Tanto Angular como Django son frameworks todo en uno, incluyendo todo lo necesario para el desarrollo. Veremos cómo
estrechar ambos mundos a través de Django Rest Framework, y todo lo bueno que puede traer Django al desarrollador de
Angular.

La presentación está `disponible online <https://nekmo.github.io/angular-django-presentacion/>`_ ya compilada
para su visualización.

Requisitos y contenido
----------------------
La presentación está orientada a desarrolladores de Angular, que estén interesados en desarrollo backend. No es
necesario conocer Python o Django previamente, siendo ésta una presentación para conocer las ventajas de Django y cómo
puede ser utilizado en conjunto con Angular. En la presentación se verán los siguientes puntos:

* Introducción a Python.
* Filosofía de Django y cómo se aplica a Angular.
* Django y sus características.
* Proxies en Angular.
* Django Rest Framework.
* Componentes y características de Django Rest Framework, y su relación con Angular.
* Interfaces y servicios en Angular.
* Angular-django.


Motivación
----------
Angular y Django son dos frameworks que comparten una filosofía similar: ser todo en uno. Django es un framework de
Python que incluye todo lo necesario para el desarrollo web, al igual que Angular. Los desarrolladores de Angular
encontrarán en Django una herramienta que comparte su misma filosofía, al mismo tiempo que aprovechan el ecosistema de
Python. Esta charla está orientada a los siguientes perfiles:

* Desarrolladores Angular que deseen conocer alternativas a Node.js y Express.
* Desarrolladores de Angular que ya conociesen Python, o están interesados en su uso.
* Desarrolladores Django que deseen conocer cómo integrar Angular en sus proyectos.

Es recomendable tener conocimientos previos de Angular, aunque no es necesario conocer Django o Python previamente.

Acerca de
---------
Presentación para `Angular Málaga <https://angularmalaga.com/>`_ el día 17 de septiembre de 2024. Puedes
utilizar esta misma presentación, íntegra o con modificaciones para cualquiera de los usos descritos en la licencia
MIT adjunta en este proyecto.

Compilación
-----------
Para compilar desde el código fuente se requiere Python 3 instalado, estando probado sólo bajo Python 3.12. Se
recomienda ejecutar los siguientes pasos en un
`virtualenv <https://nekmo.com/es/blog/python-virtualenvs-y-virtualenvwrapper/>`_::

    # Clonar proyecto
    git clone https://github.com/Nekmo/angular-django-presentacion.git
    cd angular-django-presentacion
    # Instalar dependencias
    pip install -r requirements.txt
    # Compilar ficheros de estilos
    sassc _static/theme.scss _static/theme.css
    # Compilar presentación
    make revealjs

Tras la compilación puede verse los ficheros resultantes en el directorio ``_build``.


Copyright
=========
Licencia MIT. Ver fichero ``LICENSE.txt``.

Nekmo 2024.

