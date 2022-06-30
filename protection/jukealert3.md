### Culling and dormancy

Snitches need to be periodically refreshed by a player entering the snitch 
field who is on the snitch group with the namelayer LIST_SNITCHES permission. 
Snitches that are not refreshed will first become dormant and lose all functionality 
but once refreshed will become functional again, if a dormant snitch isn't refreshed 
however after more time it will become culled. A culled snitch has no functionality 
but also can't be refreshed, functionality can only be regained by breaking and 
replacing the snitch block. You can use &l/jalist &r&fto see if your snitches have become 
dormant or how long is left until a snitch becomes dormant or culled. When you 
refresh a snitch, the timer on &l/jalist &r&fwon't be updated until the daily server restart. 

### Lever trigger

Jukebox snitches can be configured to cause levers on the blocks on or adjacent to 
the jukebox sides to output a redstone pulse. This behavior which is disabled by 
default can be enabled with &l/jaToggleLevers 1 &r&fand disabled by &l/jaToggleLevers 0 
in radius of snitch.

The direction the lever is placed on changes the action type that causes it to trigger. 

Nearby levers will be turned on for a duration of approximately 750ms. This duration can 
vary due to server lag. Levers that have already been enabled by players will also be 
turned off after 750ms.

### Mechanics

    -Breaking a snitch will print the namelayer group it is reinforced to along with the 
       owner of the namelayer. This does not apply to culled snitches.
    -Pearling in a snitch field will not trigger the snitch but moving inside will.
