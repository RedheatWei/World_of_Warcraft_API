### 团队函数

###### 也可以查看[RAID函数](https://wow.gamepedia.com/World_of_Warcraft_API#Raid_Functions)

[AcceptGroup](https://wow.gamepedia.com/API_AcceptGroup)\(\) - 接受团队邀请.

[ConfirmReadyCheck](https://wow.gamepedia.com/API_ConfirmReadyCheck)\(isReady\) - 表明您是否准备好了。

[ConvertToParty](https://wow.gamepedia.com/API_ConvertToParty)\(\) - 将具有5个或更少成员的团队组转换为小队。

ConvertToRaid\(\) - 小队转换为团队.

DeclineGroup\(\) - 拒绝邀请。

[DoReadyCheck](https://wow.gamepedia.com/API_DoReadyCheck)\(\) - 启动准备检查。

[GetLootMethod](https://wow.gamepedia.com/API_GetLootMethod)\(\) - 返回当前活动的[副本模式](https://wow.gamepedia.com/LootMethod)

[GetLootThreshold](https://wow.gamepedia.com/API_GetLootThreshold)\(\) - 返回当前副本模式（对于团体/主战利品）

[GetMasterLootCandidate](https://wow.gamepedia.com/API_GetMasterLootCandidate)\(index\) - 返回有资格以团长分配模式接收战利品的玩家的名字

[GetNumGroupMembers](https://wow.gamepedia.com/API_GetNumGroupMembers)\(\[groupType\]\) - 获取队伍中玩家数量

[GetNumSubgroupMembers](https://wow.gamepedia.com/API_GetNumSubgroupMembers)\(\[groupType\]\) - 返回您队伍（或raid小队）中其他玩家的数量。

[InviteUnit](https://wow.gamepedia.com/API_InviteUnit)\("name"\) - 邀请指定的玩家加入您当前所在的队伍。

[IsInGroup](https://wow.gamepedia.com/API_IsInGroup)\(\[groupType\]\) - 判断是否在小队.

[IsInRaid](https://wow.gamepedia.com/API_IsInRaid)\(\[groupType\]\) - 判断是否在团队.

[LeaveParty](https://wow.gamepedia.com/API_LeaveParty)\(\) - 退出活动，通常可用于解决“phantom party”错误，这些错误可能会在您实际上没有时在活动中列出您。

[PromoteToLeader](https://wow.gamepedia.com/API_PromoteToLeader)\("unit"\) - 提升队长.

[SetLootMethod](https://wow.gamepedia.com/API_SetLootMethod)\("lootMethod"\[, "masterPlayer" or threshold\]\) - 设置当前分配模式.

[SetLootThreshold](https://wow.gamepedia.com/API_SetLootThreshold)\(itemQuality\) - 设置组/主战利品的阈值

HW [UninviteUnit](https://wow.gamepedia.com/API_UninviteUnit)\("name" \[, "reason"\]\) - 如果玩家是小组长，则踢出一个单位;或者在LFD小组中发起投票。

[UnitInParty](https://wow.gamepedia.com/API_UnitInParty)\("unit"\) - 如果单位是小队成员,返回true.

[UnitIsGroupLeader](https://wow.gamepedia.com/API_UnitIsGroupLeader)\("unit" or "player name"\) - 如果单位是您的队长，则返回true。

