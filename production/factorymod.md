Create a factory by placing a furnace, a crafting table and a chest (or trapped chest) side by side. 
Hitting a factory component with a stick in hand is used to interact with the factory.
  -The furnace is used to run the factory. Place charcoal in either or both furnace slots. Hit the furnace 
  with a stick to toggle the factories activation.
  -The crafting table is used to select which factory recipe to run. Hit the crafting table with a stick 
  to open the 'Select a recipe' GUI. Mouse over an item to see which recipe it corresponds to and the number
  of times it has been run. Left click an item to switch recipe.
  -The chest is where recipe inputs and outputs are deposited. The chest may be a double chest. Hit the chest 
   with a stick to see the factory type and health.
Complete the factory setup by placing exactly the ingredients required for a desired factory in the chest. 
Use the commands /fm and /fm [factory name] to see all factories and their recipes.

### Mechanics
Factories have health which degrades over several months When the health reaches zero only the repair 
factory recipe can be ran. This recipe is found in every factories 'Select a recipe' GUI and is symbolized 
by the furnace item. The cost to repair a factory ranges from 5 to 15% of setup cost. After 1000 days in a 
broken state the factory will break permanently and irreparably. If a component (furnace, crafting table 
and chest) or all components of the factory are physically broken they can be replaced in the same location
and the factory can be recreated for half of the initial factory setup creation cost.

### Details
  -The crafting tables 'Select a recipe' GUI has two settings consistent across all factories. 
  The 'Toggle auto select' setting, symbolized by a redstone block when turned on causes the factory 
  to automatically select any recipe it has the ingredients to run whenever it is activated. Be careful as 
  some factories create an output in one recipe and take it as input in another recipe meaning the two 
  products cycle until charcoal runs out. The 'Open menu' setting symbolized by a painting opens a GUI e
  quivalent to the /fm [factory name] command.
  -If the chest becomes full during a factory run, the factory will stop. The only exception might be 
  printing presses which will continue to run and may waste materials in the process (Bug).
  -Redstone that activated the factory furnace will cause the factory to run
  -Factories can be placed vertically
