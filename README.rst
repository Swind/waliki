**Waliki** is an extensible wiki engine based on Flask.

It's a fork of `mgaitan/waliki`_  project

.. mgaitan/waliki:: https://github.com/mgaitan/waliki/

Setup
----------------

.. code-block:: bash

    pip install -r requirements.txt

Start
-----------------

Modify gunicorn.py to set the ip address.

.. code-block:: python

    import os

    bind = "192.168.1.27:8000"

