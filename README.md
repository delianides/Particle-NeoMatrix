SparkCore NeoPixel Matrix
==========================

This is a port of Adafruit's NeoPixel Matrix [Library](https://github.com/adafruit/Adafruit_NeoMatrix) for the [Spark](http://spark.io). Porting this over was very easy thanks to the work done by [technobly](https://github.com/technobly) porting the NeoPixel [library](https://github.com/technobly/SparkCore-NeoPixel) over.

Installation
-----------

- You should be able to just add the library via the Web IDE and include "neomatrix.h" (It should add it for you)
- You can compile locally using the Particle CLI tool.

```bash
$ particle compile photon neomatrix-project --saveTo firmware.bin
$ particle flash --usb firmware.bin
```

Read the docs for more information with this method of updating the cores.

Resources/Prior Art
--------

- [Particle-NeoPixel](https://github.com/technobly/Particle-NeoPixel)
- [Adafruit_TFT](https://github.com/lbarrosoneto/Adafruit_TFT)
- [Adafruit NeoMatrix Uberguide](https://learn.adafruit.com/adafruit-neopixel-uberguide/neomatrix-library)

Contributions
------------

All of them. I'll probably compile them first to make sure but I can't image there's
too much to break.

Again, so much thanks to [technobly](https://github.com/technobly). Porting that
library over made this one pretty easy.

License
-------

See LICENSE
