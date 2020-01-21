### Revit Плагин для расстановки мебели 

#### Пользование 

- выбираешь группу мебели в одной комнате
- выбираешь точку в любой комнате

Группа должна копироваться с центром в выбранной точке.

#### Подключение
- Скачать и разархивировать в C:\test\PlaceFurniture-003\PlaceFurniture-003\bin\Release\PlaceFurniture-003.dll
- Сохранить placeFurniture01.addin в папку C:\ProgramData\Autodesk\Revit\Addins\201*\
- Во вкладке **Revit Add-Ins** нажать **Внешние Инструменты**, нажать PlaceFurniture-003.


---
#### Place furniture in rooms Revit plugin according to tutorial:
https://knowledge.autodesk.com/support/revit-products/learn-explore/caas/simplecontent/content/lesson-1-the-basic-plug.html

##### Usage 
###### Enable
unzip to C:\test\PlaceFurniture-003\PlaceFurniture-003\bin\Release\PlaceFurniture-003.dll
Inside Revit on the Add-Ins ribbon tab, click the External Tools drop-down list, then click PlaceFurniture-003. This will start your plug-in.

###### Use
Move the cursor over Room1 in the Revit building model. When the cursor is hovering over the furniture group, its bounding box should be highlighted as per the below picture, with a tooltip showing Model Groups : Model Group : Group 1. Click to select this furniture group. (Note: when highlighted the room looks very similar to the group. Please carefully select the group according to the message in the tooltip. If the room is selected, you will not see the expected result after the following step.)
NOTE:Make sure the TOOLTIP message is ModelGroups…..Then click to pick.

Pick a point in another room, for example in Room 2. You should see the group copied to this location. The center of the new group is the point you selected.



