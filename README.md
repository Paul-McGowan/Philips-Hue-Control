# Philips-Hue-Control
A collection of Python scripts to control the lights on a Philips Hue hub

These scripts use the phue library (pip install phue) to control your Philips Hue lights.

You need to run the 'key' script first, and follow the instructions to generate a key
with which to access the Hue hub. This is pasted into the two other files together with
the IP address of your Hue hub.

The 'bulbs' script lists all the lights/bulbs on the Hue hub, together with the numeric bulb ID
which is a number between 1 and 64. These numbers are how you address the lights.

Now edit the 'hue' script, adding the IP address of the Hue hub and the key.
You can also create groups to control and create new colours too.
There is also a variable to specify the filename of the restore program.

Usage:

hue [command] [bulb(s)]/[group]

