### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @flyoutOnly true
### @hideIteration true 
### @explicitHints 1

# Подозрительные ящики

## Step 1
Помоги Супергерою пройти через ящики и найти пропавший фрагмент картины. Обследуй каждый ящик, и если он найдёт пропавший фрагмент пазла, пусть разрушит ящик, чтобы забрать его.

**Доступные блоки:**

``||ww:Движение <направление> на <число>||`` - Супергерой двинется в указанном *направлении* на заданное *число* блоков.

``||ww:Поворот <направление>||`` - Супергерой повернётся в указанном *направлении*.

``||ww:картина в ящике <направление>||`` - Возвращает булево значение (*истина* | *ложь*), находится ли картина спрятанной в указанном *направлении*.

``||ww:Разрушить ящик <направление>||`` - Супергерой пытается достать спрятанную картину.

``||loops:повторить <число> раз||`` - Повторить код заданное *число* раз.

``||loops:пока <булево>||`` - Повторять код, пока булево значение *истина*.

``||logic:если / тогда||`` - Проверяет, истинно ли условие, и делает что-то, если это так.

``||logic:не <булево>||`` - Изменяет операцию условия. Пример: *пока <истина>* против *пока не <истина>*.

```ghost
    ww.moveWW(Direction.Forward, 1)
    ww.turnWW(LEFT_TURN)
    if (ww.locatePainting(Direction.Forward)) {
        ww.retrievePainting(Direction.Forward)
    }
    for (let index = 0; index < 4; index++) {
        
    }
    while (!(false)) {
        
    }	
```
```template
    if (ww.locatePainting(Direction.Forward)) {

    }
```
```package
minecraft-ww1984=github:fc-minecraft/ww1984-ts#v0.0.2
```