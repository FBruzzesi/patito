Overview
========

.. toctree::
   :hidden:
   :titlesonly:

   Tutorials - User Guide <tutorial/index>
   api/index
   license

Patito offers a simple way to declare pydantic data models which double as schema for your polars data frames.
These schema can be used for:

| 👮 Simple and performant data frame validation.
| 🧪 Easy generation of valid mock data frames for tests.\
| 🐍 Retrieve and represent singular rows in an object-oriented manner.\
| 🧠 Provide a single source of truth for the core data models in your code base.

Patito has first-class support for `polars <https://github.com/pola-rs/polars>`_, a *"blazingly fast DataFrames library written in Rust"*.

Installation
------------

You can simply install Patito with :code:`pip` like so:

.. code-block:: console

   pip install patito

Developer Notes
---------------

To run the noxfile with pyenv, first run
```
pyenv local 3.8 3.9 3.10 3.11
```
