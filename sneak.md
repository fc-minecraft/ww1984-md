### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints 1

# Stealth Mission

## Step 1
Help Wonder Woman move through the room without triggering the alarm by avoiding the lasers. Sneak behind and takedown the goon.

**Blocks Available:**  
``||ww:Move <direction> by <number>||`` - Wonder Woman will move in that direction the specified number of blocks.  
``||ww:Turn <direction>||`` - Wonder Woman will turn in the specified direction.  
``||ww:Takedown goon <direction>||`` - Stealthily knock out the goon in the specified direction.  
``||loops:repeat <number> times||`` - Repeat code the specified number of times.  

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        ww.moveWW(Direction.Forward, 1)
        ww.turnWW(LEFT_TURN)
        ww.takedownGoon(Direction.Forward)
    }
})
```
```template
player.onChat("run", function () {
    ww.moveWW(Direction.Forward, 1)
    ww.turnWW(LEFT_TURN)
})
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```
