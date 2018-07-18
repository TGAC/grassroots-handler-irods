# iRODS handler {#irods_handler_guide}

The iRODS handler allows the Grassroots Server to access data objects and collections stored on an [iRODS](https://irods.org) system.

Handlers are components that abstract out common I/O operations such as opening and closing files as well as reading and writing to them. By using the Handler API, any component in the Grassroots infrastructure can access these resources without having to worry about how or where they are stored.
 
## Installation

To build this handler, you need the [grassroots core](https://github.com/TGAC/grassroots-core) and [grassroots build config](https://github.com/TGAC/grassroots-build-config) installed and configured. 

The files to build the iRODS handler are in the ```build/<platform>``` directory. 

### Linux

If you enter this directory 

```
cd build/linux
```

you can then build the service by typing

```
make all
```

and then 

```
make install
```

to install the handler into the Grassroots system where it will be available for use immediately.

