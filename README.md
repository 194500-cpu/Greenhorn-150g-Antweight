# Greenhorn-150g-Antweight
My 150g antweight wedgebot design (only 3dprinted parts excluding motors/batteries/board).

Key features and design choices I made:
1) The wedge is intetionally not flat at the bottom. It is more of a triangle pointing downwards, in order to have a higher surface clearance.
2) My antweight does NOT use TPU for its wedge, but rather 100% PLA+.  This because the rigid wedge will get under opponents using TPU wedges (90% of opponents).
3) Even when flipped, the bot can still move around.
4) A pointy end helps prevent it from lying on its back (imagine if your bot landed on the back but couldn't self-right -> loss)
5) Finally, the wedge is not flush with the top. The small amount of vertical face helps it to catch onto opponents, not just slide under them.

By combining all these features, I have created a deceptively simple design, which is beginner friendly and competitive.

-Colgation

**Bill of Materials**
-> 2x N20 Motors 6V - <img width="440" height="398" alt="image" src="https://github.com/user-attachments/assets/0cc9eaea-2967-4f1e-b460-f22566eeafc9" /> 
-> 2x Polulu Wheels (32mm x 7mm wheels for n20 motors) - https://www.pololu.com/product/1087
-> A Kakapo V2 board (IF you are confident in ESC/Receiver/Transmitter you can replace this with your own alternative) - https://combatrobotics.co.nz/products/kakapo-2a-v1-2?srsltid=AfmBOorcJZ9p2gLWG6NNb6qwdkI8eQIo_saxhcBDmlufdOuAXIksVP4v
-> 22 AWG Silicone Wire (I recommend stranded)
-> 3dprinted parts in the STL-files folder of this repository (You need to 3d print them, instructions on how are below)
-> A 2S LIHV battery - I used GNB 2S 7.6V 300mAh LiHV Battery 60C
-> 2x 10mm screws
-> a male and female JST connector
-> 2 Zipties

**3d Printer Settings**

USE PLA+ FILAMENT, AS IT IS FAR LESS BRITTLE THAN PLA

-> Nozzle Temperature: 220 'C
-> Bed Temperature: 60 'C
-> Print Speeds 
Initial layer: 50mm/s
Outer wall: 200mm/s
Inner wall: 300mm/s
-> Layer height: 0.2mm
-> Line width: 0.4mm
-> Infill density: 15%
-> Infill pattern: Grid
-> Wall count: 2
-> Supports: Standard (Needed for wedge and chassis)

**Assembly**
1) Push the wedge into the trapezium looking hole. It should be a bit resistant, so using a plastic hammer will help (it is friction fit)
2) *Skip to step 6 if you are not using a Kakapo v2 board: position the board so that you can see the labels on it, then solder a wire each to the two most right-hand side terminals. (*NOTE: The two outermost terminals are negative, while the other two are positive)
3) Repeat step 2 for the two most left-hand side terminals.
4) Take a male JST connector and solder its positive end to the BAT terminal and its negative end to the GND terminal adjacent to the BAT terminal.
5) Take a female JST connector and solder its positive end to the WEAP terminal and finally solder its negative end to the one remaining GND terminal.
6) Solder the wire in the M1 terminal to the positive tab of a N20 motor.
7) solder the wire next to the M1 terminal to the negative tab of the N20 motor.
8) Take a second N20 motor and solder the wire connected to the M2 terminal to the motor's positive tab, then the remaining wire onto the N20 motor's negative tab.
9) 
