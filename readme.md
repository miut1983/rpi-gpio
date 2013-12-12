This project is gathered from multiple other projects;

- [Python GPIO module by Ben Croston](https://code.google.com/p/raspberry-gpio-python/)
- [Lua binding to that library by Andre Simon](http://www.andre-simon.de/doku/rpi_gpio_lua/en/rpi_gpio_lua.html)

It contains two branches, the first being [source_python](https://github.com/Tieske/rpi-gpio/tree/source_python), which is (so far) an exact copy of Ben Crostons' code (all releases). The second one is [master](https://github.com/Tieske/rpi-gpio/tree/master) which is Andre Simons' code, merged with the `source_python` branch, and some of my own (planned) changes.

This allows for new updates to the library to be added to the `source_python` branch and be merged with the Lua binding in `master`. And it has all source code in one repo.

License
=======
See [Ben Crostons' license](https://github.com/Tieske/rpi-gpio/blob/master/LICENCE.txt), and [Andre Simons' license](https://github.com/Tieske/rpi-gpio/blob/master/lua/LICENCE.txt).
My modifications are under the same license as [Andre Simons'](https://github.com/Tieske/rpi-gpio/blob/master/lua/LICENCE.txt)
