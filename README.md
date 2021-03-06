# Enigma Machine Emulator

An Enigma machine emulator written in C#.

## Enigma model
The project models the Enigma I, from ~1930.

## Features
All the features the real Enigma I had. Plugboard, rotors with arbitrary order, and three available reflectors. Produces the same output as the real machine.

### Todo
* Improve the settings query in Program.cs
    * Make it fail safe
    * Make the code prettier

### Future work
* Make the machine compatible with the later Enigma models, M3 and M4.
    * Expand the machine with more rotors (M3 and M4 had up to eight).
    * Expand the machine with more reflectors (Beta and Gamma)
* Translate the code into JavaScript and make a web version of the machine.

### References and thanks
Other simulators that helped in the research and when testing if the output was correct:
* http://startpad.googlecode.com/hg/labs/js/enigma/enigma-sim.html
* https://people.physik.hu-berlin.de/~palloks/js/enigma/enigma-i+m3_v16.html
* http://enigma.louisedade.co.uk/enigma.html

Technical details about the Enigma:
* http://enigma.louisedade.co.uk/howitworks.html
* http://users.telenet.be/d.rijmenants/en/enigmatech.htm
* https://en.wikipedia.org/wiki/Enigma_machine#Design
* https://en.wikipedia.org/wiki/Enigma_rotor_details
