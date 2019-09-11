=============================
Django Ariadne JWT
=============================

.. image:: https://badge.fury.io/py/django-ariadne-jwt.svg
    :target: https://badge.fury.io/py/django-ariadne-jwt

.. image:: https://travis-ci.org/ricardolobo/django-ariadne-jwt.svg?branch=master
    :target: https://travis-ci.org/ricardolobo/django-ariadne-jwt

.. image:: https://codecov.io/gh/ricardolobo/django-ariadne-jwt/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/ricardolobo/django-ariadne-jwt

Your project description goes here

Documentation
-------------

The full documentation is at https://django-ariadne-jwt.readthedocs.io.

Quickstart
----------

Install Django Ariadne JWT::

    pip install django-ariadne-jwt

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_ariadne_jwt.apps.DjangoAriadneJwtConfig',
        ...
    )

Add Django Ariadne JWT's URL patterns:

.. code-block:: python

    from django_ariadne_jwt import urls as django_ariadne_jwt_urls


    urlpatterns = [
        ...
        url(r'^', include(django_ariadne_jwt_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
