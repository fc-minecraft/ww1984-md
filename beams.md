### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true 
### @explicitHints 1

# Лучи цвета

## Step 1
Помоги Супергерою разместить витражное стекло на лучах света, чтобы оно соответствовало цветовому узору на стене. Тебе нужно будет сказать ему, куда двигаться и какие цвета размещать.

**Доступные блоки:**

``||ww:Двигаться <направление> на <число>||`` - Супергерой двинется в указанном *направлении* на заданное *число* блоков.

``||ww:Повернуть <направление>||`` - Супергерой повернётся в указанном *направлении*.

``||ww:Разместить <цвет> витражное стекло <направление>||`` - Разместить кусок цветного витражного стекла в указанном *направлении*.

``||loops:повторить <число> раз||`` - Повторить код заданное *число* раз.

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        ww.moveWW(Direction.Forward, 1)
        ww.turnWW(LEFT_TURN)
        ww.placeBlock(BeamsGlass.YellowStainedGlass, Direction.Forward)
    }
})
```
```template
player.onChat("run", function () {
    ww.moveWW(Direction.Forward, 3)
    ww.placeBlock(BeamsGlass.LimeStainedGlass, Direction.Right)
})
```
```package
minecraft-ww1984=github:fc-minecraft/ww1984-ts
```