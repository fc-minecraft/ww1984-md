### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly false
### @hideIteration true 
### @explicitHints 1

## Beams of Color

# Beams of Color
Place stained glass over the beacons to match the color sequence needed to unlock the painting piece.

**Blocks Available:**  
*Place <color> Stained Glass <direction>* - Place a piece of colored stained glass in the specified direction.  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*repeat <number> times* - Repeat code the specified number of times.  

```ghost
ww.placeBlock(BeamsGlass.YellowStainedGlass, Direction.Forward)
ww.moveWW(Direction.Forward, 0)
for (let index = 0; index < 4; index++) {
    
}
```

```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```