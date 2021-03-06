##### Added a function to set the calibration values manually. -0lumide

# Arduino Library for the Pololu QTR Reflectance Sensors

Version: 2.1.1
Release Date: 2014-05-02
"www.pololu.com":http://www.pololu.com/

## Summary

This is a library for the "Arduino":http://www.pololu.com/catalog/product/2191 that interfaces with the "Pololu QTR reflectance sensors":http://www.pololu.com/catalog/category/123 ("QTR-1A":http://www.pololu.com/catalog/product/958, "QTR-1RC":http://www.pololu.com/catalog/product/959, "QTR-8A":http://www.pololu.com/catalog/product/960, and "QTR-8RC":http://www.pololu.com/catalog/product/961).

For documentation, please see the "user's guide":http://www.pololu.com/docs/0J19 for the library on Pololu's website.

## Version History

* 2.1.1 (2014-05-02): Minor improvements to @read()@ behavior and whitespace cleanup.
* 2.1.0 (2013-04-18): Improved existing examples and added two new examples for printing raw values.
* 2.0.2 (2013-04-17): Made constructors initialize pointers to avoid possible problems.
* 2.0.1 (2012-09-13): Added a 200 us delay after emitter state changes to ensure sensors do not start being sampled before the LEDs turn on/off.
* 2.0.0 (2012-02-14): Initial release of library on GitHub (with Arduino 1.0 compatibility).
