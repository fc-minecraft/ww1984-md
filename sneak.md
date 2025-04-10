### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints 1

# Скрытная миссия

## Step 1
Помоги Супергерою пройти через комнату, не сработав сигнализацию, избегая лазеров. Ему нужно прокрасться сзади и обезвредить преступника.

**Доступные блоки:**

``||ww:Движение <направление> на <число>||`` - Супергерой двинется в указанном *направлении* на заданное *число* блоков.

``||ww:Поворот <направление>||`` - Супергерой повернётся в указанном *направлении*.

``||ww:Обезвредить преступника <направление>||`` - Скрытно обезвредить преступника в указанном *направлении*.

``||loops:повторить <число> раз||`` - Повторить код заданное *число* раз.

```ghost
    for (let index = 0; index < 4; index++) {
        ww.moveWW(Direction.Forward, 1)
        ww.turnWW(LEFT_TURN)
        ww.takedownGoon(Direction.Forward)
    }
```
```template
    ww.moveWW(Direction.Forward, 1)
```
```package
minecraft-ww1984=github:fc-minecraft/ww1984-ts
```
