# Mumble Errata

## V1.0
### Fixed
* ~J1 RTS and DTR are swapped, should use RTS=reset DTR=prog (design error)~
* ~No "hello world" LED (design improvement)~
* ~Servo power should connect to vBAT? (design error)~
* ~Order of buttons: [start, hold, abort (grbl reset), reset, (esp) program] (layout improvement)~
* ~Footprint for motor drivers has pins too close~

### To fix
* USB footprint does not have mid-placed pads for alternate connector (layout improvement)

### Notes
* Large switch pads are not connected (layout improvement)
*	- On switches ordered large pads are shorted (chassis).