NCSA Mosaic
===========

![GitHub viewed with Mosaic](http://github.com/downloads/alandipert/ncsa-mosaic/github.png "GitHub with Mosaic")

This is NCSA Mosaic 2.7, one of the first graphical web browsers.
If you're on Ubuntu or something like it, your time machine is fueled
up and ready to go.  Follow the instructions below to build and run.

Many thanks to [Sean MacLennan and Alan Wylie](http://seanm.ca/mosaic/) for doing the heavy lifting.

Building
--------

* First, install these packages:

      sudo apt-get install build-essential libmotif3 libmotif-dev libpng3 x11-proto-print-dev libxmu-headers libxpm-dev libxmu-dev

* Next, build with:

      make linux

* Run!

      src/Mosaic
