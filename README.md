# Project Name: HW 4 Aleatoric
**Name: Carson Hansen**


**Description**\
 This program will take user input and plays a sequence of notes, most of which are randomly selected from a major scale.

**To build this program**\
To build this program, you will need to install the following to get the program to run. Once these are installed, you will want to create the .exe by typing 'make'. Once the makefile has been created, you can run the program like a normal .exe and can choose to use arguments or run the program without them. Argument usage is described later in this document.

*Installs the sfml library that is used:*\
**sudo apt-get install libsfml-dev** 

*Installs the g++ compiler that is used to compile the program:*\
**sudo apt-get install g++**

**How to use command line arguments**\
You can use any amount of the following command line arguments or none if you choose and default values will be used.\
***--root[x]*** This is the root tone of the scale, where x is a valid MIDI key from 21-115\
***--beats[x]*** Number of beats per measure, where x is a whole number greater than 0\
***--bpm[x]*** number of beats per minute, where x is a value greater than 0.0\
***--ramp[x]*** fraction of the beats time for the attack and release time for the note evelope, where x is between 0.0 - 0.5\
***--accent[x]*** volume of the first beat of each measure, where x is between 0.0 - 10.0\
***--volume[x]*** volume of the unaccented beats of each measure, where x is between 0.0-10.0\
\
**Example of how arguments may be used**\
./Aleatoirc --bpm[120] --volume[8] --root[64]






