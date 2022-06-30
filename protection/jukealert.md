## &nJukeAlert

Record the actions of other players in an area using snitches

### Creating a snitch

Snitches are triggered when a player enters the 11 block square shaped radius around 
the snitch block. Players with namelayer permission SNITCH_NOTIFICATIONS on the group
the snitch is reinforced to receive a chat message in the format * <player> entered 
snitch at <snitch name> [world <x>,<y>,<z>]. To create a snitch place a reinforced 
noteblock or jukebox. The snitch name can be set using the /janame <name> command. 
Both noteblocks and jukebox snitches output chat messages on player entry yet jukebox 
snitches have the additional functionality of logging the entry in addition to block 
placement, block breaks and interactions with entities (Such as opening chests, killing
mobs and mounting horses)
  
### Checking snitches
  
Jukebox logs can be checked by players who have the permission READ_SNITCHLOG. Standing 
within snitch range (11 block raduis) and typing /jainfo prints logs in chat while /ja 
opens a GUI containing logs. Both commands display the same information. /jainfo can take 
additional parameters in the syntax 
  
&l/jainfo [<page number> or 'next'] [censor] [action=<action type>] [player=<username>]. 
  
These parameters can be combined in any order. 
