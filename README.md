# CSE210-06


# Getting Started
---

* Python 3.8.0
* Raylib Python CFFI 3.7

---

# Team contributors

```
Daniel Harris har21072@byui.edu
Weylin Douglas  weylin76@msn.com
Christian Mijangos  mij1700@byui.edu
Christi Johnson   joh21088@byui.edu
```

# Holy War game 

Holy War is a game where the players try to cut each other off using snakes representing the Univeristy of Utah (Red) and Brigham Young University (Blue).  

Holy war is played according to the following rules.

Players can move up, down, left and right...
Red player moves using the W, S, A and D keys.
Blue player two moves using the I, K, J and L keys.
Each player's tail grows as they move and eat the spread food. 
Players try to maneuver so the opponent collides with their tail. 
If a player collides with their opponent's trail the player loses. 


# Getting Started

---
Make sure you have Python 3.8.0 or newer and Raylib Python CFFI 3.7 installed and running on your machine. You can install Raylib Python CFFI by opening a terminal and running the following command.
```
python3 -m pip install raylib
```
After you've installed the required libraries, open a terminal and browse to the project's root folder. Start the program by running the following command.

```
python3 Holy War 
```
You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the hunter folder and click the "run" icon.

# Project Structure

The project files and folders are organized as follows:
```
+-- CSE210-06           (source code for game)
  +-- holy_war          (specific game classes)
  +-- __main__.py       (entry point for program)
  +-- constants.py      (game screen size)
+-- README.md           (general info)
```
