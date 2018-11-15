### 查找队伍函数

###### 用于“寻找队伍”工具的功能。另请参阅：[组查找器功能](https://wow.gamepedia.com/World_of_Warcraft_API#Group_Finder_Functions)和[查找Raid功能](https://wow.gamepedia.com/World_of_Warcraft_API#Looking_for_Raid_Functions)

HW [AcceptProposal](https://wow.gamepedia.com/API_AcceptProposal)\(\) - 接受LFD组邀请并进入地下城。

CanPartyLFGBackfill\(\) - 返回该方是否有资格从LFG池中招募更多成员。

ClearAllLFGDungeons\(\)

CompleteLFGRoleCheck\(boolean\) - boolean = false表示拒绝roleCheck。返回的布尔值似乎表明roleCheck是否成功

CompleteLFGReadyCheck\(\)

[GetInstanceLockTimeRemainingEncounter](https://wow.gamepedia.com/API_GetInstanceLockTimeRemainingEncounter)\(index\) - 返回boss名称,组织,是否击杀.

GetLFDChoiceCollapseState\(nil or table\) - 返回LFGCollapseList

GetLFDChoiceEnabledState\(nil or table\) - 返回LFGEnabledList

GetLFDChoiceLockedState\(nil or table\) - 返回将地下城ID映射到是否锁定的表（在LFD UI中）

GetLFDChoiceOrder\(nil or table\) - 返回 LFDDungeonList

GetLFDLockInfo\(dungeonID, lockedPlayerNumber\) - 返回玩家名称, 锁定原因; 从1到GetLFDLockPlayerCount\(\)的锁定用户数 ;锁定原因在LFG\_INSTANCE\_INVALID\_CODES中查找

GetLFDLockPlayerCount\(\) - 返回地下城组中的锁数

[GetLFGBonusFactionID](https://wow.gamepedia.com/API_GetLFGBonusFactionID)\(\)

[GetLFGBootProposal](https://wow.gamepedia.com/API_GetLFGBootProposal)\(\) - 返回有关正在进行的LFG Kick投票的信息。

GetLFGCategoryForID\(\)

GetLFGCompletionReward\(\)

GetLFGCompletionRewardItem\(\)

[GetLFGDeserterExpiration](https://wow.gamepedia.com/API_GetLFGDeserterExpiration)\(\) - 返回在过早离开组后再次使用地下城查找器的时间。

[GetLFGDungeonEncounterInfo](https://wow.gamepedia.com/API_GetLFGDungeonEncounterInfo)\(\)

[GetLFGDungeonInfo](https://wow.gamepedia.com/API_GetLFGDungeonInfo)\(dungeonId\) - 返回列表中特定地下城的信息：dungeonName，typeID，minLevel，maxLevel，recLevel，minRecLevel，maxRecLevel，expansionLevel，groupID，textureFilename，difficulty，maxPlayers，dungeonDescription，isHoliday

[GetLFGDungeonNumEncounters](https://wow.gamepedia.com/API_GetLFGDungeonNumEncounters)\(\)

GetLFGDungeonRewards\(dungeontype\) - dungeontype = 261（正常）或262（英雄），返回doneToday，moneyBase，moneyVar，experienceBase，experienceVar，numRewards

[GetLFGDungeonRewardCapBarInfo](https://wow.gamepedia.com/API_GetLFGDungeonRewardCapBarInfo)\(dungeontype\) - 返回有关每周点数限制的信息

GetLFGDungeonRewardCapInfo\(\)

GetLFGDungeonRewardInfo\(dungeonID, rewardIndex\) - 返回name，texturePath，quantity。rewardIndex匹配来自GetLFGDungeonRewards的1到numRewards

GetLFGDungeonRewardLink\(\)

GetLFGDungeonShortageRewardInfo\(\)

GetLFGDungeonShortageRewardLink\(\)

GetLFGInfoServer\(\) - 返回 inParty, joined, queued, noPartialClear, achievements, lfgComment, slotCount

GetLFGInviteRoleAvailability\(\)

GetLFGInviteRoleRestrictions\(\)

UI [GetLFGMode](https://wow.gamepedia.com/API_GetLFGMode)\(\) - 返回模式，subMode（有时是空结果）

[GetLFGProposal](https://wow.gamepedia.com/API_GetLFGProposal)\(\) - 返回有关LFD组邀请的信息。

[GetLFGProposalEncounter](https://wow.gamepedia.com/index.php?title=API_GetLFGProposalEncounter&action=edit&redlink=1)\(encounterNumber\) - 返回 bossName, texture, isKilled. encounterNumber is from 1 to totalEncounters from

GetLFGProposal\(\)

GetLFGProposalMember\(playerNumber\) - 在LFG提案中返回有关玩家（数字1-5）的信息：是否队长，角色，级别，应答，接受，名字，职业

[GetLFGQueueStats](https://wow.gamepedia.com/API_GetLFGQueueStats)\(\) - 返回队列中的当前状态和等待时间

GetLFGQueuedList\(\)

[GetLFGRandomCooldownExpiration](https://wow.gamepedia.com/API_GetLFGRandomCooldownExpiration)\(\) - 返回您可能再次为随机地下城排队的时间。

GetLFGRandomDungeonInfo\(index\) - 返回有关随机地下城队列的信息：id，name

GetLFGReadyCheckUpdate\(\)

GetLFGReadyCheckUpdateBattlegroundInfo\(\)

[GetLFGRoles](https://wow.gamepedia.com/API_GetLFGRoles)\(\) - 返回isLeader，isTank，isHealer，isDPS  - 返回您注册的角色，而不是您分配的角色。

[GetLFGRoleShortageRewards](https://wow.gamepedia.com/API_GetLFGRoleShortageRewards)\(dungeonID, shortageSeverity\) -返回有关LFG Call to Arms奖励的信息

GetLFGRoleUpdate\(\) - 返回roleCheckInProgress, slots, members

[GetLFGRoleUpdateBattlegroundInfo](https://wow.gamepedia.com/API_GetLFGRoleUpdateBattlegroundInfo)\(\)

GetLFGRoleUpdateMember\(\)

[GetLFGRoleUpdateSlot](https://wow.gamepedia.com/API_GetLFGRoleUpdateSlot)\(slot\) - 返回特定角色位的地下城类型，地下城ID（整数）

GetLFGSuspendedPlayers\(\)

[GetLFGTypes](https://wow.gamepedia.com/API_GetLFGTypes)\(\) - 返回所有可用的LFG类别

GetNumRandomDungeons\(\) - 返回可以排队的特定地下城的数量

GetPartyLFGBackfillInfo\(\) - 返回有关您当前可以从LFG池中招募其他成员的地下城的信息。

GetPartyLFGID\(\)

GetRandomDungeonBestChoice\(\) - 返回建议的随机地下城ID。

[HasLFGRestrictions](https://wow.gamepedia.com/API_HasLFGRestrictions)\(\) - Returns whether the player is in a random party formed by the dungeon finder system.

IsInLFGDungeon\(\)

[IsLFGComplete](https://wow.gamepedia.com/API_IsLFGComplete)\(\) - Returns whether you have currently finished a Dungeon Finder instance.

IsLFGDungeonJoinable\(dungeonId\) - Returns whether you can queue for a particular dungeon; dungeonId is from GetLFGRandomDungeonInfo

IsPartyLFG\(\)

JoinLFG\(\)

JoinSingleLFG\(\)

LeaveLFG\(\)

LeaveSingleLFG\(\)

[LFGTeleport](https://wow.gamepedia.com/API_LFGTeleport)\(\[toSafety\]\) - Teleports the player to \(toSafety = nil\) or from \(toSafety = true\) a dungeon

PartyLFGStartBackfill\(\)

[RejectProposal](https://wow.gamepedia.com/API_RejectProposal)\(\) - Reject an LFD group invite and exit the queue.

RequestLFDPartyLockInfo\(\)

RequestLFDPlayerLockInfo\(\)

[SetLFGBonusFactionID](https://wow.gamepedia.com/API_SetLFGBonusFactionID)\(\)

SetLFGBootVote\(vote\) - responds to a vote-kick.

SetLFGDungeon\(id\)

SetLFGDungeonEnabled\(dungeonID, isEnabled\)

SetLFGHeaderCollapsed\(headerID, isCollapsed\)

SetLFGRoles\(isLeader, isTank, isHealer, isDPS\) - changes the selected roles

[UninviteUnit](https://wow.gamepedia.com/API_UninviteUnit)\("name" \[, "reason"\]\) - initiate a kick vote in a LFD group.

[UnitGroupRolesAssigned](https://wow.gamepedia.com/API_UnitGroupRolesAssigned)\("unit"\) - Return's the targeted unit's assigned role.

[UnitHasLFGDeserter](https://wow.gamepedia.com/API_UnitHasLFGDeserter)\("unit"\) - returns whether the specified unit has recently deserted

[UnitHasLFGRandomCooldown](https://wow.gamepedia.com/API_UnitHasLFGRandomCooldown)\("unit"\) - returns whether the specified unit has recently queued for a random

