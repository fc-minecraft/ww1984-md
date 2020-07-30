### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly false
### @hideIteration true
### @explicitHints 1

## Laser Sneak

# Laser Sneak Part 3
In this room Wonder Woman will need to sneak up behind the goon and get the painting piece from him. You'll still need to make sure she avoids tripping the lasers.

**Blocks Available:**  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*Apprehend goon <direction>* - Instruct Wonder Woman to apprehend the goon.  
*repeat <number> times* - Repeat code the specified number of times.  

```ghost
ww.moveWW(Direction.Forward, 0)
ww.apprehendGoon(Direction.Forward)
for (let index = 0; index < 4; index++) {
    
}
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```
