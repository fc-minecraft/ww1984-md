### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints 1

# Скрытое на виду

## Step 1
Преступник, который спланировал ограбление, скрывается среди толпы. Помоги Супергерою проверить каждого человека, чтобы выяснить, кто из них вор в маске, а затем используй лассо правды, чтобы получить последний фрагмент картины.

**Доступные блоки:**

``||ww:Движение <направление> на <число>||`` - Супергерой двинется в указанном *направлении* на заданное *число* блоков.

``||ww:Поворот <направление>||`` - Супергерой повернётся в указанном *направлении*.

``||ww:участник - вор <направление>||`` - Возвращает булево значение (*истина* | *ложь*), является ли участник вором.

``||ww:Лассо вора <направление>||`` - Супергерой использует лассо правды на воре.

``||loops:повторить <число> раз||`` - Повторить код заданное *число* раз.

``||loops:пока <булево>||`` - Повторять код, пока булево значение *истина*.

``||logic:если / тогда||`` - Проверяет, истинно ли условие, и делает что-то, если это так.

``||logic:не <булево>||`` - Изменяет операцию условия. Пример: *пока <истина>* против *пока не <истина>*.

```ghost
    ww.moveWW(Direction.Forward, 1)
    ww.turnWW(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
        
    }
    if (ww.locateGoon(Direction.Forward)) {
        ww.apprehendGoon(Direction.Forward)
    }
    while (!(false)) {
        
    }	
```
```template
    if (ww.locateGoon(Direction.Forward)) {

    }
```
```package
minecraft-ww1984=github:fc-minecraft/ww1984-ts#v0.0.2
```
