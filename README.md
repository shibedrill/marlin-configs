# Marlin Configurations

## License Notice

This code is not mine. It is a derivative of Marlin's [maintained example configurations](https://github.com/MarlinFirmware/Configurations/tree/bugfix-2.1.x/config/examples/). I altered it slightly on December 26th, 2024, to work with my modified printer. The original license, along with this notice, are provided in order to conform to the terms of the original code's license.

## About

This is a set of Marlin configuration files for my modified Ender 3 Pro. The relevant modifications include:

- A filament runout sensor
- A BLtouch bed leveling probe
- A BigTreeTech SKR Mini E3 3.0 mainboard

I had to modify the configuration files to get the sensors working properly, so in order to avoid having to remember all my modifications when recompiling, I decided to commit the code to a repository.

## Reuse

Feel free to use this configuration on your own printer, but only if it is the same exact printer with the same exact mainboard. If you don't have a BLtouch, be careful to ensure you comment out all the options relevant to Z-homing with the probe. Otherwise, it may dig the nozzle into the bed while homing the Z axis.

If you are making your own changes, be sure to look through the license before publishing them.
