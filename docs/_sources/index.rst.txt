.. grfc documentation master file, created by
   sphinx-quickstart on Fri Mar 29 09:03:16 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to GRFC's documentation!
================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   roster
   grfcapp
   game
   grfc

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Technology Stack
================

* Heroku hosting
    + Environment variables
        + Using the CLI
        + heroku config:set FLASK_ENV=production
    + FLASK_ENV
    + FLASK_APP
* Flask
    + Talisman 
* JQuery
* SQLite

Application Overview
====================

The application's initial screen is the login screen. Users are pre-signed up, with usernames and passwords stored in the database.

Running Locally
---------------

.. code-block:: python

   export FLASK_ENV=development
   FLASK_APP=./wsgi.py flask run

Development And Unit Test
-------------------------

The folder `test` contains the test files that can be run wity *pytest*. Before running the tests, the above environment variable, `FLASK_APP` should be set.
