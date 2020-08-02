### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints 1

# Stealth Mission
Help Wonder Woman navigate through the room without triggering the alarm by avoiding the lasers. Sneak behind and takedown the goon.

**Blocks Available:**  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*Turn <direction>* - Wonder Woman will turn in the specified direction.  
*Takedown goon <direction>* - Stealthily knock out the goon in the specified direction.  
*repeat <number> times* - Repeat code the specified number of times.  

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        ww.moveWW(Direction.Forward, 0)
        ww.turnWW(Direction.Forward)
        ww.takedownGoon(Direction.Forward)
    }
})
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```
