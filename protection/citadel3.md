### Decay

Reinforcements placed under a group will decay if the group becomes 
inactive (no player in the groups logs in).

Currently, reinforcements will start decaying after 3 months of inactivity
and the damage multiplier doubles every year. The damage multiplier is 
applied to every block break. This means that with a damage multiplier of 2, 
reinforced blocks can be broken twice as fast.

Since a single player logging in is enough to reinitialize the decay clock
and since the decay rate is rather slow, decayed buildings aren't common. 

### Terminology

A common abbreviation series is DRO/IRO/SRO/PRO, standing for for 
Diamond/Iron/Stone/Paper reinforced obsidian.

### Advanced features

    -Note that reinforced blocks are not affected by gravity (e.g. reinforced 
       sand will float). However if the block by default breaks when block beneath 
       is removed, it will break even if reinforced (e.g. rails whose base is broken
       will also break).
    -Being in reinforcement or fortify mode will prevent the use of citadel buttons.
       Walking over pressure plates while in this mode will reinforce them to currently 
       selected group.
    -Reinforcing farmland will give crops planted on it citadel protection.
    -Reinforce leaf blocks and destroying the tree they are apart of will lead to 
    loss of reinforcment.

Known bugs

  -Placing a reinforced button/sign and breaking the block at the base will make it drop but 
     will leave a reinforced air block behind. As this is an exploit its use should be avoided.

