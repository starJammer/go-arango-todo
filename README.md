# go-arango-todo
A small pet project that uses go and arangodb to drive a small todo app.

The directory structure is as follows

    _ web - The go server that serves the html and assets. The executable comes from here.
    _ middle - Go based functionality to be used by web. It that acts as gateway to the database
    _ db - database level code that handles persistence and has model information
    _ etc
     |___arangodb - contains configuration files for arangodb as well as setup scripts to create the database
     |___web - contains configuration files for web server
