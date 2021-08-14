# SiIva Note Importer For FNF
Tool to convert charts made in FL Studio's piano roll to .json files usable in [Friday Night Funkin'](https://github.com/ninjamuffin99/Funkin).
Imagine using FnF's chart editor smh

# HOW DO I USE THIS??!??
### JSON to FLP
Open SNIFF dot exe and select the \*.json file. The program should create a fl studio sequence file, which behaves like a midi file. If you understand how SNIFF works (you have to play around with it), you'll know what the notes mean.

### FLP (MIDI) TO JSON
Open the "Friday Night Funkin'" template. Fill in the notes for all patterns (it should be straightforward, as the project template __labels everything__). Afterwards, you can save the project as the same name or a different name. Open SNIFF, select the \*.flp file you want to target. If you've got it correct, the program will ask you which characters should be associated with the chart, the BPM, and whether you want separate voices. You will then be prompted to enter scroll speeds for each difficulty. Each time you enter a scroll speed, you will be prompted to save a \*.json file for that difficulty. If you are doing all difficulties, you will do this three times.

# Changes
Added Kade Engine 1.6 support. See details on release.

# Credits
The original repo can be found here: https://github.com/PrincessMtH/SNIFF
