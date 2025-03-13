<!---
# cspell: ignore venv sleeperservice Elgato
---> 

# sleeperservice

A basic Windows tray utility that enables (forces) sleep or hibernate when Windows
system required power requests prevent switching to these standby/suspend states. 

This utility is specifically designed to address a problem with Elgato's Wave Link 
software. However, the implementation should allow it to address other system required
power requests (`SYSTEM: [DRIVER]`). It also provides a general purpose override that
suspends Windows after a specified idle time (for those cases where Windows just ignores
what the user actually wants it to do ...).

# Change Log

**v0.0.1** Proof of concept. 

## Breaking

Empty. 

## New Features

None yet.
