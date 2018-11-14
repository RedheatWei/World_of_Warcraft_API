### 查找队伍函数

###### 用于“寻找队伍”工具的功能。另请参阅：[组查找器功能](https://wow.gamepedia.com/World_of_Warcraft_API#Group_Finder_Functions)和[查找Raid功能](https://wow.gamepedia.com/World_of_Warcraft_API#Looking_for_Raid_Functions)

HW [AcceptProposal](https://wow.gamepedia.com/API_AcceptProposal)\(\) - Accept an LFD group invite and enter the dungeon.

CanPartyLFGBackfill\(\) - Returns whether the party is eligible to recruit additional members from the LFG pool.

ClearAllLFGDungeons\(\)

CompleteLFGRoleCheck\(boolean\) - boolean = false means declining the roleCheck. The returned boolean seems to indicate that the roleCheck was successful?

CompleteLFGReadyCheck\(\)

[GetInstanceLockTimeRemainingEncounter](https://wow.gamepedia.com/API_GetInstanceLockTimeRemainingEncounter)\(index\) - returns bossName, texture, isKilled

GetLFDChoiceCollapseState\(nil or table\) - returns LFGCollapseList

GetLFDChoiceEnabledState\(nil or table\) - returns LFGEnabledList

GetLFDChoiceLockedState\(nil or table\) - Returns a table mapping dungeonID to isLocked \(in LFD UI\)

GetLFDChoiceOrder\(nil or table\) - returns LFDDungeonList

GetLFDLockInfo\(dungeonID, lockedPlayerNumber\) - returns playerName, lockedReason; lockedPlayerNumber is from 1 to GetLFDLockPlayerCount\(\); lockedReason is found in LFG\_INSTANCE\_INVALID\_CODES

GetLFDLockPlayerCount\(\) - returns the number of locks in a dungeon group

[GetLFGBonusFactionID](https://wow.gamepedia.com/API_GetLFGBonusFactionID)\(\)

[GetLFGBootProposal](https://wow.gamepedia.com/API_GetLFGBootProposal)\(\) - Returns information about an LFG Kick vote in progress.

GetLFGCategoryForID\(\)

GetLFGCompletionReward\(\)

GetLFGCompletionRewardItem\(\)

[GetLFGDeserterExpiration](https://wow.gamepedia.com/API_GetLFGDeserterExpiration)\(\) - Returns the time at which you may once again use the dungeon finder after prematurely leaving a group.

[GetLFGDungeonEncounterInfo](https://wow.gamepedia.com/API_GetLFGDungeonEncounterInfo)\(\)

[GetLFGDungeonInfo](https://wow.gamepedia.com/API_GetLFGDungeonInfo)\(dungeonId\) - Returns information about a particular dungeon in the list: dungeonName, typeID, minLevel, maxLevel, recLevel, minRecLevel, maxRecLevel, expansionLevel, groupID, textureFilename, difficulty, maxPlayers, dungeonDescription, isHoliday

[GetLFGDungeonNumEncounters](https://wow.gamepedia.com/API_GetLFGDungeonNumEncounters)\(\)

GetLFGDungeonRewards\(dungeontype\) - dungeontype = 261 \(normal\) or 262 \(heroic\), returns doneToday, moneyBase, moneyVar, experienceBase, experienceVar, numRewards

[GetLFGDungeonRewardCapBarInfo](https://wow.gamepedia.com/API_GetLFGDungeonRewardCapBarInfo)\(dungeontype\) - returns information on the weekly point limits

GetLFGDungeonRewardCapInfo\(\)

GetLFGDungeonRewardInfo\(dungeonID, rewardIndex\) - returns name, texturePath, quantity. rewardIndex matches 1 through numRewards from GetLFGDungeonRewards

GetLFGDungeonRewardLink\(\)

GetLFGDungeonShortageRewardInfo\(\)

GetLFGDungeonShortageRewardLink\(\)

GetLFGInfoServer\(\) - returns inParty, joined, queued, noPartialClear, achievements, lfgComment, slotCount

GetLFGInviteRoleAvailability\(\)

GetLFGInviteRoleRestrictions\(\)

UI [GetLFGMode](https://wow.gamepedia.com/API_GetLFGMode)\(\) - returns mode, subMode \(sometimes empty result\)

[GetLFGProposal](https://wow.gamepedia.com/API_GetLFGProposal)\(\) - Returns information about a LFD group invite.

[GetLFGProposalEncounter](https://wow.gamepedia.com/index.php?title=API_GetLFGProposalEncounter&action=edit&redlink=1)\(encounterNumber\) - returns bossName, texture, isKilled. encounterNumber is from 1 to totalEncounters from

GetLFGProposal\(\)

GetLFGProposalMember\(playerNumber\) - returns info about players \(numbers 1-5\) in the LFG proposal: isLeader, role, level, responded, accepted, name, class

[GetLFGQueueStats](https://wow.gamepedia.com/API_GetLFGQueueStats)\(\) - returns current state and wait times for being in queue

GetLFGQueuedList\(\)

[GetLFGRandomCooldownExpiration](https://wow.gamepedia.com/API_GetLFGRandomCooldownExpiration)\(\) - Returns the time at which you may once again queue for a random dungeon.

GetLFGRandomDungeonInfo\(index\) - Returns information about a random dungeon queue: id, name

GetLFGReadyCheckUpdate\(\)

GetLFGReadyCheckUpdateBattlegroundInfo\(\)

[GetLFGRoles](https://wow.gamepedia.com/API_GetLFGRoles)\(\) - returns isLeader, isTank, isHealer, isDPS - Returns the roles you signed up as, not the role you were assigned.

[GetLFGRoleShortageRewards](https://wow.gamepedia.com/API_GetLFGRoleShortageRewards)\(dungeonID, shortageSeverity\) - returns information about the LFG Call to Arms rewards

GetLFGRoleUpdate\(\) - returns roleCheckInProgress, slots, members

[GetLFGRoleUpdateBattlegroundInfo](https://wow.gamepedia.com/API_GetLFGRoleUpdateBattlegroundInfo)\(\)

GetLFGRoleUpdateMember\(\)

[GetLFGRoleUpdateSlot](https://wow.gamepedia.com/API_GetLFGRoleUpdateSlot)\(slot\) - returns dungeonType, dungeonID for a particular role slot \(integer\)

GetLFGSuspendedPlayers\(\)

[GetLFGTypes](https://wow.gamepedia.com/API_GetLFGTypes)\(\) - Returns all available LFG categories

GetNumRandomDungeons\(\) - returns the number of specific dungeons that can be queued for

GetPartyLFGBackfillInfo\(\) - Returns information about the dungeon for which you may currently recruit additional members from the LFG pool.

GetPartyLFGID\(\)

GetRandomDungeonBestChoice\(\) - Returns suggested random dungeon ID.

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

