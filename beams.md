### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true 
### @explicitHints 1

# Beams of Color

## Step 1
Help Wonder Woman place stained glass over the beams of light to match the color sequence displayed on the wall. You'll need to tell her where to move and which colors to place. 

**Blocks Available:**  
``||ww:Move <direction> by <number>||`` - Wonder Woman will move in that direction the specified number of blocks.  
``||ww:Turn <direction>||`` - Wonder Woman will turn in the specified direction.  
``||ww:Place <color> Stained Glass <direction>||`` - Place a piece of colored stained glass in the specified direction.  
``||loops:repeat <number> times||`` - Repeat code the specified number of times.  

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        ww.moveWW(Direction.Forward, 0)
        ww.turnWW(Direction.Forward)
        ww.placeBlock(BeamsGlass.YellowStainedGlass, Direction.Forward)
    }
})
```

```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```