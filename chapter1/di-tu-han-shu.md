### 地图函数

###### 这些功能与世界地图的显示有关。另请参见[位置功能](https://wow.gamepedia.com/World_of_Warcraft_API#Location_Functions)。

ClickLandmark\(id\) - ?

[GetCorpseMapPosition](https://wow.gamepedia.com/API_GetCorpseMapPosition)\(\) - 返回当前世界地图上尸体的位置。

[GetCurrentMapAreaID](https://wow.gamepedia.com/API_GetCurrentMapAreaID)\(\) - 返回当前地图的区域ID。

[GetCurrentMapContinent](https://wow.gamepedia.com/API_GetCurrentMapContinent)\(\) - 返回当前显示世界地图的大陆的编号。

[GetCurrentMapDungeonLevel](https://wow.gamepedia.com/API_GetCurrentMapDungeonLevel)\(\) - 返回当前显示的多级地图的哪个级别。

[GetCurrentMapZone](https://wow.gamepedia.com/API_GetCurrentMapZone)\(\) - 返回世界地图当前显示的区域编号。

[GetMapContinents](https://wow.gamepedia.com/API_GetMapContinents)\(\) - 返回大陆名称。

GetMapDebugObjectInfo\(id\) - ?

[GetMapInfo](https://wow.gamepedia.com/API_GetMapInfo)\(\) - 返回当前世界地图的名称和大小。

[GetMapLandmarkInfo](https://wow.gamepedia.com/API_GetMapLandmarkInfo)\(landmarkIndex\) - 返回有关当前世界地图上的地标的信息。

[GetMapNameByID](https://wow.gamepedia.com/API_GetMapNameByID)\(id\) - 返回ID指定的区域的完整本地化名称。

[GetMapOverlayInfo](https://wow.gamepedia.com/API_GetMapOverlayInfo)\(overlayIndex\) - 返回有关当前世界地图上叠加层的信息。

[GetMapZones](https://wow.gamepedia.com/API_GetMapZones)\(continentIndex\) - 返回大陆的区域名称。

[GetNumDungeonMapLevels](https://wow.gamepedia.com/API_GetNumDungeonMapLevels)\(\) - 返回当前显示的区域映射中的级别数（0表示无）。

GetNumMapDebugObjects\(\) - ?

[GetNumMapLandmarks](https://wow.gamepedia.com/API_GetNumMapLandmarks)\(\) - 返回当前世界地图上的地标数。

[GetNumMapOverlays](https://wow.gamepedia.com/API_GetNumMapOverlays)\(\) - 返回当前世界地图上的叠加层数。

[GetPlayerMapPosition](https://wow.gamepedia.com/API_GetPlayerMapPosition)\("unit"\) - 返回当前世界地图上单位的位置。

[GetPlayerFacing](https://wow.gamepedia.com/API_GetPlayerFacing)\(\) - 返回玩家面对的方向。

[ProcessMapClick](https://wow.gamepedia.com/API_ProcessMapClick)\(x,y\) - 将单击传递给客户端，然后客户端计算是否必须更改区域。

SetDungeonMapLevel\(level\) - 设置当前显示的多级地图（达拉然，地下城等）的哪个级别。

[SetMapByID](https://wow.gamepedia.com/API_SetMapByID)\(id\) - Set map by area id.

[SetMapToCurrentZone](https://wow.gamepedia.com/API_SetMapToCurrentZone)\(\) - 将当前世界地图设置为玩家当前所在的区域。

[SetMapZoom](https://wow.gamepedia.com/API_SetMapZoom)\(continentIndex\[, zoneIndex\]\) - 将当前世界地图设置为特定大陆和可选区域。

[SetupFullscreenScale](https://wow.gamepedia.com/API_SetupFullscreenScale)\(\) - 将全屏视图的比例（例如世界地图）配置为最佳填充屏幕。

[UnitPosition](https://wow.gamepedia.com/API_UnitPosition)\("unit"\) - 返回当前世界区域内单位的位置。

[UpdateMapHighlight](https://wow.gamepedia.com/API_UpdateMapHighlight)\(x,y\) - 提供突出显示的地图翻转信息。

ZoomOut\(\) - “缩小”当前地图：从区域到大陆到世界观。



