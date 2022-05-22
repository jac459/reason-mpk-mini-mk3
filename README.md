# reason-mpk-mini-mk3
Reason Remote files for Akai MPK Mini MKIII

This is a fork of the excellent work of philoSurfer.
##### Intent is to :
###### increase the number of controls per synths using groups ===> Use the drumpad to change the group you control, allowing to control 64 to 80 elements in the synth with the 8 knobs of the mk3 (ex: pad1 to control the Engine 1 of Scenic, pad2 for Engine 2, pad3 Filter 1, etc...)

So far the following Synths have rich controls:
### Reason: Europa, Thor, Subtractor, Malstrom, Algoritm, Parsec(1&2), Scenic and Friktion
### Rob Papen: Go2
### Robotic Bean: Resonans
### Synapse: The Legend, Antidote
### Blamsoft: Expanse
### Softtube: Saturation knob (only 2 knobs, lol)
### Lectric Panda: Nostromo (80 elements controlled)

Following added devices have basic controls (8 or 16 knobs):
### Reason: Quartet, Sweeper, BVX Vocoder, Layers, Layers Wave Edition, Radical Keys, Processed Piano, Electric Bass, Complex1, Reason Drum Kits, UMPF Club Drums, UMPF Retro Beats, Monotone, Reason Electric Bass, Mimic.
### Audiorealism: abl3

Many other devices are supported thanks to the work of philosurfer: all the other reason devices (as far as I have seen), ReSpire, ElectroClap, ...




Create a working set of remote files for the new Akai MPK Mini MKIII, which currently does not have a supported set of mappings.  The MKII mappings do not work.


# Install for macOS
Copy and paste the following command to install the appropriate Lua and Remote files.

You will be _prompted for your macOS user password_ to move the files to the correct location. This is a one time event.
```
git clone https://github.com/philoSurfer/reason-mpk-mini-mk3.git && cd reason-mpk-mini-mk3; chmod +x install-macOS.sh; sudo sh ./install-macOS.sh;
```

Once installed, restart Reason and proceed to plugin your MPK Mini MK3 and mannualy add it via the settings


# Install for Windows - NOT WORKING
I need help with a windows script to install, as I do not have a windows machine to test on.PRs accepeted
==> manual install is ultra easy though, you just have to go to the "remote" folder of your reason installation and place the folders with the both lua files and remotemap (if you don't see what I mean, just look what is in the remote folder. 


# Contribution - Remote mapping
If you would like to work on adding remote maps, feel free to edit the appropriate files and submit PRs.   

You can edit the files in the cloned repo and re-run the install script to copy the changes to the default production environment for these files.

# Program Change Controls Mapping

The following is the current "Prog Change" mapping

| Button | Function|
| :---: | ------|
| --  | --- Bank A ---  |
| __A1__  |  Stop  |
| __A2__  |  Play  |
| __A3__  |  Record |
| __A4__  |  Target Next Track |
| __A5__  |  Click On/Off |
| __A6__  |  Loop On/Off  |
| __A7__  |  Auto-quantize  |
| __A8__  |  Target Previous Track  |
| -- | --- Bank B --- |
| __B9__  |  Select Prev Patch for Target Device  |
| __B10__ | |
| __B11__ | |
| __B12__ | |
| __B13__ | Select Next Patch for Target Device |
| __B14__ | |
| __B15__ | |
| __B16__ | |
