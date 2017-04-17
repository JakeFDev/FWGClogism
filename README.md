# FWGClogism
About
---------------------------------------------------------------------------------------------------
Implementing the Farmer Wolf Goat Cabbage problem using logism (logic gates and low level hardware, etc)
This was created for CS 2521 at University of Minnesota, Duluth as a team project by Jacob & Mackenzie Fulton
---------------------------------------------------------------------------------------------------

How to use, notes
---------------------------------------------------------------------------------------------------
Open the circ file in logism. You can try to solve the puzzle while on the default sceen (the main circuit) by
pressing the buttons on the top (F for farmer, W for wolf, etc). 

When the puzzle is solved, you will see the colorful LED's light up. There is currently no reset button so if you wish to try the puzzle again you must backtrack, set the corresponding registers to 0 (just clck on them using the poke tool and set to 0), or just open the file again.

You must make sure that the clock simulation is on. You can enable it in the simulation settings.
Because of the way a button in logism works, there is a bug where sometimes pressing a button for
a legal move can result in the led not updating correctly. Try playing with the clock speed, I settled
with 128hz. 

---------------------------------------------------------------------------------------------------
