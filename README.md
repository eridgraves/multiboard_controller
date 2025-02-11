# multiboard_controller
A board to connect a single host to multiple dev/eval boards, each with:
- Power over USB
- USB (shared with above?) for Fastboot communication 
- Serial (RS-232)

Only one board can be active at a time.  The current board can be selected using a [switch/microcontroller]? and is displayed on a [screen/LEDs]?.

The idea is that this board gives a clean interface between my host PC and full rack of microcontrollers/SoMs without fiddling with wires. 