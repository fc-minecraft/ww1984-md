### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly false
### @hideIteration true
### @explicitHints 1

## Hidden in Plain Sight

# Hidden in Plain Sight
The final goon is hiding amongst the gala attendees. Help Wonder Woman find and apprehend him.

**Blocks Available:**  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*Locate goon <direction>* - Return a boolean (*true* | *false*) of whether the goon is found in the specified direction.  
*Apprehend goon <direction>* - Instruct Wonder Woman to apprehend the goon.  
*repeat <number> times* - Repeat code the specified number of times.  
*if / then* - Checks if a condition is *true* and then does something if so.  
*while <boolean>* - Repeated run the code while the boolean is *true*.  
*not <boolean>* - Switches the operation of a condition. Example: *while <true>* vs. *while not <true>*  

```ghost
ww.moveWW(Direction.Forward, 0)
ww.locateGoon(Direction.Forward)
ww.apprehendGoon(Direction.Forward)
for (let index = 0; index < 4; index++) {
    
}
if () {
    
}
while (true) {
    
}
!(false)
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```
