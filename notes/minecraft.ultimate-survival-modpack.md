---
id: 0x28k9lcw46p2a6dt2v5gqy
title: Ultimate Survival Modpack
desc: Rationale behind and guide to playing Ultimate Survival Modpack.
updated: 1685109111701
created: 1679589598725
---
modification on RGB 1
modification on laptop 3

# Ultimate Survival Modpack

## Rationale

I developed this modpack as a fix to issues I have had in the past with other modpacks.

    1. Way too much time and effort looking for ores. 

    I solved this by using the Lots of Ores mod. This mod generates large ore deposits and is very configurable. It also puts patterns of flowers on the surface  to aid in locating large ore deposits.

    2. I wanted a focused modpack instead of a "everything but the kitchen sink" modpack. To this purpose I have 4 main catagories of mods. 

        1. Technology Mods

            1. Mekanism and it's associated mods. 
            
            Mekanism is a complete modpack in that it has advanced ore processing, power generation, advanced armor, and a lot of devices that are just fun. You gotta love jet packs and flame throwers.

            2. Applied Energistics 2

            Inventory control and automated manufacturing

            3. CC:Tweaked

            ComputerCraft computers are a good basis for control systems and the turtles can be effective minions. It does feel a bit like cheating because they are so easy to make so early in the game but at this time OpenComputers is not available for Minecraft 1.19.2. If you enjoy the challenge of writing your own programs Lua is a simple yet powerful programming language and if you rather there are many high quality programs you can download for your computers and turtles.

        2. Magic Mods

            1. Ars Nouveau

            Ars Nouveau allows you to create your own spells and is involved enough to be enjoyable. I haven't played it before so we will see how useful it is.
        
        3. Enhanced Enjoyment

            Better biomes, villages, etc.

        4. Quality of Life Mods

            Removal of many tiny frustrations.

## Game Play Notes

Mekanism Wind Turbines
    - Place them at level 251 for maximum power generation.
    - Use RFTools Simple Power Cell with an ID card. This allows you to distribute the power anywhere.
    - Probably need to place an anchor in the chunk

## A great seed
    - 3104911294046904486

# Minecraft Large Ore Deposits Cheatsheet (Abbreviated)

* Coal
    * 80 to 0
    * minecraft:large_fern, 3
    * minecraft:large_fern, 6
Copper
* Diamond
    * -16 to -64
    * minecraft:blue_orchid, 3
    * minecraft:blue_orchid, 6
* Gold
    * 8 to 32
    * minecraft:dandelion, 3
    * minecraft:oxeye_daisy, 6
Iridium
* Iron
    * 64 to -64
    * minecraft:orange_tulip, 3
    * minecraft:azure_bluet, 6
Lapis
* Lead
    * 64 to 16
    * minecraft:azure_bluet, 3
    * minecraft:azure_bluet, 6
Nether Gold
Nether Quartz
Nickel
* Osmium
    * 32 to 8
    * minecraft:blue_orchid, 3
    * minecraft:blue_orchid, 6
    * minecraft:blue_orchid, 9
* Redstone
    * -16 to -32
    * minecraft:poppy, 3
    * minecraft:poppy, 6
Rhodium
Ruby
Ruthenium
Sapphire
Silver
* Tin
    * 64 to 16
    * minecraft:oxeye_daisy, 3
    * minecraft:lily_of_the_valley, 6


# Vanilla Mining Levels
Ore | Location
-----   |---------   
Gravel 	|Can be found at any level
| Coal   	|Can be found above y=-1, but is more common in y=95 and 136.|
Iron 	    |Can be found above y=80 and below y=72, but is most common at y=15 and 232.|
Copper 	|Can be found between y=-16 and 112, but is most common at y=48. More common in the dripstone caves biome.|
Gold 	    |Can be found below y=32, but is most common in y=-16. In the badlands biome, it is also generated between y=32 and 256.|
Lapis  	|Can be found below y=64, but is most common in y=0.|
Emeralds 	|Can be found above y=-16, but are most common in y=236. Generates exclusively in the mountains biome.|
Diamonds 	|Can be found below y=16, but are most common at y=-59.|
Redstone 	|Can be found below y=16, but is most common at y=-59.|
Lava 	    |Excluding lava lakes, can be found below y=-53, but is less common below y=-60.|
Bedrock 	|Can be found below y=-59.|
Nether Quartz 	|Can be found at all y levels in blobs of 1-14, only in the nether.|
Nether Gold Ore 	|Can be found between y level 10-117 in all biomes, only in the nether.|
Ancient Debris 	|Can be found between y=8 and 119, but is most common between y=8 and 22, only in the nether.|




