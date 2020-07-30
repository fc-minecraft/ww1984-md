### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly false
### @hideIteration true 
### @explicitHints 1

## Suspicious Cates

# Suspicious Cates
Help Wonder Woman navigate through the crates and find the missing painting piece. Search each one and if she finds the missing puzzle piece, have her break the box to get it.

**Blocks Available:**  
*Search crate <direction>* - Return a boolean (*true* | *false*) of whether the painting is found hidden in the specified direction.  
*Break crate <direction>* - Instruct Wonder Woman to try and retrieve the hidden painting.  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*if / then* - Checks if a condition is *true* and then does something if so.  
*repeat <number> times* - Repeat code the specified number of times.  
*while <boolean>* - Repeated run the code while the boolean is *true*.  
*not <boolean>* - Switches the operation of a condition. Example: *while <true>* vs. *while not <true>*  

```ghost
player.onChat("run", function () {
    if (ww.locatePainting(Direction.Forward)) {
        ww.retrievePainting(Direction.Forward)
        ww.moveWW(Direction.Forward, 0)
    }
    for (let index = 0; index < 4; index++) {
        
    }
    while (!(false)) {
        
    }	
})
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```