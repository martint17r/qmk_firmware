# ErgoDox lefthanded Mac OS VIM configuration

## build

```bash
export PATH=/usr/local/Cellar/avr-gcc@7/7.3.0/bin/:$PATH
make ergodox_ez:mtvb
teensy_loader_cli -mmcu=atmega32u4 -w -v ergodox_ez_mtvb.hex
```

## Changelog

* Dec 2016:
  * Added LED keys
  * Refreshed layout graphic, comes from http://configure.ergodox-ez.com now.
* Sep 22, 2016:
  * Created a new key in layer 1 (bottom-corner key) that resets the EEPROM.
* Feb 2, 2016 (V1.1): 
  * Made the right-hand quote key double as Cmd/Win on hold. So you get ' when you tap it, " when you tap it with Shift, and Cmd or Win when you hold it. You can then use it as a modifier, or just press and hold it for a moment (and then let go) to send a single Cmd or Win keystroke (handy for opening the Start menu on Windows).

This is what we ship with out of the factory. :) The image says it all:

![Default](https://i.imgur.com/Be53jH7.png)
