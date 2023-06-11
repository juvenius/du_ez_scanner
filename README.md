# EZ Scanner

2022 Octuber DU Release UPDATED! 

Dual Universe Ore Node Finder Script, This script finds ore node location with just 4 points using the True-range multilateration Algorithm. 

You can see the full instalation and use tutorial video here:

[Dual Universe - EZ Scanner Script - Installation and Use Tutorial Video](https://www.youtube.com/watch?v=-dG060p57Iom)


### Features
- Simple **Main Panel** for easy unclutterd UI
- **Help Panel** for ingame help on how to use script
- Finds the node location with just 4 points
- Easily add and delete points without restarting script
- **Slider Panel** for a faster data entry (experimental) 
- Script easy pause and exit shortcuts
- Set parameters to have a more streamline workflow
- Auto pause mode **Paused Panel** after finding node location, to reduce GPU/CPU usage.
- Auto Exit and Auto Pause Timers
- Auto Scan after 4th Point

New:
- Sets the Result as **Destination Automatically**

### Requisites

Elements:
- Dynamic core
- Programing board
- Installed Script

# INSTALLATION AND USE

### Installation

- COPY ***du_ez_scanner.json*** in this repository to your clipboard
- PASTE the code ingame in your Programing Board- 

### Before you run your script
- Make sure you that your scaning node is in range of the Programing Board
- Be mindfull of your CPU / GPU usange, it is very intensive in computational resorces. If you see any problems with it when starting it **press ALT+9** to STOP the Script

### How to Use

On your desired scan location and with the programing board in range with the EZ Scanner Script running, do:

1) Open your ore node scanner and filter to just show the desired node type to scan
2) Scroll Mouse Wheel to match the distance of the node ping. Add point with Alt+3 and Remove with Alt+5.
3) Space your points at least 50 mts from each other, and never more than 2 points with the same altitude
4) When you have the 4 points, use Alt+4 to find node location
5) Set Destination with Link provided in the lua chat panel on your chat interface
6) Resume Paussed Script with Alt+8 if you want to take an other mesurement.
7) Exit Script (Alt+9)

### Good to know
- Always take points with more than 50 meters apart from each other and never more than 2 with the same elevation
- **Only Alioth Coords Tested ATM**, i havent test it yet on other planets
- After the node search the scrip will pause, resume if needed
- All points will be flused after search
- Keep the script paused to save GPU/CPU
- Change Script parameters for panels to be on/off at the start of the script
- The mouse scroll wheel has a aceleration multiplier, move it arround a bit to get the feeling of it 

### Keyboard Shortcuts

Alt+1 : Help\
Alt+2 : n/a\
Alt+3 : Add Point\
Alt+4 : Find Node \
Alt+5 : Delete Point \
Alt+6 : n/a\
Alt+7 : Tougle Slider On/Off\
Alt+8 : Pause | Resume Script\
Alt+9 : Exit App

## ABOUT

###  Versions
- 1.05 | 2022.10.20 | Current Stable Version

###  Author
- Juvenius Drakonius (Discord: Juvenius#2318), I'm learning to code and english is not my first languange...so be gentle.

### Acknowledgements
- Thank you to [d6rks1lv3rz3r0](https://github.com/d6rks1lv3rz3r0) for his script that helpme finished my own take on the problem. Check out his code [DU-Prospector](https://github.com/d6rks1lv3rz3r0/DU-Prospector)
- [Yamamushi](https://github.com/yamamushi) for just been an amazing help in building amazing code.
- To the [Rekium DU](https://discord.gg/Xy3Sk59p) [[du.rekium.org](du.rekium.org)] guys for pushing me to finish this code that i've been working for weeks to finish

### Planned Upgrades
- [x] Parameter: Auto-Scan on 4th point
- [x] Parameter: Auto-pause after finding coordinate link
- [x] Feature: Auto-pause after x time without movement
- [x] Feature: Multiplanet functionality
- [ ] Feature: Show when a point is NOT 50 meters from an others, and if more than 2 points have the same elevation
- [ ] Better UI: Point map, screenshots ingame of help menu
- [ ] Less character in script
- [ ] Better performance script

### References

[1] https://en.wikipedia.org/wiki/True-range_multilateration#Three_Cartesian_dimensions,_three_measured_slant_ranges 

[2] https://www.101computing.net/cell-phone-trilateration-algorithm/

[3] http://archive.cone.informatik.uni-freiburg.de/teaching/vorlesung/wsn-s16/slides/WSN-C-23.pdf


# SCREENSHOTS

## Basic Panels
![fig1](fig1.png)
![fig4](fig5.gif)

## Paused Panels
![fig4](fig4.gif)
![fig2](fig2.png)

## Parameters
![fig3](fig3.png)
