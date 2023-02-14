# The AirBnB clone :hotel::hotel:

This is the first step towards building your first full web application: the AirBnB clone.
Building the Console is very important as this is the first step that will be used to build subsequent steps such as HTML/CSS templating, database storage, API, front-end integration…

The Console consists of a command-line interface for data management, and the base classes for the storage of this data.

The Objectives of this project is being able to:
	-create a parent class (called BaseModel);initialization, serialization and deserialization of your future instances
	-create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
	-create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
	-create the first abstracted storage engine of the project: File storage.
	-create all unittests to validate all our classes and storage engine.

## The Console
### functionalities
-Create a new object (ex: a new User or a new Place)
-Retrieve an object from a file, a database etc...
-Do operations on objects (count, compute stats, etc...)
-Update attributes of an object
-Destroy an object

### Console and Command Usage
The console is a Unix shell-like command line user interface provided by the python CmdModule
It prints a prompt and waits for the user input.

## Models


