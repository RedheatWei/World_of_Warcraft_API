### 公会函数

[AcceptGuild](https://wow.gamepedia.com/API_AcceptGuild)\(\) - 玩家接受加入公会的邀请。

[BuyGuildCharter](https://wow.gamepedia.com/API_BuyGuildCharter)\("guildName"\) - 购买公会注册表

CanEditGuildEvent\(\) - 如果允许您编辑公会事件（在日历中），则返回true，

CanEditGuildInfo\(\) - 如果允许您编辑公会信息，则返回true

[CanEditMOTD](https://wow.gamepedia.com/API_CanEditMOTD)\(\) - 如果允许您编辑公会motd，则返回true。

CanEditOfficerNote\(\) - 如果允许您编辑公会成员的官员记录，则返回true。

CanEditPublicNote\(\) - 如果允许您编辑公会成员的公共注释，则返回true。

[CanGuildDemote](https://wow.gamepedia.com/API_CanGuildDemote)\(\) - 如果允许降级公会成员，则返回true。

[CanGuildInvite](https://wow.gamepedia.com/API_CanGuildInvite)\(\) - 如果允许您邀请新成员加入公会，则返回true。

[CanGuildPromote](https://wow.gamepedia.com/API_CanGuildPromote)\(\) - 如果允许降级公会成员，则返回true。

CanGuildRemove\(\) - 如果允许删除公会成员，则返回true。

[CanReplaceGuildMaster](https://wow.gamepedia.com/API_CanReplaceGuildMaster)\(\) - 返回是否可以因不活动而弹劾公会会长。

[CanViewOfficerNote](https://wow.gamepedia.com/API_CanViewOfficerNote)\(\) - 如果允许您查看官员备注，则返回true。

CloseGuildRegistrar\(\) - ?.

CloseGuildRoster\(\) - ?.

CloseTabardCreation\(\) - ?.

[DeclineGuild](https://wow.gamepedia.com/API_DeclineGuild)\(\) - 玩家拒绝加入公会的邀请。

[GetGuildApplicantInfo](https://wow.gamepedia.com/API_GetGuildApplicantInfo)\(index\) - 返回有关公会申请人的信息。

GetGuildCharterCost\(\) - 返回购买公会章程的费用。

GetGuildEventInfo\(index\) - 返回事件信息。（在2.3中添加）

[GetGuildFactionInfo](https://wow.gamepedia.com/API_GetGuildFactionInfo)\(\) - 返回玩家的公会名称和公会职位。

[GetGuildInfo](https://wow.gamepedia.com/API_GetGuildInfo)\("unit"\) - 此函数返回公会单位所属的名称。

GetGuildInfoText\(\) - 返回持久的公会信息数据。（在1.9中添加）

REMOVED GetGuildRosterContribution\(index\) - 返回每周和总XP以及每周和总排名。

REMOVED GetGuildRosterLargestContribution\(\) - 返回最大每周XP和最大总XP。

GetGuildRosterLargestAchievementPoints\(\) - 返回最大成就点数。

[GetGuildRosterInfo](https://wow.gamepedia.com/API_GetGuildRosterInfo)\(index\) - 此函数用于获取公会成员的信息。

[GetGuildRosterLastOnline](https://wow.gamepedia.com/API_GetGuildRosterLastOnline)\(index\) - 返回当前排序顺序中indexth成员自上次联机以来的时间。

[GetGuildRosterMOTD](https://wow.gamepedia.com/API_GetGuildRosterMOTD)\(\) - 返回公会的MOTD.

[GetGuildRosterSelection](https://wow.gamepedia.com/API_GetGuildRosterSelection)\(\) - 返回当前所选公会成员的索引。

[GetGuildRosterShowOffline](https://wow.gamepedia.com/API_GetGuildRosterShowOffline)\(\) - 如果显示公会的脱机成员，则返回true。

[GetGuildTradeSkillInfo](https://wow.gamepedia.com/API_GetGuildTradeSkillInfo)\(index\) - Returns the tradeskill index for a guild tradeskill using the index from GetNumGuildTradeSkill

[GetNumGuildApplicants](https://wow.gamepedia.com/API_GetNumGuildApplicants)\(\) - 返回公会申请人的总数。

GetNumGuildEvents\(\) - 返回公会事件的数量。（在2.3中添加）

[GetNumGuildMembers](https://wow.gamepedia.com/API_GetNumGuildMembers)\(\) - 返回总公会成员和在线公会成员的数量。

GetNumGuildTradeSkill\(\) - 返回公会UI可用的交易技能数量

GetTabardCreationCost\(\) - 返回铜币的成本。

GetTabardInfo\(\) -?.

GuildControlAddRank\("name"\) - 添加另一个名为“name”的排名。仅限公会会长。

[GuildControlDelRank](https://wow.gamepedia.com/API_GuildControlDelRank)\("name"\) - 删除排名“name”。仅限公会会长。

GuildControlGetNumRanks\(\) - 返回公会框架打开后的排名数。任何公会成员都可以使用它。

[GuildControlGetRankFlags](https://wow.gamepedia.com/API_GuildControlGetRankFlags)\(\) - 返回选择等级的每个权限的值列表（默认等级1）。

[GuildControlGetRankName](https://wow.gamepedia.com/API_GuildControlGetRankName)\(index\) - 返回索引处的排名。任何公会成员都可以使用它。

[GuildControlSaveRank](https://wow.gamepedia.com/API_GuildControlSaveRank)\("name"\) - 保存排名“name”的权限。仅限公会会长。

[GuildControlSetRank](https://wow.gamepedia.com/API_GuildControlSetRank)\(rank\) - 设置要查看的当前所选等级。.

[GuildControlSetRankFlag](https://wow.gamepedia.com/API_GuildControlSetRankFlag)\(index, enabled\) - 启用/禁用索引处的操作权限。仅限公会会长。

[GuildDemote](https://wow.gamepedia.com/API_GuildDemote)\("name"\) - 给指定玩家降级.

[GuildDisband](https://wow.gamepedia.com/API_GuildDisband)\(\) - 解散公会。你必须是公会的领导者才能这样做。小心，在解散之前没有给出任何警告。

[GuildInfo](https://wow.gamepedia.com/API_GuildInfo)\(\) - 显示有关您所属的公会的信息。

[GuildInvite](https://wow.gamepedia.com/API_GuildInvite)\("name"\) - 邀请玩家加入你的公会。

[GuildLeave](https://wow.gamepedia.com/API_GuildLeave)\(\) - 退出公会.

[GuildPromote](https://wow.gamepedia.com/API_GuildPromote)\("name"\) - 提升玩家“name”。

[GuildRoster](https://wow.gamepedia.com/API_GuildRoster)\(\) - 获取公会列表并触发GUILD\_ROSTER\_UPDATE事件。

[GuildRosterSetOfficerNote](https://wow.gamepedia.com/API_GuildRosterSetOfficerNote)\(index, "note"\) - 添加官员备注

[GuildRosterSetPublicNote](https://wow.gamepedia.com/API_GuildRosterSetPublicNote)\(index, "note"\) - 添加公共备注

[GuildSetMOTD](https://wow.gamepedia.com/API_GuildSetMOTD)\("note"\) - 将当天的公会消息设置为“note”。

[GuildSetLeader](https://wow.gamepedia.com/API_GuildSetLeader)\("name"\) - 转移公会会长

GuildUninvite\("name"\) - 踢出公会

[IsGuildLeader](https://wow.gamepedia.com/API_IsGuildLeader)\("name"\) - 查看玩家是否为公会会长

[IsInGuild](https://wow.gamepedia.com/API_IsInGuild)\(\) - Lets you know whether you are in a guild.

QueryGuildEventLog\(\) - Fetches the guild event list and fires a GUILD\_EVENT\_LOG\_UPDATE event. \(Added in 2.3\)

[ReplaceGuildMaster](https://wow.gamepedia.com/API_ReplaceGuildMaster)\(\) - Impeaches the current Guild Master.

[RequestGuildApplicantsList](https://wow.gamepedia.com/API_RequestGuildApplicantsList)\(\) - Requests information about guild applicants.

[SetGuildInfoText](https://wow.gamepedia.com/API_SetGuildInfoText)\(\) - Sets the persistant Guild Information data. Limit is 500 letters \(GuildInfoEditBox is limited to this number\). Longer texts are possible, but will be reseted during the day. \(added in 1.9\)

[SetGuildRosterSelection](https://wow.gamepedia.com/API_SetGuildRosterSelection)\(index\) - Selects/deselects a guild member according current sorting order.

[SetGuildRosterShowOffline](https://wow.gamepedia.com/API_SetGuildRosterShowOffline)\(enabled\) - Sets/Resets the show offline members flag.

[SortGuildRoster](https://wow.gamepedia.com/API_SortGuildRoster)\("sort"\) - Sorts guildroster according "sort". Any unknown values sort on "name".

