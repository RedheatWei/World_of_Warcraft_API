### 阵营函数

###### 这里的阵营应该属于各种派系,比如说暴风城声望,奥格瑞玛声望,水土派熊猫人声望,加基森声望等.

[CollapseFactionHeader](https://wow.gamepedia.com/API_CollapseFactionHeader)\(index\) - 折叠阵营标题行.

CollapseAllFactionHeaders\(\) - 折叠所有阵营标题行.

[ExpandFactionHeader](https://wow.gamepedia.com/API_ExpandFactionHeader)\(index\) - 展开阵营标题行。

ExpandAllFactionHeaders\(\) - 展开所有阵营标题行。

[FactionToggleAtWar](https://wow.gamepedia.com/API_FactionToggleAtWar)\(index\) - 为一个阵营切换战争旗帜。

[GetFactionInfo](https://wow.gamepedia.com/API_GetFactionInfo)\(index\) - 获取特定派系/阵营标题的详细信息。

[GetFactionInfoByID](https://wow.gamepedia.com/API_GetFactionInfoByID)\(factionID\) - 通过factionID获取特定阵营的详细信息。

[GetFriendshipReputation](https://wow.gamepedia.com/API_GetFriendshipReputation)\(factionID\) - 获取有关NPC朋友的详细信息。（在5.1.0中添加）

[GetFriendshipReputationRanks](https://wow.gamepedia.com/API_GetFriendshipReputationRanks)\(factionID\) - 获取有关NPC朋友的等级数据。（在5.1.0中添加）

[GetNumFactions](https://wow.gamepedia.com/API_GetNumFactions)\(\) - 返回阵营显示中的行数。

GetSelectedFaction\(\) - 返回信誉窗口中当前所选阵营的行索引。（在1.10中添加）

[GetWatchedFactionInfo](https://wow.gamepedia.com/API_GetWatchedFactionInfo)\(\) - 返回有关当前查看的阵营的信息。

[IsFactionInactive](https://wow.gamepedia.com/API_IsFactionInactive)\(index\) - 如果阵营被标记为非活动，则返回true。

[SetFactionActive](https://wow.gamepedia.com/API_SetFactionActive)\(index\) - 从非活动组中删除一个阵营。

[SetFactionInactive](https://wow.gamepedia.com/API_SetFactionInactive)\(index\) - 将阵营移动到非活动组。

SetSelectedFaction\(index\) - 在声望窗口中设置当前选定的阵营。（在1.10中添加）

[SetWatchedFactionIndex](https://wow.gamepedia.com/API_SetWatchedFactionIndex)\(index\) - Sets which faction should be watched in Blizzard reputation bar.

[C\_Reputation.GetFactionParagonInfo](https://wow.gamepedia.com/API_C_Reputation.GetFactionParagonInfo)\(factionID\) - Gets Paragon information. \(added in 7.2.0\)

[C\_Reputation.IsFactionParagon](https://wow.gamepedia.com/API_C_Reputation.IsFactionParagon)\(factionID\) - Returns true/false if a factionID is a Paragon. \(added in 7.2.0\)

C\_Reputation.RequestFactionParagonPreloadRewardData \(factionID\) - Queries the server to pre-load Paragon reward data. \(added in 7.2.0\)

