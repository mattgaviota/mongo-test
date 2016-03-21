Prueba
======

.. code-block:: sh

    npm install
    node app.js

Requisitos
==========

Hay que tener una BD en MongoDB llamada video, con una collection llamada movies
con la siguiente estructura.

.. code-block:: json

    movies: {
        'title': String,
        'year': Number,
        'imdb': String
    }
