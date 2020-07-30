### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly false
### @hideIteration true 
### @explicitHints 1

## Search the crates

# Search the crates
Move through the boxes to find and retrieve the painting.

**Blocks Available:**  
*Locate painting <direction>* - Return a boolean (*true* | *false*) of whether the painting is found hidden in the specified direction.  
*Retrieve painting <direction>* - Instruct Wonder Woman to try and retrieve the hidden painting.  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*if / then* - Checks if a condition is *true* and then does something if so.  
*repeat <number> times* - Repeat code the specified number of times.  
*while <boolean>* - Repeated run the code while the boolean is *true*.  
*not <boolean>* - Switches the operation of a condition. Example: *while <true>* vs. *while not <true>*  

```ghost
ww.retrievePainting(Direction.Forward)
ww.moveWW(Direction.Forward, 0)
if (ww.locatePainting(Direction.Forward)) {
    
}
for (let index = 0; index < 4; index++) {
    
}
while (!(false)) {
    
}
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```