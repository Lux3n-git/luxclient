### Interaction

Upon passing on the detector rail, the redstone signal will activate only if the player 
on the minecart chose a direction written on the sign. If it's the case, the detector rail 
will send a signal which will allow the T-junction to change direction, thus allowing the 
player to chose a direction. In the example on the right, if the player had the mall set 
has their destination, the detector would send a redstone signal which would change the 
T-junction orientation, thus sending the player to the mall. If the player had another 
destination setup, the detector rail won't send a redstone signal, and the player would 
continue straight up as per the normal T-junction rules. When the redstone signal is sent, 
the T-junction change direction

Additionally, the destination * is a special case, which activates the detector rail if the 
player has any destination set, which can be used to redirect rogue carts and players who've 
forgotten to set their destination.

### Direction of the rail

The intersection minecart will always follow the south-east rule. In the case the rail has to 
be directed in the other direction, a redstone inverter has to be made. This gives two 
additional conditions:
    -The rail has to be at least at y = 4
    -The detector rail has to be placed two blocks before the intersection to make space for 
    the inverter.
