# atomrpgedit
This is a savegame editor for the game [Atom RPG](https://store.steampowered.com/app/552620/ATOM_RPG_Postapocalyptic_indie_game/).
It allows to reskill your character and heal party members, i.e., cheat.

## Usage
```
$ ./atomrpgedit --help
usage: atomrpgedit [-h] [-n] [-p] [-v] savegame

positional arguments:
  savegame           Savegame filename.

optional arguments:
  -h, --help         show this help message and exit
  -n, --no-backup    Do not create a backup file.
  -p, --edit-player  Instead of asking for a particular character, select the
                     player character by default.
  -v, --verbose      Increase verbosity.

$ ./atomrpgedit ~/.config/unity3d/AtomTeam/Atom/Save_0_v10.as 
 1) Player
 2) Wolfter
 3) Fidel
 4) Gexogen
Edit which character: 3

~~~ Fidel level 5 (6556 XP) ~~~
Damage 0        Hunger 0        Radiation 0        Toxicity 0       
Characteristics 0 
   Strength             7 
   Endurance            7 
   Dexterity            5 
   Intellect            6 
   Attention            7 
   Personality          6 
   Luck                 4 

Skills          0 
   Martial Arts         10
   Melee Weapons        64
   Pistols and SMG      20
   Rifles & Shotguns    17
   Automatic Firearms   18
   Throwing Weapons     15
   Speechcraft          0 
   Barter               0 
   Gambling             0 
   Survival             10
   First Aid            25
   Stealth              0 
   Lock Picking         0 
   Pickpocket           0 
   Technology           0 
   Tinkering            0 

Abilities       6 
   Survivor
   (SP_MasterMelee)
   (SP_MeleeAC)
 1) Heal character
 2) Reskill characteristics
 3) Reskill skills
 4) Reskill abilities
Option: 
```

# License
GNU GPL-3.
