# synology
Synology personnal hack, info, tools &amp; source code

Currently only contains patches to get hauppauge WinTV functional.

Working:
- em28xx: 1st tuner detected & loading firmware ok
Not working:
- lgdt3306a: crash probably due to i2c mux calls used for 2nd tuner not yet ported to em28xx.
