# Launchpad4ATEM

These scripts for [JustMacros](https://secure.justmacros.tv/) allow it to control
an [ATEM Television Studio](https://www.blackmagicdesign.com/products/atemtelevisionstudio)
from a [Novation Launchpad Mini](https://novationmusic.de/launch/launchpad-mini)

It shouldn't be too hard to adopt it to other ATEMs if needed.

## Installation
Move the *.ATEMLuaScripts files to the "Macros" folder of your JustMacros installation.
Move the InitLaunchpad macro to the AutoExec folder, if you want to initialize the Launchpad
on startup.

## Known issues
The ATEM Software Control grabs all MIDI devices on startup. JustMacros can not connect to
the Launchpad anymore if it is started after ATEM Software Control. You need to start
JustMacros first, before starting ATEM Software Control.