barrel_encoding
=====


A sortable serialization library This library offers a serialization format (a la term_to_binary()) that preserves the Erlang term order. This serve the purpose of barrel to store json paths in the database.

Encoded terms are:

* list of binaries
* binaries
* atom
* integers unsigned or not
* floats

The library allows to encode/decode the data in ascending or descending order.

Build
-----

    $ rebar3 compile
