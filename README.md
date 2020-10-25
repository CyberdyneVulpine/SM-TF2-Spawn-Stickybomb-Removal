# [TF2] Spawn Stickybomb Removal
**Current Version: 1.0.0**  



## Description:
Removes stickybombs if they are placed within a (default: 150 units) radius of the other team's spawn door.  
 The sticky-camping player will also be shown a hint message asking them to stop.  

## Cvars:  
-   **spawn_sticky_removal**
    -   Plugin Version
-   **sticky_break_distance**
    -   Stickybombs closer to a spawn then this value will be removed.
    -   Default: 150
    -   [These stickies are aprox 150-200 units from the spawn.](http://screencast.com/t/X6qUZIhvR)

## Install Instructions:
1.  Place  **NoStickySpawn.smx**  into your addons/sourcemod/plugins/ folder.

## Notes:
This plugin uses the func_respawnroomvisualizer entity to detect locations.  
If your map does not have visualizers on the spawn doors, this plugin will not work.

## Version History:
-   **v1.0.0**
    -   Initial Release
