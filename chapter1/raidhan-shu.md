### Raid函数

###### 另请参阅[团队函数](https://wow.gamepedia.com/World_of_Warcraft_API#Group_Functions)。

ClearRaidMarker\(index\) - 从世界中删除raid标记。（4.0.1）

[ConvertToParty](https://wow.gamepedia.com/API_ConvertToParty)\(\) - 将具有5个或更少成员的raid组转换为小队。（4.0.1）

ConvertToRaid\(\) - 小队转换为团队

DemoteAssistant\("unit"\) - 取消助理。需要团队领袖。

GetAllowLowLevelRaid\(\) - 返回是否为当前字符启用了加入低级别raid。

GetPartyAssignment\("assignment"\) - 返回分配给给定角色的单位的unitID。

GetPartyAssignment\("assignment", "unit"\) - 根据单元是否分配给给定角色返回值。

[GetRaidRosterInfo](https://wow.gamepedia.com/API_GetRaidRosterInfo)\(index\) - 返回有关raid成员的信息。

[GetRaidTargetIndex](https://wow.gamepedia.com/API_GetRaidTargetIndex)\("unit"\) - 获取分配给单位的raid目标索引。

GetReadyCheckStatus\("unit"\) - 返回raid成员对当前就绪检查的响应。

IsRaidMarkerActive\(index\) - 返回index指定的raid标记是否处于活动状态。

PROTECTED PlaceRaidMarker\(index\) - 打开一个目标圈，在世界上放置一个raid标记。（4.0.1）

PromoteToAssistant\("unit"\) - 将玩家提升为助理状态。需要团队领袖。

[RequestRaidInfo](https://wow.gamepedia.com/API_RequestRaidInfo)\(\) - 返回有关保存到的实例的信息。

PROTECTED SetPartyAssignment\("assignment", player\) \(2.3.3\)

SetAllowLowLevelRaid\(allowed\) - 控制当前角色是否可以加入低级别的raid。

[SetRaidSubgroup](https://wow.gamepedia.com/API_SetRaidSubgroup)\(index, subgroup\) - 将raid成员从其当前子组移动到另一个（非完整）小队。

PROTECTED [SwapRaidSubgroup](https://wow.gamepedia.com/API_SwapRaidSubgroup)\(index1, index2\) - 将raid成员交换成不同的组。

[SetRaidTarget](https://wow.gamepedia.com/API_SetRaidTarget)\("unit", index\) - 在单位上设置raid图标。

UI [SetRaidTargetIcon](https://wow.gamepedia.com/API_SetRaidTargetIcon)\("unit", index\) - 将raid图标设置或重置为一个单位。

[UnitInRaid](https://wow.gamepedia.com/API_UnitInRaid)\("unit"\) - 如果单位在你的raid中，则返回1，否则返回nil。

