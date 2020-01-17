=============================
The Best Chinese Locale
=============================

Collect the best chinese translation.

.. image:: https://badge.fury.io/py/django-bestzhlocale.svg
    :target: https://badge.fury.io/py/django-bestzhlocale

.. image:: https://travis-ci.org/daimon99/django-bestzhlocale.svg?branch=master
    :target: https://travis-ci.org/daimon99/django-bestzhlocale

.. image:: https://codecov.io/gh/daimon99/django-bestzhlocale/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/daimon99/django-bestzhlocale

The best Chinese locale.

Documentation
-------------

The full documentation is at https://django-bestzhlocale.readthedocs.io.

Quickstart
----------

Install The Best Chinese Locale::

    pip install django-bestzhlocale

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_bestzhlocale',
        ...
    )

Add The Best Chinese Locale's URL patterns:

.. code-block:: python

    from django_bestzhlocale import urls as django_bestzhlocale_urls


    urlpatterns = [
        ...
        url(r'^', include(django_bestzhlocale_urls)),
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
