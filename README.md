# lua_speedruns
World of Warcraft AzerothCore(https://azerothcore.org) lua script to record time player needs to finish vanilla dungeon runs.

Install:
1) Install Eluna Mod: https://www.azerothcore.org/modules-catalogue/details.html?id=131435473
2) Place speedruns.lua in your /lua_scripts folder
3) Insert the 3 sql tables into your db (care if your world schema is not acore_world!)
4) Ingame type in .reload eluna

How to use:
1) Enter any dungeon listed in custom_speedruns_dungeon
2) You have to kill all listed bosses to complete the run
3) Your results are saved in custom_speedruns_results
4) You can show your current run by typing in "show stats"

Todo:
1) Add more dungeons
2) Add npc to start run
3) replace player:say with sth usefull
