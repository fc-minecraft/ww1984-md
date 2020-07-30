### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly false
### @hideIteration true
### @explicitHints 1

## Stealth Mission

# Stealth Mission
Wonder Woman needs to make her way through these rooms without tripping any alarms. If she crosses a laser, the gates will shut! Help her move through the rooms undetected.

**Blocks Available:**  
*Move <direction> by <number>* - Wonder Woman will move in that direction the specified number of blocks.  
*repeat <number> times* - Repeat code the specified number of times.  

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        ww.moveWW(Direction.Forward, 0)
    }
})
```
```package
minecraft-ww1984=github:ReWrite-Media/ww1984-ts
```
