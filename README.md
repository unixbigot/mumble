# Mumble - a very small GRBL

Mumble is a board for [the ESP32 port of GRBL](https://github.com/bdring/Grbl_Esp32), targetted at low-voltage stepper motors. 
It was designed for the Minigraph CNC sticker plotter, but is intended to be usable for other CNC experiments.

It exposes all the GRBL pins, and has three DRV8834 low-votage motor drivers on-board.   
Unlike the more popular A4988, the DRV8834 operates from motor voltage in the range 3v to 10.8v, making it suitable
for low-voltage miniature steppers.

The board also features a lithium battery charge controller.

