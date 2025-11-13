<div align="center">

# 🎮 Game Specific Patches & DLL Wrappers  

***created and maintained by***

[![Chip-Biscuit Website](https://img.shields.io/badge/Chip--Biscuit-Website-blue?style=for-the-badge)](https://chip-biscuit.github.io/)

Reverse Engineering • Programming • Patching • Game Improvements • DLL Creation 

</div>


# 102-Dalmatians-PC-Controller-Support

Features full controller support, including right stick camera movement and switch puppies button (aren't present in the default configs of the game)

Supports only Xbox controllers (or controllers, emulated as an Xbox one, via tools such as DS4Windows or x360ce.)

You can fully edit the controller mapping in the d3d9.ini instructions are all included inside of the ini.

# built-in controller input from the game

Go to releases and download 

***102DalmatiansController.zip***

unzip the folder and put the contents into the games installation location next to ***pcdogs***.exe then the following instructions: 

Features full controller support, including right stick camera movement and switch puppies button (aren't present in the default configs of the game). Supports only Xbox controllers.

This fix also includes Elisha's wrapper, which also fixes Widescreen resolution, and adds anti-aliasing and Anisotropic Filtering for smoother image. (can be turned off in dxwrapper.ini)

Installation:
-Drop the files from archive into the game folder (next to pcdogs.exe)
-(optional) If the game added to the steam library, be sure to turn Steam Input off for the game.
-Check "Important" section below.

# Important:

It is strongly recommended to NOT change "switch puppies" and "look left/right" in Config 1 options in the control menu. Since the game doesn't support right stick camera movement by default, default values from this menu are utilized.

Default controller buttons for Jump, Bark, Sniff and Roll, as well as default look left/right controller buttons (Config 2), are a bit all over the place. It is recommended to change them in the game "control" menu after installing the fix. To do so, you have to use keyboard, press "Enter" on each button and just then press any controller button you want to map.

# Recommended controller buttons (Under Config 2) are:
 
Jump - A (Joy button1)

Bark - X (Joy button3)

Sniff - Y (Joy button4)

Roll - B (Joy button2)

Look Left - LB (Joy button5)

Look Right - RB (Joy button6)
 

Aside of those buttons above, there's the buttons mapped by default:

BACK - Switch puppies

START - Pause menu 

Right stick - Camera movement

Left stick (press) - menu

DPAD - nothing

Triggers - nothing 

Bonus: If you want XBOX controller button prompts, change keyboard buttons to literal "X", "A", "B" and "Y" keyboard buttons (Buttons under Config 1) as shown on the screenshot.

<img width="2559" height="1439" alt="1_2" src="https://github.com/user-attachments/assets/434ffcf0-09aa-4b5e-8ce7-2230182bbfb6" />


<img width="1920" height="1080" alt="102dalmatians" src="https://github.com/user-attachments/assets/f5323ac4-9822-4921-8318-201e1e9d9b88" />

# Credits
Credit to Elisha Riedlinger for the base wrapper and 13 AG.

Credit to Elisha Riedlinger for dxwrapper

# Issues
If you have any issues please go to discord for help 

https://discord.gg/eVJ7sQH7Cc

# Chip-Biscuit
“Creating compatibility fixes and enhancements for legacy PC games.”



# Chip
- founder
- reverse engineer
- programmer
- developer
  
<img width="250" height="500" alt="my logoo" src="https://github.com/user-attachments/assets/9bb13d3f-0734-4f1d-b68f-14114b13744a" />

<br>

# Roman Nikolaev
<img width="100" height="100" alt="YouTube_Logo" src="https://github.com/user-attachments/assets/9ef381e5-a1e8-4806-bfdb-4499749307cf" /> <br>
- Role (Moderator, Tester) 

