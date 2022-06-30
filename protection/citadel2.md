-Tool durability will not go down when damaging a reinforced block
-Because a moment passes between block break animation and reinforced 
    block reappearing it is possible to 'reach' behind reinforced block. 
    The block will reappear before a player can fall or walk though, however
-It is possible to double reinforce a double chest by placing it while using /ctf
-Explosions will do one reinforcement damage to all blocks in blast range. This
    only applies to blocks that the explosion would have been able to damage 
    had they been unreinforced.
    
### Acid blocks

Reinforcing a gold block creates an acid block. An acid block can remove 
the reinforced block directly above it regardless of respective reinforcement 
groups. The acid block must be allowed to mature and must use the same 
reinforcement type as the block directly above it. When enough time has 
passed such that the acid block is mature, looking at the acid block and 
doing /ctacid will remove the blocks. The block on the top will be removed
an the gold block will be dropped on the ground. /ctacid has a range of 40 
blocks. It can remove several blocks at the same as long as they line up 
with the player's cursor. Acid blocks can be used in traps.

### Insecure reinforcements

A reinforcement can be set to insecure using /ctin or /ctinsecure and hitting it. 
This allows hoppers to move items out.
Redstone interactions
    -Reinforced buttons will only emit a signal if someone from the namelayer is nearby (distance?)
    -Comparators cannot inspect the content of a reinforced container block (e.g: chests, furnaces, droppers)
    -Droppers and hoppers will not transfer items if the destination block is not on the same reinforcement group.
    -Blocks can not be attached to a reinforced redstone component (e.g dropper, dispenser,
      hopper?) if not on the reinforcement groups.
    -Reinforced doors, trapdoors and fences gate will only respond to a redstone signal if 
      someone on the reinforcement group is less than 7 blocks away from iT.
