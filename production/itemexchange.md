## &nItemExchange

Chests contain "Exchange Rules" which are stone buttons with lore containing trade information.

### Browsing shop chests

It is customary to put a sign on the chest with the exchanges. However, if you left click the 
chest there will be text that says what the input and output for the chest are. Note: Always 
check that there is an output! You don't want to put in diamonds only to realize you gave a 
free donation because they forgot to add an output

### Buying from shop chests

There can be multiple exchanges available from a single shop chest. Make sure to left click 
and be looking at the exchange you want (For example Exchange 1/2 or Exchange 2/2). Hold the 
input item in your hand and then right click the chest. The input will be removed from your
hand and the output automatically added to your inventory.
Creating shop chests

### 1) First way to create exchange rules:

    -Hold the item you want, in the quantity you would like, (For example, 5 diamonds) and 
    type /iec input. An exchange rule (lored stone button) will be created in your inventory.
    -Hold the item you are selling, in the quantity you are selling for, (For example, one 
    cow egg) and type /iec output. An exchange rule (lored stone button) will be created in 
    your inventory
    -Place the two buttons in a chest (make sure to reinforce it!). If you left click the 
    chest it will now tell you the exchanges available.

Note: You can place multiple exchanges in a chest. For example, you can have one input rule 
of 5 diamonds and output rule of 1 cow egg. And also have one input rule for 4 diamonds and
one output rule for 1 pig egg in the same chest. Left clicking the chest multiple times will
allow you to move through all the available exchanges.

Note: You can have multiple inputs for one output, or one input for multiple outputs. For example, 
one input rule of 5 diamonds and output rule of 1 cow egg, and a second output rule of 1 pig egg. 
Second example, one input rule of 5 diamonds, and a second input rule for 9 iron blocks and one 
output rule for 1 cow egg.

### 2) Second way to create exchange rules:

If you don't have access to the items you're buying/ selling there are other commands you can use.

&l/iec input [item] [quantity]
For example: /iec input diamond 5

&l/iec output [item] [quantity]
For example: /iec output sapling 10

Note: The name of the item has to be the Minecraft data name. For example, dark_oak_sapling.

### Editing exchange rules

While holding an exchange, use the following command to change the quantity it trades:

&l/ies amount [number]
For example: /ies amount 5. This will change the exchange to trade 5 of whatever item 