# Turtle Programs

## Turtle Architect 

[Link](http://www.computercraft.info/forums2/index.php?/topic/16641-turtle-architect-v20-the-ultimate-turtle-planningconstruction3d-printer-software/)


pastebin run VTZ6CqWY


## Variable Size Quarry

[Link](http://www.computercraft.info/forums2/index.php?/topic/5681-variable-size-quarry-now-with-super-ore-quarry%e2%84%a2/)

Version 3.6.4 (this goes on the turtle):
http://pastebin.com/rpXRAZs4
Version 3.6.5 Rednet Companion Program (this goes on computer, compatible with 3.5.2 - current):
https://pastebin.com/7Ksx4qUJ
Version 1.0.3 Rednet Repeater Program (goes on computer, compatible with 3.5.4 - current)
http://pastebin.com/Te359WA2
Ladder Placing:
http://pastebin.com/GbWZhXCC

Version Made by Renari compatible with the "Miny Chunky Module" peripheral. (Version 3.5.5)
http://pastebin.com/4y9W8i9i

### Turtle Mining Package

I've written a small "installer" script a while ago that lets me download most of the programs and files I commonly use in CC. To use it, just execute 

```
pastebin run p9ZkrH1i 
```
on a turtle.
Here's the current list of programs/files it will offer to install, what they do, and if you might need them:

### updater.lua

 (source): This is my auto-updater script. When installed, programs can use it to check if there is an updated version of themselves available on pastebin, and automatically download it. You probably don't need this unless you want to use the auto-update functionality in your own programs.

### betterturtle.lua
 (source): This file adds a few convenience functions to a turtle when it starts up, which can then be used in code. You don't need this, but the added functions can be useful:

### turtle.turnAround(): 
180° turn

### turtle.left()/turtle.right(): 
move one block to the left/right without changing orientation.

### turtle.forceForward():
 Will forcibly move forward by digging & attacking if the block in front is not empty. The command exists for all other directions too. (up, down, left, right, back)

### Additional dig, detect, compare, inspect, place, drop, and suck directions, for example turtle.digLeft() and turtle.dropBack()


### quarry.lua (source):
 This is my quarry program. It digs columns into the ground in such a pattern that the turtle only needs to move the minimum amount of blocks, and never looks at a block twice. It optionally uses an ignore-list or allow-list, so that it won't dig up stone, cobble, dirt and other things you might not need. The source code is quite large, and I still have not yet written a readme for it since I was the only one using it so far. I'll try to write something up in the next few days. If you want to check it's capabilities yourself, you can see what parameters the program accepts from line 134 to 239 of the code.

### quarry-minion.lua (source):
 this is a small script which just runs the quarry for a 16x16 area, using a predefined ignore-list from my pastebin. You might want to use this and modify it to your liking. If you do, I suggest to change the true in lines 17 and 18 to false. This will prevent the script from re-downloading my ignore-list every time you run it. The turtle will remember all types of blocks it dug up, and store it in a file called mined-blocks.txt. You can check this file after you run the turtle, and add any blocks you don't want mined to the ignore.list file.

### ignorelist-generator.lua (source):
 I recommend you install this. It let's you add blocks to the ignore.list file by just placing them in front of the turtle, while the ignorelist-generator program is running.

### oredict-sorter.lua (source):
 Requires an "oreDictionary" peripheral from Peripherals++ to work. I don't fully remember how this program works, but I used it to convert f.e. copper ingots from different mods into one kind.

### testcode.lua:
 This is just whatever code I was trying/editing at the time. Not needed.

### ignore.list (source):
 This is the ignore.list file I used for my quarries the last time I played. You might want to grab it edit to fit your needs. (Or use the ignorelist-generator to add blocks to it)

### oredict.config (source):
 The last configuration for the ore-dictionary functionality of the quarry/the oredict-sorter that I used. You don't need this, unless you happen to play with the exact same combination of mods that I was 2 years ago.

Feel free to ask me any questions about the quarry or my other programs (https://pastebin.com/u/npexception). I'll try to answer them as best I can. :)

## Branch Miner

https://github.com/Equbuxu/mine

## Another Mining Program

https://www.reddit.com/r/feedthebeast/comments/kiziih/anyone_know_of_a_good_mining_turtle_program_that/

pastebin run p9ZkrH1i

## do and act

pastebin get AE5bJyZh act
pastebin get B19FgvuV do

# Stop Day-Night Cycle

/gamerule dodaylightcycle false
