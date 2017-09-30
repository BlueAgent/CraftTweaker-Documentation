# ICTBlockState

An ICTBlockState object represents a block's current state.

## Importing the package
It might be required for you to import the package if you encounter any issues, so better be safe than sorry and add the import.  
`import mods.contenttweaker.BlockState;` 

## Calling an ICTBlockState
You can get an ICTBlockState either as a parameter in an [IBlockAction function](/Mods/ContentTweaker/Vanilla/Advanced_Functionality/Functions/IBlockAction) or from the [Block Bracket Handler](/Mods/ContentTweaker/Vanilla/Brackets/Bracket_Blocks)

`<block:minecraft:dirt>`

## ZenMethods
|ZenMethod  | Return Type                      | Description                          |
|-----------|----------------------------------|--------------------------------------|
|getBlock() | [IBlock](/Vanilla/Blocks/IBlock) | Returns the refered block            |
|getMeta()  | int                              | Returns the refered block's metadata |