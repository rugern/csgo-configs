# csgo-configs
A collection of CS:GO config files and links for different game modes, training, and maps.

## Configs
Check [SUMMARY.md](https://github.com/rugern/csgo-configs/blob/main/cfg/SUMMARY.md) for an overview of configs
for fungames, practice, etc

## Plugin commands

### Chat commands
- .setup, begins the setup phase and sets the pug leader
- .10man, an alias of setup with 5v5, captains, and a mapvote
- .listpugmaps: List all maps in map rotation (that also will show up in vote)
- .pause requests a pause (which takes effect next freezetime)
- .unpause request an unpause
- .start starts the game if auto-live has been disabled
- .capt gives the pug leader a menu to select captains
- .leader gives a menu to change the game leader
- .endgame force ends the game safely (only the leader can do this, note that this resets the leader to nobody)

### Console commands
- rcon_password <password>: Get admin rights on server
- rcon <command>: Prefix all commands with "rcon" to use admin rights    
  E.g: `rcon exec fungames/competitive_fast` to execute config
- sm_map <map>: Change map
- sm_mapvote <map1> <map2> <...>: Start map vote for these maps
- sm_spawnhp @all/@t/@ct <hp>: Set how much health players should start with
- sm_help <1-10>: See plugin commands

## Collection of workshop maps
https://steamcommunity.com/sharedfiles/filedetails/?id=2600005602