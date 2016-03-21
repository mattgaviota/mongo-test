Prueba
======

.. code-block:: sh

    npm install
    node app.js

Requisitos
==========

Hay que tener una BD en MongoDB llamada video, con una collection llamada movies
con la siguiente estructura.

+-------+------------------+
|  Key  |    Value Type    |
+=======+==================+
| title | <type 'unicode'> |
+-------+------------------+
|  _id  |      other       |
+-------+------------------+
|  imdb | <type 'unicode'> |
+-------+------------------+
|  year | <type 'unicode'> |
+-------+------------------+
