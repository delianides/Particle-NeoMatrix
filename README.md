SparkCore NeoPixel Matrix
==========================

This is a port of Adafruit's NeoPixel Matrix [Library](https://github.com/adafruit/Adafruit_NeoMatrix) for the [Spark](http://spark.io). Porting this over was very easy thanks to the work done by [technobly](https://github.com/technobly) porting the NeoPixel [library](https://github.com/technobly/SparkCore-NeoPixel) over.

Installation
-----------

- You should be able to just add the library via the Web IDE and include
  "neomatrix/neomatrix.h" (It should add it for you)
- You can compile locally using the Spark CLI tool.

Caveats
-------

I would love to be able to just package the matrix library independently of the
pixel and GFX libraries but there doesn't seem to be an easy way to do
that. So for now, both the NeoPixel Library and The Adafruit GFX library are
included in this repo.

Resouces
--------

- [SparkCore-NeoPixel](https://github.com/technobly/SparkCore-NeoPixel)
- [Adafruit_TFT](https://github.com/lbarrosoneto/Adafruit_TFT)

Contributions
------------

All of them. I'll probably compile them first to make sure but I can't image there's
too much to break.

License
-------

See LICENSE
