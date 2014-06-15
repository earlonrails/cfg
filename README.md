Install
---

copy all apart from the autoexec.cfg to your dota/cfg folder. Located roughly:
windows

    C:/Program Files (x86)/Steam/steamapps/common/dota 2 beta/dota/cfg
    C:/Program Files/Steam/steamapps/common/dota 2 beta/dota/cfg

linux

    ~/.steam/steam/SteamApps/common/dota 2 beta/dota/cfg
    
mac

    ~/Library/Application Support/Steam/SteamApps/common/dota 2 beta/dota/cfg

For the autoexec.cfg, copy the contents to prefrably the bottom of your current autoexec.cfg.

Use
---

This should work without the hero dependent features out of the box. When you want to use these, you will need to open the console and type `exec hero\'name'` where name is the 'name' of the hero. These are diffrent to normal in most cases, but the common DotA2 player will know them. And example of getting Axe and Naga Siren:
   
   exec hero\axe
   exec hero\naga
   
Bugs & features
---
Please report bugs and features here on github. Just raise a new issue for both.

How it works
---
This uses the fact that ctrl ability, levels the pressed ability up. This allows us to utalis a little loop, that counts to 4 on normal abilites and 3 on your ult. Each time you level up you exicute a small command, that defults to a small echo, however hero's like axe have it so that your health per verticle marker changes each level of culling blade, to easily determin if you can deal an insta-kill. Or hero's like sniper increase there range.
We also utalise a modifyer on the ctrl key to determin if you are casting your ability or leveling it up.

The other code is currently rather simple, so if you want to know how that works I recomend you look at it.
