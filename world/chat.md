Chat is range restricted to be local. Messages are only seen within a 1000 
block radius from the sending player (plus an additional block in range for 
each each block above y=100). This range restriction can be bypassed by using 
chat groups or direct messages.

Namelayer allows the creation of chat groups. Chat groups are managed with 
Namelayer which includes functionality for inviting and removing players from 
groups. 
The first line is output caused by typing &l/g Circleblob. &r
The second and third line display a message that was types as-is. 
The fourth line, in yellow, is the output of typing &l/g&r. The fifth line was typed as-is.  

-&l/g <group> [message] &rAlias: &l/groupchat &l/gchat &l/gc&r: Changes chat 
  group to specified group. If [message] is included it is sent to specified group.    
  
-&l/tell <player> [message] &rAlias: &l/message &l/msg &l/m &l/pm: 
  &rChanges chat to private message with specified player. If [message] is included 
  it is sent to specified player.  
  
-&l/tell 	Alias: &l/message &l/msg &l/m &l/pm &l/e&r: Leaves active private message  
  
-&l/exit &rAlias: &l/e &l/g&r: Send any further chat messages to local chat 
  (within ~1000 blocks), leaving any active group chats.  
  
-&l/reply [message] &rAlias: &l/r &r:Changes chat to private message with last 
  player that has messaged you. If [message] is included it is sent to specified 
  player. Use with caution, as another player may message you just before you 
  send the command.  
  
-&l/ignore &rAlias: &l/i&r: Toggle ignoring a player
  
-&l/ignoregroup <group> &rAlias:&l/ig &l/igroup &l/ignoreg&r: Toggle ignoring a group  
  
-&l/ignorelist&r:	List of ignored groups and players  
  
-&l/afk&r: Toggle. Prevents receiving direct messages.  

If you are trying to ignore a group's snitches, the use the command &l/jamute [group] &r 
### Namecolors  
Players who donate $10 or more to the CivClassic Patreon have ability to change the color their 
  name displays in chat and tab menu using the command &l&l/namecolor. For $25 the color can be 
  set as rainbow. [2]. Note not to confuse the grey colored names with the greyed out spectator
  names, which unlike namecolor can only be used by superfriends or admins. Note that as of 
  August 2020, the namecolor feature is currently broken. 
