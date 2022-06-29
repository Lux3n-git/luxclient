## &nChat

Chat is range restricted to be local. Messages are only seen within a 1000 block radius from the sending player (plus an additional block in 
range for each each block abovey=100). This range restriction can be bypassed by using chat groups or direct messages. Namelayer allows the 
creation of chat groups. Chat groups are managed with Namelayer which includes functionality for inviting and removing players from groups.

-&l/g <group> [message] 
  &r&fAlias: &l/groupchat &l/gchat &l/gc&r&f 
  Changes chat group to specified group. If [message] is included it is sent to specified group.    
  
-&l/tell <player> [message] 
  &r&fAlias: &l/message &l/msg &l/m &l/pm
  &r&fChanges chat to private message with specified player. f [message] is included it is sent to specified player.  
  
-&l/tell 
  &r&fAlias: &l/message &l/msg &l/m &l/pm &l/e&r&f: Leaves active private message  
  
-&l/exit 
  &r&fAlias: &l/e &l/g&r&f
  Send any further chat messages to local chat (within ~1000 blocks), leaving 
  any active group chats.  
  
-&l/reply [message] 
  &r&fAlias: &l/r &r&f
  Changes chat to private message with last player that has messaged you. 
  If [message] is included it is sent to specified player. Use with caution,
  as another player may message you just before you send the command.  
  
-&l/ignore 
  &r&fAlias: &l/i&r&f 
  Toggle ignoring a player
  
-&l/ignoregroup <group> 
  &r&fAlias:&l/ig &l/igroup &l/ignoreg&r&f
  Toggle ignoring a group  
  
-&l/ignorelist
  &r&fList of ignored groups and players  
  
-&l/afk
  &r&fToggle. Prevents receiving direct messages.  

If you are trying to ignore a group's snitches, the use the command &l/jamute [group] &r&f 
  
