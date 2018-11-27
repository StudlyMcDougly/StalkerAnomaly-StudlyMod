# StalkerAnomaly-StudlyMod

My setup for [S.T.A.L.K.E.R.: Anomaly](https://www.moddb.com/mods/stalker-anomaly). Includes a collection of mods as well as some of my own tweaks.<br/>
<br/>
Requires:<br/>
[S.T.A.L.K.E.R.: Anomaly — Version 1.4 (Ver: 9/9/2018)](https://www.moddb.com/mods/stalker-anomaly/downloads)<br/>

## Updates
*11/26/2018*<br/>
Added English_Voices_Addon_CoC_1.5 - Anomaly Compatible <br/>
<br/>
*11/25/2018*<br/>
Initial Commit (Version 1.4.0)<br/>
Added S.T.A.L.K.E.R. ANOMALY: ENGLISH VOICES<br/>
Added No Ammo on HUD<br/>
Added No Neutral Crosshair<br/>

## Installation
1. Download S.T.A.L.K.E.R.: Anomaly Repack 1.3.1 Part 1  and 2,  Update 1.3.3, Update 1.4.0.
2. Unzip into folder in this order 1.3.1 part1,1.3.1 part2, 1.3.3, 1.4.0
3. Download and unzip this mod into the install folder, overwriting old files with the new versions.

## Mods
**_[S.T.A.L.K.E.R. ANOMALY: ENGLISH VOICES](https://www.moddb.com/mods/stalker-anomaly/addons/english-voices)_**<br/>
(Ver: 9/7/2018)<br/>
*Adds some voices to English*<br/>

## My Mods
**No Ammo on HUD**<br/>
*Removes the Ammo count from the HUD (Ported from Last Day. Sets Ammo X coordinate to negative value)*<br/>
`gamedata\configs\ui\maingame.xml`<br/>
`gamedata\configs\ui\maingame_16.xml`<br/>
<br/>
**No Neutral Crosshair**<br/>
*Removes the crosshair when you are at neutral (no weapon etc out). Stock has a big ugly circle. Replaced with texture from Last Day which is a small X*<br/>
`gamedata\textures\ui\cursor.dds`<br/>
`gamedata\textures\ui\cursor.thm`<br/>
<br/>
**English_Voices_Addon_CoC_1.5 - Anomaly Compatible**<br/>
*Based off [English Voices Addon for COC 1.5](https://www.moddb.com/mods/call-of-chernobyl/addons/coc-english-voices-addon). Adds English voices from all games EXCEPT those that are present in the Anomaly English Mod. Since all voices have been added some characters might have 2 voices thanks to audio from different games. But such is life in the zone*<br/>
`gamedata\sounds\characters_voice\human_01`<br/>
`gamedata\sounds\characters_voice\human_02`<br/>
`gamedata\sounds\characters_voice\human_03`<br/>
`gamedata\sounds\characters_voice\scenario`<br/>

## TODO
- [X] HUD Remove Ammo Count (Port from Last Day)
- [X] HUD Neutral crosshair (like Last Day) so it is only a dot.
- [X] Add in more English Voices.
- [ ] "Lost to the Zone" Message on death (Maybe).
- [ ] Remove Aurora Borealis effect when close to death.
- [ ] Remove all crosshairs (different from disable. Disabling removed NPC identification).