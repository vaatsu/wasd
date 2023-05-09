Instructions on how to setup WASD-clantag\
This clantag changes your clan-tag to show what movement keys you are currently pressing. (WASD)\
For this to work you'll need multiple cfg files and you also need to join 16 steam groups\
The steam groups are required, since their clan tag is the set of keys you are currently holding down.\
CSGO requires you to be in the group(s) to display clan-tag next to your name.\
\
JOINING GROUPS:\
Join the following groups:\
Easiest way for this is to log in to steam using your preferred web-browser; \
	┣ 1) then copy & paste the first link\
	┣ 2) join the group\
	┣ 3) change the number to the next one in browser (wasd-01 ⇝ wasd-02)\
	┗ 4) repeat steps 2 & 3 until done.\
\
https://steamcommunity.com/groups/wasd-01
https://steamcommunity.com/groups/wasd-02
https://steamcommunity.com/groups/wasd-03
https://steamcommunity.com/groups/wasd-04
https://steamcommunity.com/groups/wasd-05
https://steamcommunity.com/groups/wasd-06
https://steamcommunity.com/groups/wasd-07
https://steamcommunity.com/groups/wasd-08
https://steamcommunity.com/groups/wasd-09
https://steamcommunity.com/groups/wasd-10
https://steamcommunity.com/groups/wasd-11
https://steamcommunity.com/groups/wasd-12
https://steamcommunity.com/groups/wasd-13
https://steamcommunity.com/groups/wasd-14
https://steamcommunity.com/groups/wasd-15
https://steamcommunity.com/groups/wasd-16
\
SETTING UP CFG FOLDER:
1) Extract wasd folder to your cfg folder.\
	The folder structure should be like this:\
	csgo\
	└───cfg\
	│   │   autoexec.cfg\
	│   │   ...\
	│   └───wasd\
	│       │   states\
	│       │   disable.cfg\
	│       │   help.cfg\
	│       │   init.cfg 

2) Create or modify your autoexec.cfg and include this in it:\
	exec wasd/init.cfg

3) For first time setup after 'exec wasd/init.cfg' is ran (autoexec should do this) run this console command:\
	WASD_on\
	The script also adds the following commands: WASD_off, WASD_toggle, WASD_help\
\
KNOWN ISSUES:\
This script changes your keybinds on W, A, S, D keys to aliases (when you run WASD_on, or other WASD_ commands)\
if your autoexec is not set up correctly, after rebooting your game your movement keys might be broken.\
Console should send messages such as: "Unknown command '+w'" in this case.\
\
You can fix this issue by running 'exec wasd/init' manually or by disabling the script completely by running 'exec wasd/disable' in your console.\
My recommendation would be to fix your autoexec to run when the game starts. There are multiple tutorials online how to do this.