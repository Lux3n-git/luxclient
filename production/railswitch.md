## &nRailSwitch

RailSwitch (also known as "The /dest Plugin") is a rail transport plugin that allows someone to set a 
destination when using rails. The plugin works by using the redstone mechanics of T-junction, which 
follows the South-east rule, interaction with detector rails. The plugin allows the detector rail to 
send a redstone signal only if the person in the minecart chose the right destination. This plugin can 
only work in one direction as the player has to arrive from a certain direction. Also, it can only 
choose between two destinations for a total of three rail directions : one starting point and two destinations. 

### Usage

If the rail is set up, simply write /dest place where place is the place where you want to go. 
You can also chain destinations /dest place1 place2 etc. this can be useful for taking a route 
via specific junctions, RailSwitch will route players towards signs that contain either place1 
or place2. Stations where /dest has been set up will probably list possible destinations on signs, 
if you use normal direct rails between A and B /dest will do nothing.

### Block placement

A sign with the destination name on it must be placed over a detector rail and reinforced under the 
same group. The sign first line must be [destination], then the other three lines can be destination 
names. They have to be placed before the T-junction. You may also use [!destination], which will 
activate the rail if a player's destination is not on the signs.

### Interaction

Upon passing on the detector rail, the redstone signal will activate only if the player on the minecart 
chose a direction written on the sign. If it's the case, the detector rail will send a signal which will 
allow the T-junction to change direction, thus allowing the player to chose a direction. In the example on 
the right, if the player had the mall set has their destination, the detector would send a redstone signal 
which would change the T-junction orientation, thus sending the player to the mall. If the player had another 
destination setup, the detector rail won't send a redstone signal, and the player would continue straight up 
as per the normal T-junction rules. When the redstone signal is sent, the T-junction change direction

Additionally, the destination * is a special case, which activates the detector rail if the player has any 
destination set, which can be used to redirect rogue carts and players who've forgotten to set their destination.

