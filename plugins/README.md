# Plugin info

A collection of useful commands for the Sølvguttene scrim server running splewis/csgo-pug-setup and sethealth plugin

## Chat commands
- .setup, open setup menu to choose captains, teams, map, voting, etc.
- .10man, an alias of setup with 5v5, captains, and a mapvote
- .listpugmaps: List all maps in map rotation (that also will show up in vote)
- .pause requests a pause (which takes effect next freezetime)
- .unpause request an unpause
- .start starts the game if auto-live has been disabled
- .capt gives the pug leader a menu to select captains
- .leader gives a menu to change the game leader
- .endgame force ends the game safely

## Console commands
- rcon_password <password>: Get admin rights on server
- rcon <command>: Prefix all commands with "rcon" to use admin rights    
  E.g: `rcon exec fungames/competitive_fast` to execute config
- sm_map <map>: Change map (or use .setup -> next -> "Change map")
- sm_mapvote <map1> <map2> <...>: Start map vote for these maps
- sm_spawnhp @all/@t/@ct <hp>: Set how much health players should start with
- sm_help <1-10>: See plugin commands
