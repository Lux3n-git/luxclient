## &nKira

### Overview

Kira is a plugin that lets the player create relays on discord. These relays can 
display snitch hits, chat messages and player login/logout.

The commands can be issued in any Discord channel that Kira can read (e.g., &l!kira help&r&f), 
or sent via direct message (without the prefix, e.g., just help).

### Authenticating

Authentication is required before using Kira. This will link the discord account to the IG account.

In order to do that &l/discordauth &r&fmust be performed on the server. This will create a token. 
The token must be then transmitted to Kira through discord in order to perform the authentication 
using &lauth [token]&r&f.
In Game commands

    -&l/deletediscordchannel
    
    -&l/discordauth 
        Creates auth code
        
    -&l/linkdiscordchannel
    
    -&l/syncdiscordchannel
