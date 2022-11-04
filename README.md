# AirBnB Clone - The Console
is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB. Currently we only implements the back-end console.

# The Console
* Create your data model
* Manage (create, update, destroy, etc) objects via a console / command interpreter
* Store and persist objects to a file (JSON file)
   * To Operate:

    ./console.py

# Files and Directories
## models directory:
will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance.
## tests directory:
will contain all unit tests.
## console.py file:
is the entry point of our command interpreter.
## models/base_model.py file:
is the base class of all our models. It contains common elements:
### attributes: 
id, created_at and updated_at
### methods: 
save() and to_json()
## models/engine directory:
will contain all storage classes (using the same prototype). For the moment you will have only one: file_storage.py.