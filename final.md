### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints 1

## Hidden in Plain Sight

# Hidden in Plain Sight
The criminal mastermind who orchestrated this heist has hidden among the gala attendees. Help Wonder Woman investigate each attendee to figure out which is the goon in hiding and then use the lasso of truth to find out where the final piece of the painting is.

**Blocks Available:**  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*Investigate attendee <direction>* - Return a boolean (*true* | *false*) of whether the attendee is a goon or not.  
*Lasso goon <direction>* - Causes Wonder Woman to use her lasso of truth on a goon.  
*repeat <number> times* - Repeat code the specified number of times.  
*if / then* - Checks if a condition is *true* and then does something if so.  
*while <boolean>* - Repeated run the code while the boolean is *true*.  
*not <boolean>* - Switches the operation of a condition. Example: *while <true>* vs. *while not <true>*  

```ghost
ww.moveWW(Direction.Forward, 0)
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```
