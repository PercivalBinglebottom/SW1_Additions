# Additional EMD SW1 Models And Speedometer Fix

*Credits to Kakashi Hatake for troubleshooting, and positioning of the Speedometer*
*Credits also to Elijah Gooden, Jeff, Giraffe LLC for the default SW1 from which these are built*

## Installation

1. Download Definitions.json
2. Navigate your file explorer to your Railroader install. This is usually located in your steam library:
   > {DRIVE}:\SteamLibrary\steamapps\common\Railroader\
   or
   > C:\Program Files (x86)\Steam\steamapps\common\Railroader\
3. Open the Railroader_Data\StreamingAssets\AssetPacks folder.
4. Open ld-sw1 folder.
5. **Make a copy of Definitions.json to back up the default SW1**
6. Drop in the new Definitions.json file and overwrite.
7. Open Railroader into a sandbox save. Place in any of the new EMD SWs or even the old SW1. You will find it now has an speedometer in the gauge cluster in front of the engineers seat.
8. ==Enjoy!==

## New SW models and Specs

| Model | Starting Tractive Effort (lbs) | Adjusted Tractive Effort (lbs) | Empty Weight(lbs) | Fuel Capacity(gal) | Adjusted Fuel(gal) (gamified) | Price |
| ----- |------------------------------- | ------------------------------ |------------------ | ------------------ | ----------------------------- | ----- |
|SW|50,000|55,000|180,000|600|600|27,098|
|SW900|57,500|63,000|230,000|600|600|29,625|
|SW7|62,000|73,000|248,000|600|600|31,472|
|SW9|62,000|75,000|248,000|600|600|31,958|
|SW1200|74,000|84,000|245,000|600|900|31,764|
|SW1500|62,000|100,800|248,000|600|1200|36975|

These models all shared a similar bonnet style and therefore we can *cheat* by using the SW1 in game model to get more variants.
I do not have modelling experience and am not skilled enough in modelling to make new SWs (as much as I'd like to) that have a different physical model.

### Why do we have "Adjusted Tractive Effort and Adjusted Fuel?"
I changed the starting Tractive Effort Values to better reflect performance based on advice from an SW9/SW1200 driver. The 1200 was underperforming and we can't adjust horsepower as part of the performance calculations. After some testing we've adjusted the TE to act in place of the Horsepower values until a better solution presents. We adjusted fuel for the top 2 tiered locomotives because, lets face it... Are you going to buy the SW1200 if the GP carries twice the fuel and most of the same power? Somethings just need to be gamified. Better bang for the buck so to speak.

## GIRAFFE LLC Modding Policy

This is the license that Giraffe gives to us in their Discord server:
Railroader does not currently officially support mods, therefore modifying you game is done at your own risk. Future game updates may break mod functionality. Railroader hopes to officially support modding in the future.
However, please note once more that modifying your game is done at your own risk. Bug reports submitted from modified games will not be accepted. If you encounter a bug, please retry in a non-modified game and see if that issue persists before submitting.

Asset bundles, models, textures, and animations that ship with Railroader may NOT be modified and/or redistributed. Many of the models in Railroader are owned by the modelers who created them and have been generously licensed to Giraffe Lab LLC for use in the game. We ask that you respect the contributors' rights and refrain from modifying or redistributing their work.

You are free to modify and distribute Definition.json files as long as you do not remove the credits. Remember that modding is not officially supported and Railroader is in active development. File formats may change without warning.