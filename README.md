This project provides the following:

* `*.c` — a fast base64 encoding routine based on [libb64](http://libb64.sourceforge.net/).
* `base64.cry` — a Cryptol specification of base64.

# Usage

To build the C code:

    $ make

To run the C code:

    $ echo -n 'foobar' | ./b64enc -
    Zm9vYmFy

# License

C code: public domain, without any warranty.
Everything else: MIT license.

# Contributing

Please report bugs and feature requests using the [GitHub issue tracker](https://github.com/davidlazar/base64/issues).
