# GBFR Grinding Assistant

This script is designed to alleviate the repetitive aspect of GBFR using Python. It supports automation and shortcuts to enhance the experience and to eliminate Carpal Tunnel Syndrome. I'm aware that AHK exists, however I have Python installed and not AHK. Furthermore, I wanted to implement QoL for offline play.

## Features

- Automates perfect Rackam's shots in any quest, but works best in Slimepede.
- Using fast travel to interact with NPCs and for starting Slimepede.
- Moving into position in Slimepede and begin automatic fire.
- Full auto mode:
  - Travels to the Quest Counter, select and start the Slimepede mission. Moves into the back upon mission entry and begin automatic fire.
  - Will continue to move into position and automatic fire provided repeat is turned on.
- Automates transmutation and transmarvel.
- Reduces chest opening timer and quest result timer.
- Repeat quest indefinitely.

## Disclaimer

Script has been tested in closed matchmaking and offline mode.
Timer for macros are tested on 60FPS, and will have a different result at 30FPS or 120FPS.

## Setup

Install [Python] if you don't have it on your system.
Open up the command prompt(cmd) and run the following commands to install the dependencies:
```sh
pip install -r requirements.txt
```
__Always__ run GBFR first before the script.
Go to Game Options > Gameplay.
- Ensure "Quest Cutscene Auto-Skip" is set to On and "Loading Screen Skip" is set to Auto Skip.

See Controls.

## Controls

- F1: Activates automatic fire for Rackam.
- F2: Moves to one of the four designated positions before activating automatic fire.
- F3: Travels to the Quest Counter, select and start the Slimepede mission. Moves into the back upon mission entry and begins Automatic fire.
- F4: Simply mashes the enter key. Be sure to select the right transmutation level or transmarvel before activating F4.
- F5: Turns chest opening timer to 0s and quest result page to 5s.
- F6: Resets the quest repeat counter.
- r + 1: Uses fast travel to move and interact with the Quest Counter and talk to the NPC.
- r + 2: Uses fast travel to move and interact with the Blacksmith.
- r + 3: Uses fast travel to move interact with Sierokarte.
- r + 4: Uses fast travel to move interact with Zathba.
- Ctrl + q: Force quits the script.

[Python]: <https://www.python.org/downloads>