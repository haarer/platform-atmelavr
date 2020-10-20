
# Fork of Atmel AVR: development platform for [PlatformIO](http://platformio.org)

The Motivation for the fork is to provide current toolchain from my toolchain project to platformio users. 
I recently tried using platformio as a development tool and like it very much. Because of its modular architecture it is very easy to support it with different toolchains, board definitions and so one. 

![alt text](https://github.com/haarer/platform-atmelavr/workflows/Examples/badge.svg "Atmel AVR development platform")

Atmel AVR 8- and 32-bit MCUs deliver a unique combination of performance, power efficiency and design flexibility. Optimized to speed time to market-and easily adapt to new ones-they are based on the industrys most code-efficient architecture for C and assembly programming.

* [Home](http://platformio.org/platforms/atmelavr) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/atmelavr.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Default version

```ini
platform = atmelavr
board = ...
...
```

## My version

```ini
platform = https://github.com/haarer/platform-atmelavr.git
board = ...
...
```

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/atmelavr.html).
