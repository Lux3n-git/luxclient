## RealisticBiomes

### Growth rate

Growth rates drastically vary across biome type. In some biomes certain plants 
will not grow at all. There are two types of growth rate:
    -Fixed (Persistent plants such as wheat, potato and beetroot) : growth rate 
    given in hours
    -Percentage based (Non-persistent plants such as cactus, melon, mushroom): 
    growth rate given as percent of vanilla growth chance.

A biomes growth rate can be checked in multiple ways:
    -Left clicking the ground with plant item in hand
        -Returns the growth time of the item in hand at the free block above the 
        block you're hitting, or the block on the side relative to where you're 
        hitting if it is not the top side. For cocoa for example, you will want 
        to hit a jungle tree on it's side to get meaningful growth time. This growth 
        time includes all factors such as biome, light, and surrounding blocks. You 
        can also do this with fishable items, but in this case the fishing probability
        will only be reported if it is not zero to spare you from chat spam.
    -Right clicking a plant block with a stick
        -Returns how long it will take until fully grown for fixed growth time crops. 
        This can also be done to view animal growth rates (as fraction of vanilla).
    -typing /rb which brings up a GUI containing the growth rates of plants in current 
    biome.

In an optimal setting growth takes around 3 hours for small crops like wheat and potatoes, 
and for trees between 3 to 8 hours. Growth rates are generally lowest in realistic or 
reasonable corresponding biomes. For example, the biome of deep ocean has one of the worst 
growth rates. ReaslisticBiome's also changes fishing probabilities and one can hit the 
ground with a fishable item to see its fishing probability (if it is not zero). Fishing 
is restricted to water biomes.
