# Obsidian

# Fresh TODOs:  
  TODO: Look at code generation, is there a problem with the memory management ? 
  TODO: global arrays have sizes! make the code generation aware of this! 
        

## Next version of Obsidian
* Features (in progress): 
    * Only one kind of Pull array.
      However, it can have either Dynamic or Statically known length.
    * A Set of lift functional that lifts local computations 
      to global, lifts sequential into local. 
    * A collection of sequential building blocks for sequential (reg->reg 
      computations). 
      Currently: Fold 
                 Scan 
		 