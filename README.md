#AirBnB_clone project

Welcome to this clone of the AirBnB website,That implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.
Commands

    Creating new objects (ex: a new User or a new Place)
    Retrieving an object from a file, a database etc…
    Performing operations on objects (count, compute stats, etc…)
    Updating attributes of an object
    Destroying an object
Examples

Interactive Mode

$ ./console.py

(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)

(hbnb) 

(hbnb) quit

$

Non-Interactive Mode

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
