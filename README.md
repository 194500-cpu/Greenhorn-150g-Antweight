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

**Important**
Even though I have included the STL files for the antweight bot, I find it better to use Onshape in order to host it to allow modifications and precise parameters. <br>
This is why I havbe included an Onshape document link here: https://cad.onshape.com/documents/7372a678bd67ffef3bf9fe75/w/b756b9b718aa94560d7b57d3/e/aa83c5eda608b85760f218dc?renderMode=0&uiState=6a596bcb6ef2740900decdec



**Bill of Materials**
-> 2x N20 Motors 6V <br>
-> 2x Polulu Wheels (32mm x 7mm wheels for n20 motors) - https://www.pololu.com/product/1087 <br>
-> A Kakapo V2 board (IF you are confident in ESC/Receiver/Transmitter you can replace this with your own alternative) - https://combatrobotics.co.nz/products/kakapo-2a-v1-2?srsltid=AfmBOorcJZ9p2gLWG6NNb6qwdkI8eQIo_saxhcBDmlufdOuAXIksVP4v <br>
-> 22 AWG Silicone Wire (I recommend stranded) <br>
-> 3dprinted parts in the STL-files folder of this repository (You need to 3d print them, instructions on how are below) <br>
-> A 2S LIHV battery - I used GNB 2S 7.6V 300mAh LiHV Battery 60C <br>
-> 2x M3 10mm screws <br>
-> a male and female JST connector <br>
-> 2 Zipties <br>
-> Blu-tack <br>

**3d Printer Settings**

USE PLA+ FILAMENT, AS IT IS FAR LESS BRITTLE THAN PLA

-> Nozzle Temperature: 220 'C <br>
-> Bed Temperature: 60 'C<br>
-> Print Speeds <br>
Initial layer: 50mm/s <br>
Outer wall: 200mm/s<br>
Inner wall: 300mm/s<br>
-> Layer height: 0.2mm<br>
-> Line width: 0.4mm<br>
-> Infill density: 15%<br>
-> Infill pattern: Grid<br>
-> Wall count: 2<br>
-> Supports: Standard (Needed for wedge and chassis)<br>




**Assembly**
1) Hammer the wedge into the trapezoid hole using a plastic hammer for a friction fit.
2) Align the Kakapo v2 board with the chassis holes and secure it using two 10mm M3 screws. (If you are not using a Kakapo v2 board, skip to step 5).
3) Solder wires to the two right-most terminals. (Note: Outermost is negative, inner is positive).
4) Repeat this process by soldering wires to the two left-most terminals.
5) Solder a male JST connector's positive wire to BAT and negative wire to the adjacent GND.
6) Solder a female JST connector's positive wire to WEAP and negative wire to the remaining GND.
7) Solder the M1 wire to the first N20 motor's positive tab, and the adjacent wire to its negative tab.
8) Solder the M2 wire to the second N20 motor's positive tab, and the final wire to its negative tab.
9) Press both N20 motors into their slots and secure them with zip-ties through the platform holes.
10) Press the wheels firmly onto the motor shafts.
11) Plug the LIHV battery into the male JST connector.
12) Place a small piece of blu-tack onto each of the four corner chassis columns.
13) Press the cover on.
14) FINISHED!


**Photos and Demo**
All photos and demos can be found in the "Photos" and "Demo" folders of this repository respectively.







    
