<div align="center">

# 🎮 Game Specific Patches & DLL Wrappers  

***created and maintained by***

[![Chip-Biscuit Website](https://img.shields.io/badge/Chip--Biscuit-Website-blue?style=for-the-badge)](https://chip-biscuit.github.io/)

Reverse Engineering • Programming • Patching • Game Improvements • DLL Creation 

</div>


# 102-Dalmatians-PC-Controller-Support

Features full controller support, including right stick camera movement and switch puppies button (aren't present in the default configs of the game)

Supports only Xbox controllers (or controllers, emulated as an Xbox one, via tools such as DS4Windows or x360ce.)

It is strongly recommended to NOT change "switch puppies" and "look left/right" options in the control menu. Since the game doesn't support right stick camera movement by default, default values from this menu are utilized.

Default controller buttons for Jump, Bark, Sniff and Roll, as well as default look left/right controller buttons, are a bit all over the place. It is recommended to change them in the game "control" menu after applying this fix to the game folder.

You can fully edit the controller mapping in the d3d9.ini instructions are all included inside of the ini.

# Recommended controller buttons (Under Config 2) are:

Jump - A (Joy button1)
Bark - X (Joy button3)
Sniff - Y (Joy button4)
Roll - B (Joy button2)
Look Left - LB (Joy button5)
Look Right - RB (Joy button6)

# Aside of those buttons, there's the buttons mapped by default:

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

Brought to you by Fix Enhancers - https://fixenhancers.wixsite.com/fix-enhancers

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

