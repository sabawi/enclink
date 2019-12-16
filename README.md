# enclink

enclink is a client/server encrypted communication daemon running on Linux

The following are required pre-reqs for a development environment:
1) OpenSSL dev libraries
    $ sudo apt install libssl-dev

2) Beest C++ libraries:
    $ sudo apt install libboost-all-dev


To build the project for Release binaries:
    $ make -f Makefile CONF=Release

To build the project for Debug binaries:
    $ make -f Makefile CONF=Debug
