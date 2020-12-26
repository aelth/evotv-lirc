![Logo](https://i.imgur.com/fzrDtr7.png)

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/aelth/evotv-lirc#license)

# LIRC codes for Evo TV remote.

The codes were sniffed using RPI (`gpio-ir` lib) and Keyes IR receiver using specific configuration and `irrecord ~/lircd.conf` command.

In order to use the codes, [IrScrutinizer](http://www.harctoolbox.org/IrScrutinizer.html) was used to convert
lirc codes to codes usable by [irplus](https://irplus-remote.github.io/).

Conversion was done because Evo TV remotes tend to die quickly, replacement is expensive and no public codes were available.
