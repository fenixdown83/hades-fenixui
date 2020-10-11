# FenixUI mod for Hades
Heavily inspired from the look of the **Hades Racing Mod** *(designed by **ellomenoP** / currently not publically available)* used for the **Hermes Cup**.
This mod was created for those that wanted similar UI elements during their Hades runs for informational purposes or for race practice.
Mostly, it was for me to get my hands dirty with modding Hades.

![FenixUI Screenshot](https://i.ibb.co/CPqpDpT/FenixUI1.png)

# Features
- Reworked implementation of the Depth counter. It is always visible and doesn't disappear when going in and out of your Boons menu during combat.
- Room name and seed information displayed in the upper-left corner of the screen. I felt this might be helpful for memorizing certain room elements. Seed information is mostly there
  for informational purposes for me (and might be involved in a more elaborate mod later on).
- Chaos room, Story room, Well room, and Thanatos room icons and counters displayed in the upper-right corner of the screen. We all play a lot of Hades, sometimes I can't remember how many times I've ran into Chaos during a run or if I found a well. It's nice, informative information I'd like available to me as a player so when I saw the Hermes Cup utilizing a mod that rendered that information on-screen, I knew I wanted something like that and thought it would be fun to see if I could make it myself.

# Installation
I'd recommend using the **PrometheusLoader** developed by **Ship**: https://github.com/SyncingShip/PrometheusLoader. Please utilize the following mod installation instructions:

- PLEASE BACK UP YOUR SAVE FILES *(Saves can be found  in %USERNAME%/Documents/Saved Games/Hades)*.
- Download and install **Git** *(Utilized for patching your game files)*: https://git-scm.com/download/
- Download and install **Python 3** *(Necessary for **PrometheusLoader** to work)*: https://www.python.org/downloads/
- Download the **Prometheus** repository: https://github.com/SyncingShip/PrometheusLoader
- Download this repository using **Clone** or **Download** from the **Github** page.
- Place the FenixUI **.patch** file into the **PrometheusLoader/Mods** folder.
- Run the **PrometheusLoader** through the **.bat** file in the **PrometheusLoader** folder.

**IMPORTANT NOTE:** As this mod instantiates new variables to account for things not normally tracked (*Chaos rooms, Well rooms, etc.*), and it does this at the **START** of a new Hades escape attempt, you will need to **Give Up** your current escape attempt if you are in the middle of one. 

# Known Bugs
- Everytime the new UI elements are redrawn, it triggers the sound used when door icons are populated at the end of a room *(annoying but doesn't effect functionality)*.
- When in Town, only the Thanatos icon shows a numerical value *(visual bug only - displays currectly during runs)*.

# Disclaimer
**Please use at your own risk** |||
To my knowledge, **Supergiant Games** has not officially endorsed modding **Hades**. **Supergiant Games** is not responsible for any problems this mod may cause.
I am not responsible for any problems this mod may cause.
||| **Please use at your own risk**.

# Contact
Please feel free to contact me via Discord (**Fenix#6348**) if you have any questions/feedback/suggestions regarding this mod.
