# CNCPlotter Arduino Sketch

Based on the Mini_cnc_plotter_firmware sketch from https://github.com/adidax/mini_cnc_plotter_firmware

Working version - based on code from https://github.com/adidax/mini_cnc_plotter_firmware

Additional features:
 - Auto Home and uses midpoint as home Use 'H' command
 - Can disable motors using M18 command (got annoyed by motor noise)
 - Verbose logging over serial connection can ben toggled using 'V' command)
 
This sketch does nothing on its own. It requires a companion app to feed it with basic commands currently over the serial connection.
There are a few around however, I have written an OSX companion app which supports all the new features I've added here.
This is available from https://github.com/AndyQ/CNCPlotter
 
 
In addition, I'd like to thank @CNC World for creating the Instructable - http://www.instructables.com/id/How-to-Make-Arduino-Based-Mini-CNC-Plotter-Using-D which got my interest going.

**Disclaimer - this works nicely for my plotter, however, it may not work on your plotter. You use this software entirely at your own risk.**
