**Waliki** is an extensible wiki engine based on Flask.

It's a fork of `mgaitan/waliki`_  project

.. _mgaitan/waliki: https://github.com/mgaitan/waliki/

Setup
----------------

.. code-block:: bash

    pip install -r requirements.txt
    mkdir content
    cp config.py.template content/config.py

Modify gunicorn.py to set the ip address.

.. code-block:: python

    import os

    bind = "192.168.1.27:8000"

Start
-----------------

.. code-block:: bash

    gunicorn -c gunicorn.py app:app


