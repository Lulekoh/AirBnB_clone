0x00. AirBnB clone - The console

#Description

This is the initial stage of our endeavor to develop a simple copy of the AirBnB online application. To control the objects of the entire project in this initial phase, we will build a simple console using the Cmd Python module, allowing us to implement the methods create, show, update, all, and destroy to the existing classes and subclasses.

#Enviroment

Python3 (version 3.7.4) is used in Ubuntu 20.04LTS to create the console.

#Requirements 

python3 and pep8 style corrector skills, command line interpreter proficiency, and access to a computer running Ubuntu 20.04.

#Command Interpreter 

managing oobjects of the project:

. Create a new object (ex: a new User or a new Place)
. Retrieve an object from a file, a database etc…
. Do operations on objects (count, compute stats, etc…)
. Update attributes of an object
. Destroy an object

#Installation

https://github.com/Lulekoh/AirBnB_clone.git

#Examples

Execution
Your shell should work like this in interactive mode:

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$

#STRUCTURES

. README.md
. Authors
. Tests
. Models
. Console.py
