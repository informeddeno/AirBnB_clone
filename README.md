
0x00. AirBnB clone - The console

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine

The console creates a new object; retrieves an object from a file; operates on objects; destroys an object.

installation: clone the repository AirBnB_clone.git, cd into the directory and run command bash ./console.py

execution: In interactive mode: ./console.py (hbnb) help

exit: quit

Operating System: Ubuntu 20.04 using Python 3.8.3 and edited via emacs.
