### World generation

The world has a set ammount of blocks in radius. Traveling beyond this radius is blocked by an invisible

and circular world border. Any attempt to travel beyond will result in being teleported back 
into the radius at a seemingly unpredictable y-level. If a player tries to cross the world 
border in a vehicle they will automatically exit the vehicle. Blocks may be placed outside of 
the world border yet any pearls stored outside the world border will be freed upon server restart.
Several non-vanilla biomes have been added. Many of these biomes have altitudes above 
y128 and sheer cliff faces. Biomes can also contain custom trees which are larger then vanilla. 
<img src="https://user-images.githubusercontent.com/35500599/176304053-d073e584-f39e-49ed-a79c-3303f4fc1f46.png" float="right" width="200px"/>

### Humbug tweaks
Humbug changes vanilla functionality in many areas.
Mobs:
    -Disables:  
        -trading with villagers  
        -Endermen stealing blocks  
        -iron ingots from being dropped by mobs  
        -Wither explosions destroying blocks and Wither insta-break ability  
    -Sets Wither skull droprate to .4%  
    -Sets base movement speed of mounted horses to 0.3 (from .17 in vanilla)  
    -Doubles Creeper drops  
    
### Blocks, entities and items  

    -Disables:
        -opening Ender chests
        -all vanilla XP sources (including mob drops, smelting and fishing) but XP bottles
        -enchanting books via enchantment table
        -use of elytra
        -teleportation with chorus fruit
        -inventory minecarts (including chest carts and furnace carts) from being opened. They can still be loaded via hopper.
        players in vehicles from opening inventories
    -End portal tiles are indestructible
    -Boats placed on land will break upon being used
    -Allows equipping a banner as a hat
    -Sanitize sign length to 100 text row length[awkward]
    -Water and lava above y 180 has limited propagation
    -Death and join announcements disabled
