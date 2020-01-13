=============================
acdh-django-archeutils
=============================

.. image:: https://badge.fury.io/py/acdh-django-archeutils.svg
    :target: https://badge.fury.io/py/acdh-django-archeutils

Django-App to serialize a model class into arche-rdf


Quickstart
----------

Install acdh-archeutils:

    pip install acdh-django-archeutils

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'archeutils',
        ...
    )


Update your project's urls.py:

    .. code-block:: python

        urlpatterns = [
            ...
            url(r'^archeutils/', include('archeutils.urls', namespace='archeutils')),
            ...
          ]
