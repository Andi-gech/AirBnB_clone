# AirBnB_clone
The BaseModel class is a parent class for other classes in the HBnB project. It defines common attributes and methods that can be used by other classes to simplify their implementation.
The Amenity class represents an amenity in the HBnB project. It is a subclass of the BaseModel class and inherits its common attributes and methods.
he FileStorage class is an implementation of a simple storage engine that allows for the saving and retrieval of Python objects to and from a JSON file. It has the following attributes and methods:

Attributes:

__file_path: a string representing the path to the JSON file that will be used for saving and retrieving objects.
__objects: a dictionary containing the objects that have been instantiated.
Methods:

all(): returns the dictionary of instantiated objects.
new(obj): adds a new object to the dictionary of instantiated objects.
save(): serializes the dictionary of instantiated objects to a JSON file.
reload(): deserializes the JSON file to the dictionary of instantiated objects, if it exists.
The FileStorage class is used by the other classes in the project to persist and retrieve object data.
To create a user using this HBnB console, you can use the create command followed by the User class name. For example:

*******************************************************************************************************
(hbnb) create User
********************************************************************************
This will create a new user instance and return its ID. Then you can use the update command to set its attributes, for example:

*******************************************************************************************
(hbnb) update User 239d6b7e-f1b2-42b2-932d-6bt4b8c59c9f9 email "Andi@example.com"
(hbnb) update User 239d6b7e-f1b2-42b2-932d-6r40b8c59c9f9 password "mypadddssword"