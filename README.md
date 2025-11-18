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

This fix also includes Elisha's wrapper, which also fixes Widescreen resolution, and adds anti-aliasing and Anisotropic Filtering for smoother image. (can be turned off in dxwrapper.ini)

Installation:
-Drop the files from archive into the game folder (next to pcdogs.exe)
-(optional) If the game added to the steam library, be sure to turn Steam Input off for the game.
-Check "Important" section below.


![102dalmpcinputconfig](https://github.com/user-attachments/assets/5d13984c-0919-49be-b0be-47860a05dbeb)

# Alternative user profile if the above doesn't work:  
[![PCGamingWiki](https://img.shields.io/badge/PCGamingWiki-File%20Page-0066cc?style=flat&logo=pcgamingwiki&logoColor=white)](https://community.pcgamingwiki.com/files/file/3729-chipxinput-102-dalmatians-controller-calibration-fix/)

# If you experience double input 

An effect of this fix can be the fact that in some cases it will make native X-input work again in your game, in that case it is important to note that in this fix for each input inside of the .ini file you can put ***= NONE*** 

**for example** 

***A = NONE***

***B = NONE***

you can do this for every input on the Xbox controller in the .ini file

this will disable completely the custom (chip-xinput) layer for the game but the native x-input will still work you can either put NONE for each key as in the example above OR at the top of the ini set  ***output = 0***

Otherwise you would have an xbox button doing 2 inputs inside of the game like: 

**Native A = Jump in game + Chip xinput = LMB in game at the same time**

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

