# NESGuide

This repository is related to the [video](https://www.youtube.com/watch?v=V5uWqdK92i0), a tutorial for how to program the Nintendo Entertainment System (NES) and the Family Computer (Famicom). The final assembly file is given as an example of what a basic starter program should look like.

To compile this program, please download [CC65](https://github.com/cc65/cc65)

Then run the following commands:
```
C:\PathTo\cc65\bin\ca65 C:\PathTo\cart.s -o C:\PathTo\cart.o -t nes
C:\PathTo\cc65\bin\ld65 C:\PathTo\cart.o -o C:\PathTo\cart.nes -t nes
```

Where **C:\PathTo** is the path to where your cc65 folder is located and then for the files, to wherever your cart.s file is located at. The output (**-o**) of the object and NES files can be changed to whatever destination is desired. 

The result will be a .NES file located at C:\PathTo\cart.nes which can then be run using an NES Emulator. 
