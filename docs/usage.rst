=====
Usage
=====

To use The Best Chinese Locale in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_bestzhlocale.apps.DjangoBestzhlocaleConfig',
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
