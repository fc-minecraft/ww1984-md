### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints 1

# Танцевальная площадка

## Step 1
Цвета на стене, похоже, совпадают с цветами на полу. Помоги Супергерою двигаться по цветным блокам в той же последовательности, что и на стене. Это должно открыть секретную дверь на задней стене.

**Доступные блоки:**
``||ww:Двигаться <направление> на <число>||`` - Супергерой двинется в указанном *направлении* на заданное *число* блоков.
``||ww:Повернуть <направление>||`` - Супергерой повернётся в указанном *направлении*.
``||loops:повторить <число> раз||`` - Повторить код заданное *число* раз.

```ghost
player.onChat("run", function () {
    ww.moveWW(Direction.Forward, 1)
    ww.turnWW(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
        
    }
})
```
```template
player.onChat("run", function () {
    ww.moveWW(Direction.Forward, 1)
    ww.turnWW(RIGHT_TURN)
})
```
```package
minecraft-ww1984=github:fc-minecraft/ww1984-ts
```
