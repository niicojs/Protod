Protod - Protobuf's metadata extractor
(c) 2012, Sysdream (d.cauquil@sysdream.com)

WHAT IS PROTOD ?
----------------

Protod is a tool able to extract Google's protobuf metadata from any binary
file. This version has been designed to cover every file format.

The goal of this tool is to recover serialized protobuf's metadata inserted
at compilation time inside an executable, and to make it available as .proto
file, ready to compile with protoc (protobuf's compiler).

For further information on Google's protobuf library, please see:

https://developers.google.com/protocol-buffers/docs/overview


Reference:
    (1) https://github.com/protocolbuffers/protobuf
    (2) https://sysdream.com/news/lab/2012-06-06-reverse-engineering-of-protobuf-based-applications/
    (3) https://stackoverflow.com/questions/13937882/parsing-protocol-buffers-without-knowing-the-proto/14027080
    (4) https://developers.google.com/protocol-buffers/docs/overview



HOW TO USE THIS TOOL ?
----------------------

Its usage is very simple. Here is a sample:

To extract every metadata file (.proto) from a given executable:

$ python protod.py somebinary


IS THIS TOOL LIMITED ?
----------------------

Current version does not support every kind of fields, we are aware of this.
It was developed as a proof-of-concept to demonstrate this technique, and of
course you are more than welcome to contribute !

Feel free to fork this project on Github, and let us know about your issues
and ideas !


THANKS
------

Great thanks to UNclePecos for his time, and all the Sysdream's staff for
their support.

New update by thomas for  support python3.
