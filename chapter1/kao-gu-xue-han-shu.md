### 考古学函数

###### 这些功能在[Patch 4.0](https://wow.gamepedia.com/Patch_4.0)中引入。

[ArchaeologyMapUpdateAll](https://wow.gamepedia.com/API_ArchaeologyMapUpdateAll)\(\) 更新挖掘地点并返回当前地图区域中的挖掘地点数量.

ArchaeologyGetIconInfo\(index\)

REMOVED ArcheologyGetVisibleBlobID\(index\) - 返回当前地图区域中的挖掘地点的BlobID（在[补丁7.1.0](https://wow.gamepedia.com/Patch_7.1.0)中删除）

CanItemBeSocketedToArtifact\(itemID\) - 如果可以将项目添加到[selected](https://wow.gamepedia.com/API_SetSelectedArtifact)神器，则返回1。

[CanScanResearchSite](https://wow.gamepedia.com/API_CanScanResearchSite)\(\) - 返回玩家当前是否在挖掘地点。

CanSolveArtifact\(\) - 如果可以解决神器，则返回true。

CloseResearch\(\) -

[GetActiveArtifactByRace](https://wow.gamepedia.com/API_GetActiveArtifactByRace)\(raceIndex\) - 返回种族索引的活动神器的信息。

[GetArchaeologyInfo](https://wow.gamepedia.com/API_GetArchaeologyInfo)\(\) - 返回考古技能的本地化名称。

[GetArchaeologyRaceInfo](https://wow.gamepedia.com/API_GetArchaeologyRaceInfo)\(raceIndex\) - 返回考古学中使用的特定种族的信息。

[GetArchaeologyRaceInfoByID](https://wow.gamepedia.com/API_GetArchaeologyRaceInfoByID)\(researchBranchID\) - 返回种族名称和纹理。

[GetArtifactInfoByRace](https://wow.gamepedia.com/API_GetArtifactInfoByRace)\(raceIndex,artifactIndex\) - 返回特定种族工件的信息。

[GetNumArchaeologyRaces](https://wow.gamepedia.com/API_GetNumArchaeologyRaces)\(\) - 返回游戏中考古比赛的数量。

[GetNumArtifactsByRace](https://wow.gamepedia.com/API_GetNumArtifactsByRace)\(raceIndex\) - 返回玩家从提供的种族中获得的工件数量。

[GetSelectedArtifactInfo](https://wow.gamepedia.com/API_GetSelectedArtifactInfo)\(\) - 返回[selected](https://wow.gamepedia.com/API_SetSelectedArtifact)种族的信息。

[GetArtifactProgress](https://wow.gamepedia.com/API_GetArtifactProgress)\(\) - 返回有关[selected](https://wow.gamepedia.com/API_SetSelectedArtifact)工件的片段信息。

IsArtifactCompletionHistoryAvailable\(\)

ItemAddedToArtifact\(keystoneindex\) - 如果工件中存在梯形图，则返回。

[SetSelectedArtifact](https://wow.gamepedia.com/API_SetSelectedArtifact)\(raceIndex\) - 将所选工件设置为种族索引。

[RemoveItemFromArtifact](https://wow.gamepedia.com/API_RemoveItemFromArtifact)\(\) - 从[selected](https://wow.gamepedia.com/API_SetSelectedArtifact)工件中删除一个梯形图。

[RequestArtifactCompletionHistory](https://wow.gamepedia.com/API_RequestArtifactCompletionHistory)\(\)

[SocketItemToArtifact](https://wow.gamepedia.com/API_SocketItemToArtifact)\(\) - 向[selected](https://wow.gamepedia.com/API_SetSelectedArtifact)工件添加一个梯形图。

SolveArtifact\(\) - 解决[selected](https://wow.gamepedia.com/API_SetSelectedArtifact)工件。

