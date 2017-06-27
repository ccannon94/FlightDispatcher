# Flight Dispatcher Specification
## Kids In Flight

This document specifies the _Flight Dispatcher_ suite, designed for use by "Kids
in Flight". It will provide real-time tracking for the ground crew of families
in registered to fly and planes available.

#### Designed by: Chris Cannon [@ccannon94](https://github.com/ccannon94)

## Host System

The host system will be an ARM-based Raspbian system with a mySQL database.
The host system will connect to the clients via Ethernet cables.

## Client System

The clients will run a Java app to manage and manipulate data from the host.
