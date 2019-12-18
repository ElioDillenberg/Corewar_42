# Corewar (42 School Project)

Core War is a 1984 programming game created by D. G. Jones and A. K. Dewdney in which two or more battle programs (called "warriors") compete for control of a virtual computer. These battle programs are written in an abstract assembly language called Redcode.

This project can be broken down into two distinctive parts:

- The assembler: this is the program that will compile champions and translate them from the Redcode they are written in, into “Bytecode”. Bytecode is a machine code, which will be directly interpreted by the virtual machine.

- The virtual machine: It’s the “arena” in which champions will be executed. It offers various functions, all of which will be useful for the battle of the champions. Obviously, the virtual machine should allow for numerous simultaneous processes.

# How to run:

<pre>
git clone https://github.com/ElioDillenberg/Corewar_42.git corewar
cd corewar
make

To assemble your champions:
./asm champions/zork.s
./asm champions/Gagnant.s

To run the virtual arena:
./corewar zork.cor Gagnant.cor

use -v option for visualizer (uses ncurses library)
</pre>

Within the visualizer you can use following commands:

<pre>
"SPACE" : pauses the game
"+" : speeds up (game needs to be paused)
"-" : slows down (game needs to be paused)
</pre>

Enjoy!

NB: The official project subject can be found as PDF in the subject folder.
