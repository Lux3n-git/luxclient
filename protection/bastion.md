## &nBastion

Prevent actions such as block placements inside claims, unless bastion is broken.

### Basic Mechanics

CivClassic[3] uses Bastion in tandem with Citadel and Namelayer. It adds two types of 
blocks to the game: city bastions (lored bone block) and vault bastions (lored sponge). 
They are an advanced defensive block, preventing foes from taking action in the space 
surrounding it. The fields they project cover a square area from the y-level where the 
bastion block is located up to y256 (sky limit). Vault bastions are typically used in 
defensive infrastructure (most notably, vaults) to prevent block placement and ender pearl 
throwing. They allow or disallow players based in membershipon the group the bastion is 
Citadel-reinforced with, and can be broken by hostile playersfrom any block under their 
coverage. Essentially, doing any "forbidden" activity inside of a bastion field will cause 
damage, and over a period of time (scaling with the number of people attacking) the bastion 
will break, deleting the block and removing its field from existence. The health of the 
bastion block depends on the Citadel reinforcement, but due to the high cost of the block 
there is little sense in using anything but diamond. A bastion cap refers to the blocks, 
normally 1 layer of DRO (Diamond-reinforced obsidian), placed around the bastion block itself 
to protect it. Without a cap, it may be more efficient for attackers to mine the bastion block 
itself than to break it via block placements.
    -Breaking a vault bastion or city bastion alone with block placements takes exactly one 
       hour and 30 minutes respectively for a single player. Bastions can be concurrently 
       broken by several players, the speedup factor will be equal to the number of player 
       e.g: It'll take 4 times less time for 4 players to break a bastion that it'd take for 
       1 player. (15 minutes vs 1 hour)
    -50% of the damage dealt to vault bastions will also be inflicted on all other bastions 
    within a 5 blocks radius (center block + 5) from the vault bastions that were not initially 
    affected by the initial damages.
    -50% of the damage dealt to city bastions will also be inflicted on all other bastions 
    within a 25 blocks radius (center block + 25) from the city bastions that were not initially 
    affected by the initial damages.

Bastions are created with FactoryMod using a bastion factory. To build one, it costs 32 of 
each of the 6 lored bastion components, each coming from a separate factory.
