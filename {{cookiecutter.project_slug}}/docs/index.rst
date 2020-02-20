Welcome to {{ cookiecutter.project_name }}'s documentation!
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   :glob:

   readme
   installation
   usage
   modules
   contributing
   {% if cookiecutter.create_author_file == 'y' -%}authors
   {% endif -%}history
   tutorials/*

Indices and tables
==================
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
