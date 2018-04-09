# About
This project is impementing the Farmer, Wolf, Goat, Cabbage Problem using Logism (logic gates, low level hardware, etc).

# Authors
This project was created by Jacob and Mackenzie Fulton as part of a class project for CS 2521 (Computer Architecture & Design) at the University of Minnesota, Duluth.

# How To Use
Open the circ file in logism. You can try to solve the puzzle while on the default sceen (the main circuit) by pressing the buttons on the top (F for farmer, W for wolf, etc).

When the puzzle is solved, you will see the colorful LED's light up. There is currently no reset button so if you wish to try the puzzle again you must backtrack, set the corresponding registers to 0 (just clck on them using the poke tool and set to 0), or just open the file again.

You must make sure that the clock simulation is on. You can enable it in the simulation settings. Because of the way a button in logism works, there is a bug where sometimes pressing a button for a legal move can result in the led not updating correctly. Try playing with the clock speed, I settled with 128hz.

# Preview
![ScreenShot](https://github.com/JakeFDev/FWGClogism/blob/master/Screenshot.png)

# Logic
This was the initial "Drawing on a napkin" logic we started with. It may help understand the project.
![ScreenShot](https://github.com/JakeFDev/FWGClogism/blob/master/Unknown.png)
