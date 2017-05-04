The Omni Survival Game
-------------------------

Third-person survival game for Unreal Engine 4 made in C++. It currently features weapons and weapon pickups, explosives, zombie AI, multiplayer networking, an accurate day/night time system, a way to use props as barricades, and more. 

The current plan for this project is to: 

- [55%] Fix bugs and update any outdated code
- [45%] Remove any possible exploits (prop surfing, leaving the map, and etc:)
- [00%] Add more maps to increase replayability
- [00%] Add more AI monsters to increase enemy diversity and increase difficulty
- [20%] Overhaul the AI into performing much better and properly detecting the player in difficult situations
- [100%] Implement an options page that allows people with slower devices to play with reasonable framerates
- [00%] Create goals and tasks for the player(s) to complete
- [??%] Plus a few more things that I have not yet decided on ;D

*The original framework for this project was designed by Tom Looman as a 6 section tutorial series. For more info on the original, see [the main documentation page on the unreal engine Wiki](https://wiki.unrealengine.com/Survival_sample_game).*


**Currently updated for 4.15!**

### Change Log / Update Log

- {Associated Commit} [Update Type] Notes & Comments

- {OSG001} [BugFix] Replaced deprecated menu commands and fixed mouse cursor in menus.
- {OSG002} [Exploit] Added invisible barrier around entire map to contain the player within the play area
- {OSG002} [Exploit] Added invisible barriers above many different locations to prevent the player from becoming unreachable. (Eg: on top of the main building and some rocks)
- {OSG002} [Terrain] Fixed a floating pillar. Terrain reworked with some new paths painted.
- {OSG002} [Terrain] Greatly improved navmesh in some areas. Added wider and smoother entries to a few spots. Before there were a few places that had hardly pathing possible.
- {OSG002} [Props] Added a collision mesh to some props that were lacking them.
- {OSG003} [Menu] Created a new Options menu with several different graphics options. Accessible during play through the escape menu.
- {OSG003} [UI] New font added, Xirod. 
- {OSG004} [Menu] Added OSG logo to Main Menu
- {OSG004} [Levels] Rebuilt lightmaps and split them apart from levels to lower map file sizes.
- {OSG004} [UI] Black 1u outline added to most text to greatly improve readability on white backgrounds.
- {OSG00X} [] 
