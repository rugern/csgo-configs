# Fungames overview
All configs are available on scrim server. Execute a config with
```
rcon exec <config name>
```
(after running `rcon_password <password>` for admin rights)

Reset to default configuration with
```
rcon exec reset
```

## Configurations
- **fungame_respawn.cfg**      
  Players instantly respawn on death. Must defuse or explode bomb to win.
  [Video](https://www.youtube.com/watch?v=yoxFBcG6whA&t=1s)
- **fungame_headshots.cfg**  
  Only headshots.
  [Video](https://www.youtube.com/watch?v=fUnvsM2U2bM&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=18)
- **fungame_no_hud.cfg**  
  No HUD to help you.
  [Video](https://www.youtube.com/watch?v=8G30qRP7At0&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=19)
- **fungame_quake.cfg**    
  With bhops and no recoil.
  [Video](https://www.youtube.com/watch?v=4aM0YJjQKEs&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=21)
- **fungame_vampire.cfg**    
  Players lose health on missed shots and gain health on hitting shots.
  [Video](https://www.youtube.com/watch?v=oRcE3fJFwDI&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=22)
- **fungame_random_spawns.cfg**     
  Players spawn in random positions (hopefully without line of sight to eachother).
  [Video](https://www.youtube.com/watch?v=MEGmQcZ4q8E&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=25)
- **fungame_accurate_weapons.cfg**     
  Weapons have no recoil or spread.
  [Video](https://www.youtube.com/watch?v=vPdkgaHnZuM&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=7)
- **fungame_fast.cfg**      
  Players move twice as fast as normal.
  [Video](https://www.youtube.com/watch?v=K2BMj-SsN18&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=9)
- **fungame_invisible.cfg**    
  1v5 where one player is invisible.
  [Video](https://www.youtube.com/watch?v=GBUJ5O7zvKA&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=6)
- **fungame_scout_knives.cfg**    
  Low gravity environment with knife and scout only.
- **fungame_pool_day.cfg**    
  Some sensible rules for having a fun day by the pool.
- **training.cfg**
  Config for grenade practice
- **reset.cfg**
  Resets all effects from other configs

## Other

- **Give shield**  (must be executed by each player after each death)          
  sv_cheats 1; give weapon_shield;   
  [Video](https://www.youtube.com/watch?v=j7GfAbZ0xWM)
- **Give bump mine** (must be executed by each player after each death)     
  sv_cheats 1; give weapon_bumpmine; sv_falldamage_scale 0.1; sv_infinite_ammo 1;   
  [Video](https://www.youtube.com/watch?v=-xfapR8Z1p4)

## Plugin commands

- **fungame with 1000hp**
  Players have 1000hp: `sm_spawnhp @all 1000; rcon mp_restartgame 1`    
  [Plugin](https://forums.alliedmods.net/showthread.php?p=2737147)
  [Video](https://www.youtube.com/watch?v=57yCeKge8LI&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=8)    
- **fungame with 1hp**     
  Players have 1hp and no nades: `sm_spawnhp @all 1; rcon mp_buy_allow_grenades 0; rcon mp_restartgame 1`   
  [Plugin](https://forums.alliedmods.net/showthread.php?p=2737147)
  [Video](https://www.youtube.com/watch?v=Y0BwhnJrkgk&list=PLHF999pjo89OlX1XaBLqpl-5728A-P86A&index=10)    
