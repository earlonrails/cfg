My comments
--------------------
I found this repo on reddit, can't seem to find the link right now. I want to give credit here to the person that started this. Just wanted to share it with others.

This is a collection of scripts for Dota 2. The autoexec.cfg will start everything off and there are supposed to be ranges
for each character. I haven't seen these work yet. I have also included some of the macros I use and have mostly found online from reddit and other sources.

For mac, not the best OS for playing dota btw, the location of the cfg should be here

    open ~/Library/Application Support/Steam/SteamApps/common/dota 2 beta/dota/cfg

Original Source Instructions
----------------------------
I cannot promise that these scripts will not horribly break your dota2, or break on an update, new heroes will have to be manually added in, you can contact me for that.
Furthermore I cannot guarnatee accurate of the ranges themselves, I am only going off the wiki, and playdota where necessary.

If you spot any ranges that are wrong, give me a shout.

You can contact me on steam at http://steamcommunity.com/id/kamer

---

Navigate to steam\steamapps\common\dota 2 beta\dota\cfg and extract the contents of cfg there.


Edit the contents of keybindings.cfg to suit your control layout.


Shift will toggle between attack range (on ranged heroes), and blink range (on heroes who typically grab blink), and some other things, such as tinkers homing missiles.


If you would rather only have blink range only appear when shift is pressed, remove "bind shift variablerange" and uncomment "bind shift "dota_range_display 1200"


If you do not have an autoexec.cfg, copy autoexec.cfg into the cfg folder


Enable the console by right clicking dota 2 in your steam library > propeties > set launch options, and add "-console", without quotes.


Once ingame, goto options > controls > abilities, and clear the default skill hotkeys (bind them all to delete or something).


After you've selected a hero, press ~ to pull up the console, and type exec <heroname> (some heroes used their most common name (this is solely personal preference), like Natures Prophet is Furion, you can edit these manually, by renaming the .cfg files in cfg)

Level up skills by holding ctrl and pressing the respective hotkey (ctrl q will level up your first skill, for example.  Theres no way to actually track your heroes skill levels, so you have to use this shortcut for the scripts to watch what level everything is.)

QWER with the default keybindings will pull up circular range indicators when pressed.


For heroes like Invoker, and Rubick, it is impossible to setup scripts that work properly, so dont expect perfect functionality.


There are templates included to add in ranges for new heroes, if im not around to provide updates, you can look up the numbers and try and edit things to match others.