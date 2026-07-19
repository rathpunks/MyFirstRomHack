Patcher:
-----------------
Download the zip. Unzip the files.
The .toml is if you would like to edit in Hex maniac advance. Ensure the .toml is in the same file and named the same as the patched romhack for Hex maniac advance to recognise it.
To patch ensure you have a 32MB fire red squirrels. To expand from 16MB to 32MB there are a few ways, easiest might be using Hex Maniac Advance and loading the 16MB rom then selecting expand in the top 'Utilities' menue and type 1FFFFFF. This should now show as a 32MB file.
Go to a pach website (I use https://www.marcrobledo.com/RomPatcher.js/) and select the 32MB file for base rom, and one of the patch files from the zip and click patch. This should succesfully patch and you will be free to play.
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

Note this is a beta, and I am not very good at codeing or art, so there will likely be issues. Feel free to edit with the toml how you see fit. I would greatly appreciate if someone changed the overworld tileset to look cooler, I can't seem to get it to work.
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

Challenge Stadium:
---------------------
To the Left of Viridian City is where you find the Challenge stadium. There is a Man in the middle you can speak to to start a Black and White 2 World championships style battle.
There is another man off to the side who will give you rewards based on which Challeneges you have completed.
There are also every max level trainer battle set around this area where you can practice battles with each trainer if you wish.

In this same area is a cave entrace, you can go through here to take you to the move relearner and EV training zone.

There is an area on Island 3 that will have all the move tutor moves (excluding some unique ones).
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

Debug and Challenge:
-----------------------
You will notice a Lady in the corner of Oak's Lab. If you wish to play the game properly, do not talk with her. She was used for testing purposes, some of her code no longer works and causes glitches or crashes. If you wish to only face the challenge areana, you can use 'Set Flag', 'Give custom Pokemon' Give custom Item', 'Give useful items/general items' and 'lvl 100 team' The Pokemon and Items relate to the species and items files. You will need t convert the hex numbers to decimal.

If you are playing just to interact, play and test the champion stadium, you can unlock certain flags to enable lvl 100 Pokemon use and all the characters required to compete in each champion stadium. Speaking to the lady in the corner of Oak's Lab you can set these Flags and then you can travel to champion stadium. 
First you can speak to the lady and select game clear, then select custom flags to set.
Flags as follows:
0x024E
0x2D5
0x0B2
0x0BF
0x0CO
0x0C1
0x0C5
This will enable you to Level Pokemon to level 100 and hae them listen to you, allow acess to move tutors, also will act as though you have found and defeated the special trainers to allow you to face all challenges (Just need to complete some gauntlets to unlock other harder challenges).

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
To get the most out of the game make sure to speak to all NPC's and read bookshelfs for Lore information, Items, and battles.

There are areas that have the end point, but who's maps arn't completed. For example, you can Dive and catch Kyogre, however its currently just a big water square. So the game and post game are completed, but not every zone is 'Nice looking'. I may get around to completeing it, I may not, It has taken years of learning and restarting to get here as I am just 1 guy, so we will se how it goes.
Currently full playthrough testing myself for the first time and will update as I go if I find game breaking issues.
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

Known Issues include:
-------------------------
1) Some Characters names don't show porperly in battle.

FollowerMon Related:
2) Going on spin Pads while FollowerMon are out causes crashing.
3) Flying with follower mon out will lead to endless loop if you don't enter the PokeCenter first. 
   If using Follower mon, when  after using fly, enter the Pokecenter first to stop endless loop.
   If this becomes an issue you can speak with the girl in Pallet town to remove FollowerMon.
4) Going up the Escalator in the PokeCenter causes endless loop. (no need to go here)
5) Going on cycling road before manually getting on the bike while using FollowerMon causes endless loop. Get on your bike first then go onto cycling road.
-All FollowerMon related issues can be resolved by removing FollowerMon by speaking to the girl in Pallet town.

