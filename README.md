ThaumicMachines
===============

Thaumcraft extension mod with machines powered by aspects, with potential for essence transport

Idea for first machine:

Thaumic processor:

  Takes 5 essentia types:

    1. Praecantatio
      - small amount used per action (1/8 unit)
    2. ignis
      - used to cook items (1/item)
    3. potentia
      - used in purification of ores, used alone with ore creates native cluster (1/item)
    4. Fractus
      - used to "pulverize" ores into dusts(1/item)
    5. Tempus
      - used to "speed up" processing (? unit doubles speed for one step [halves processing time])

Ores:

    Single step:
      ignis -> single ingot
      potentia -> native cluster
      fractus -> 2 dusts
	
    2 steps:
      fractus + ignis -> 2 ingots
      fractus + potentia -> 2-3 dusts (weighted towards 2, <1/3 chance of 3)
      potentia + ignis -> 2 ingots
	
    3 steps:
      fractus + potentia + ignis -> 2-3 dusts (wighted towards 3, >1/3 chance of 3)
		
		
Meat: 

    Single step:
      ignis -> 1 cooked meat
      potentia -> 1-3 nuggets + 1-3 charcoal nuggets
      fractus -> 6-9 raw nuggets

    dual step:
      ignis + potentia -> 6-9 total cooked/charcoal nuggets
      fractus + ignis -> 6-9 cooked nuggets
      fractus + potentia -> 6-9 total cooked/charcoal nuggets
		
    triple step:
      fractus + potentia + ignis -> 8-12 total cooked/charcoal nuggets
	
Dusts:

    ignis -> single ignot
    potentia -> 9 nuggets
    fractus -> dust
	
    (processed f/p/i, so any combination results in the final one in the list)
	
Native clusters:
    
    ignis -> two ingots
    potentia -> native clusters
    fractus -> two dusts
	
    (processed f/p/i, so any combination results in the final one in the list)

Raw nuggets:

    ignis -> (1/9 unit/nugget) cooked nuggets
    potentia -> (1/9 unit/nugget) chance of cooked/charcoal nugget
    fractus -> ??
