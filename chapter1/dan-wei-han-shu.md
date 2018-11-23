### 单位函数

###### 这些是作用于一个或多个单位的功能。单位由[UnitIds](https://wow.gamepedia.com/UnitId)标识。

PROTECTED [AssistUnit](https://wow.gamepedia.com/API_AssistUnit)\("unit"\) - 指示角色协助指定的单位。

[CheckInteractDistance](https://wow.gamepedia.com/API_CheckInteractDistance)\("unit",distIndex\)

PROTECTED [ClearFocus](https://wow.gamepedia.com/API_ClearFocus)\(\) - 删除您可能设置的任何焦点。

[DropItemOnUnit](https://wow.gamepedia.com/API_DropItemOnUnit)\("unit"\) - 将项目从光标拖放到单元上。

[FillLocalizedClassList](https://wow.gamepedia.com/API_FillLocalizedClassList)\(classTable\[, isFemale\]\) - 使用本地化的职业名填充表。

PROTECTED [FocusUnit](https://wow.gamepedia.com/API_FocusUnit)\("unit"\) - 设置焦点单位。- 于Patch 2.0保护！

[FollowUnit](https://wow.gamepedia.com/API_FollowUnit)\("unit"\) - 跟随指定UnitID的盟友

[GetClassColor](https://wow.gamepedia.com/API_GetClassColor)\(englishClass\) - 返回有关职业颜色的信息

[GetPlayerInfoByGUID](https://wow.gamepedia.com/API_GetPlayerInfoByGUID)\("guid"\) - 在3.2中添加，返回关于guid的种族，职业，性别（客户端必须看到guid）

[GetThreatStatusColor](https://wow.gamepedia.com/API_GetThreatStatusColor)\(status\) - 返回给定UnitThreatSituation返回值的RGB值。

UI [GetUnitName](https://wow.gamepedia.com/API_GetUnitName)\("unit", showServerName\) - 如果适用，返回包含单位名称和服务器名称的字符串。

GetUnitPitch\("unit"\) - 返回单位的移动高度?（在3.0.2中添加）

[GetUnitSpeed](https://wow.gamepedia.com/API_GetUnitSpeed)\("unit"\) - 返回单位的移动速度。（在3.0.2中添加）

[InviteUnit](https://wow.gamepedia.com/API_InviteUnit)\("name" or "unit"\) - 邀请指定的玩家加入您当前所在的队伍。（在2.0中添加）

[IsUnitOnQuest](https://wow.gamepedia.com/API_IsUnitOnQuest)\(questIndex, "unit"\) - 确定指定的单位是否在给定的任务中。

SetPortraitTexture\(texture,"unit"\) - 使用指定单位的肖像绘制质地对象。

[SetPortraitToTexture](https://wow.gamepedia.com/API_SetPortraitToTexture)\(texture or "texture", "texturePath"\) - 设置要从应用圆形不透明蒙版的文件显示的纹理，使其看起来像人像。

[SpellCanTargetUnit](https://wow.gamepedia.com/API_SpellCanTargetUnit)\("unit"\) - 如果等待目标选择的技能可以在指定单位上施放，则返回true。

PROTECTED [SpellTargetUnit](https://wow.gamepedia.com/API_SpellTargetUnit)\("unit"\) - 在指定单位上施放等待目标选择的法术。

PROTECTED [TargetUnit](https://wow.gamepedia.com/API_TargetUnit)\("unit" or "name" \[, exactMatch\]\) - 选择指定的单位作为当前目标。- 于Patch 2.0保护！

[UnitAffectingCombat](https://wow.gamepedia.com/API_UnitAffectingCombat)\("unit"\) - 确定该单位是在战斗中还是具有仇恨。（如果为“false”则返回nil，如果为“true”则返回1）

UnitAlternatePowerCounterInfo\(?\) -

UnitAlternatePowerInfo\(?\) -

UnitAlternatePowerTextureInfo\(?\) -

[UnitArmor](https://wow.gamepedia.com/API_UnitArmor)\("unit"\) - 返回与指定单位相关的装甲统计数据。

[UnitAttackBothHands](https://wow.gamepedia.com/API_UnitAttackBothHands)\("unit"\) - 返回有关单位近战攻击的信息

[UnitAttackPower](https://wow.gamepedia.com/API_UnitAttackPower)\("unit"\) - Returns the unit's melee attack power and modifiers.

[UnitAttackSpeed](https://wow.gamepedia.com/API_UnitAttackSpeed)\("unit"\) - Returns the unit's melee attack speed for each hand.

[UnitAura](https://wow.gamepedia.com/API_UnitAura)\("unit", index \[, filter\]\) - Returns info about buffs and debuffs of a unit.

UnitBattlePetLevel\(?\) -

[UnitBattlePetSpeciesID](https://wow.gamepedia.com/API_UnitBattlePetSpeciesID)\(?\) -

UnitBattlePetType\(?\) -

UnitBonusArmor\(?\) -

[UnitBuff](https://wow.gamepedia.com/API_UnitBuff)\("unit", index \[,raidFilter\]\) - Retrieves info about a buff of a certain unit. \(Updated in 2.0\)

[UnitCanAssist](https://wow.gamepedia.com/API_UnitCanAssist)\("unit", "otherUnit"\) - Indicates whether the first unit can assist the second unit.

[UnitCanAttack](https://wow.gamepedia.com/API_UnitCanAttack)\("unit", "otherUnit"\) - Returns true if the first unit can attack the second, false otherwise.

[UnitCanCooperate](https://wow.gamepedia.com/API_UnitCanCooperate)\("unit", "otherUnit"\) - Returns true if the first unit can cooperate with the second, false otherwise.

UnitCanPetBattle\(?\) -

[UnitClass](https://wow.gamepedia.com/API_UnitClass)\("unit"\) - Returns the class name of the specified unit \(e.g., "Warrior" or "Shaman"\).

UnitClassBase\(?\) -

[UnitClassification](https://wow.gamepedia.com/API_UnitClassification)\("unit"\) - Returns the classification of the specified unit \(e.g., "elite" or "worldboss"\).

[UnitCreatureFamily](https://wow.gamepedia.com/API_UnitCreatureFamily)\("unit"\) - Returns the type of creature of the specified unit \(e.g., "Crab"\).

[UnitCreatureType](https://wow.gamepedia.com/API_UnitCreatureType)\("unit"\) - Returns the classification type of creature of the specified unit \(e.g., "Beast"\).

[UnitDamage](https://wow.gamepedia.com/API_UnitDamage)\("unit"\) - Returns the damage statistics relevant to the specified unit.

[UnitDebuff](https://wow.gamepedia.com/API_UnitDebuff)\("unit", index \[,raidFilter\]\) - Retrieves info about a debuff of a certain unit. \(Updated in 2.0\)

[UnitDefense](https://wow.gamepedia.com/API_UnitDefense)\("unit"\) - Returns the base defense skill of the specified unit.

[UnitDetailedThreatSituation](https://wow.gamepedia.com/API_UnitDetailedThreatSituation)\("unit", "unitMob"\) - Returns detailed information about the specified unit's threat on a mob. \(added in [Patch 3.0](https://wow.gamepedia.com/Patch_3.0)\)

[UnitDistanceSquared](https://wow.gamepedia.com/API_UnitDistanceSquared)\("unit"\) - Returns the squared distance to a unit in your group

[UnitEffectiveLevel](https://wow.gamepedia.com/API_UnitEffectiveLevel)\(?\) -

[UnitExists](https://wow.gamepedia.com/API_UnitExists)\("unit"\) - Returns 1 if the specified unit exists, nil otherwise.

[UnitFactionGroup](https://wow.gamepedia.com/API_UnitFactionGroup)\("unit"\) - Returns the faction group id and name of the specified unit. \(eg. "Alliance"\) - string returned is localization-independent \(used in filepath\)

[UnitFullName](https://wow.gamepedia.com/API_UnitFullName)\(?\) -

UnitGetAvailableRoles\(?\) -

[UnitGetIncomingHeals](https://wow.gamepedia.com/API_UnitGetIncomingHeals)\("unit"\[, "healer"\]\) - Returns the predicted heals cast on the specified unit.

[UnitGetTotalAbsorbs](https://wow.gamepedia.com/API_UnitGetTotalAbsorbs)\("unit"\) - Returns the total amount of damage the unit can absorb before losing health.

[UnitGetTotalHealAbsorbs](https://wow.gamepedia.com/API_UnitGetTotalHealAbsorbs)\(?\) -

[UnitGroupRolesAssigned](https://wow.gamepedia.com/API_UnitGroupRolesAssigned)\("unit"\) - Returns the assigned role in a group formed via the Dungeon Finder Tool. \(added in[Patch 3.3](https://wow.gamepedia.com/Patch_3.3)\)

[UnitGUID](https://wow.gamepedia.com/API_UnitGUID)\("unit"\) - Returns the GUID as a string for the specified unit matching the GUIDs used by the new combat logs. \(added in [Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

UnitHPPerStamina\(?\) -

[UnitHasIncomingResurrection](https://wow.gamepedia.com/API_UnitHasIncomingResurrection)\("unit"\) - Returns whether the unit is currently being resurrected. \([Patch 4.2.0](https://wow.gamepedia.com/Patch_4.2.0)\)

[UnitHasLFGDeserter](https://wow.gamepedia.com/API_UnitHasLFGDeserter)\("unit"\) - Returns whether the unit is currently unable to use the dungeon finder due to leaving a group prematurely. \(3.3.3\)

[UnitHasLFGRandomCooldown](https://wow.gamepedia.com/API_UnitHasLFGRandomCooldown)\("unit"\) - Returns whether the unit is currently under the effects of the random dungeon cooldown. \(3.3.3\)

UnitHasRelicSlot\("unit"\)

UnitHasVehiclePlayerFrameUI\(?\) -

[UnitHealth](https://wow.gamepedia.com/API_UnitHealth)\("unit"\) - Returns the current health, in points, of the specified unit.

[UnitHealthMax](https://wow.gamepedia.com/API_UnitHealthMax)\("unit"\) - Returns the maximum health, in points, of the specified unit.

[UnitHonor](https://wow.gamepedia.com/API_UnitHonor)\("unit"\) - Returns the amount of honor the unit has for the current rank.

[UnitHonorLevel](https://wow.gamepedia.com/API_UnitHonorLevel)\("unit"\) - Returns the current honor rank for the unit.

[UnitHonorMax](https://wow.gamepedia.com/API_UnitHonorMax)\("unit"\) - Returns the maximum amount of honor for the current rank.

UnitInBattleground\("unit"\) - Returns the unit index if the unit is in your battleground, nil otherwise.

UnitInOtherParty\(?\) -

[UnitInParty](https://wow.gamepedia.com/API_UnitInParty)\("unit"\) - Returns true if the unit is a member of your party.

UnitInPhase\(?\) -

[UnitInRaid](https://wow.gamepedia.com/API_UnitInRaid)\("unit"\) - Returns the unit index if the unit is in your raid/battlegroud, nil otherwise.

UnitIsInMyGuild\("unit"\) - Returns whether the specified unit is in the same guild as the player's character.

[UnitInRange](https://wow.gamepedia.com/API_UnitInRange)\("unit"\) - Returns true if the unit \(party or raid only\) is in range of a typical spell such as flash heal. \(added in [Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

UnitInVehicleHidesPetFrame\(?\) -

[UnitIsAFK](https://wow.gamepedia.com/API_UnitIsAFK)\("unit"\) - Only works for friendly units.

[UnitIsBattlePet](https://wow.gamepedia.com/API_UnitIsBattlePet)\(?\) -

UnitIsBattlePetCompanion\(?\) -

[UnitIsCharmed](https://wow.gamepedia.com/API_UnitIsCharmed)\("unit"\) - Returns true if the specified unit is charmed, false otherwise.

UnitIsConnected\("unit"\) - Returns 1 if the specified unit is connected or npc, nil if offline or not a valid unit.

UnitIsControlling\(?\) -

UnitIsCorpse\("unit"\) - Returns true if the specified unit is a corpse, false otherwise.

[UnitIsDead](https://wow.gamepedia.com/API_UnitIsDead)\("unit"\) - Returns true if the specified unit is dead, nil otherwise.

[UnitIsDeadOrGhost](https://wow.gamepedia.com/API_UnitIsDeadOrGhost)\("unit"\) - Returns true if the specified unit is dead or a ghost, nil otherwise.

[UnitIsDND](https://wow.gamepedia.com/API_UnitIsDND)\("unit"\) - Only works for friendly units.

[UnitIsEnemy](https://wow.gamepedia.com/API_UnitIsEnemy)\("unit", "otherUnit"\) - Returns true if the specified units are enemies, false otherwise.

[UnitIsFeignDeath](https://wow.gamepedia.com/API_UnitIsFeignDeath)\("unit"\) - Returns true if the specified unit \(must be a member of your group\) is feigning death. -- Added in 2.1

[UnitIsFriend](https://wow.gamepedia.com/API_UnitIsFriend)\("unit", "otherUnit"\) - Returns true if the specified units are friends \(PC of same faction or friendly NPC\), false otherwise.

[UnitIsGhost](https://wow.gamepedia.com/API_UnitIsGhost)\("unit"\) - Returns true if the specified unit is a ghost, false otherwise.

[UnitIsGroupAssistant](https://wow.gamepedia.com/API_UnitIsGroupAssistant)\(?\) -

UnitIsMercenary\(?\) -

UnitIsOtherPlayersBattlePet\(?\) -

UnitIsOtherPlayersPet\(?\) -

[UnitIsPVP](https://wow.gamepedia.com/API_UnitIsPVP)\("unit"\) - Returns true if the specified unit is flagged for PVP, false otherwise.

[UnitIsPVPFreeForAll](https://wow.gamepedia.com/API_UnitIsPVPFreeForAll)\("unit"\) - Returns true if the specified unit is flagged for free-for-all PVP, false otherwise.

UnitIsPVPSanctuary\("unit"\) - Returns whether the unit is in a PvP sanctuary, and therefore cannot be attacked by other players.

[UnitIsPlayer](https://wow.gamepedia.com/API_UnitIsPlayer)\("unit"\) - Returns true if the specified unit is a player character, false otherwise.

[UnitIsPossessed](https://wow.gamepedia.com/API_UnitIsPossessed)\("unit"\) - Returns whether the specified unit is currently under control of another \(i.e. "pet" when casting Mind Control\).

UnitIsQuestBoss\("unit"\) - Returns true if the specified unit is the "boss" \(objective\) of a kill quest. If true, then the default UI displays a shield with a yellow "!" on it on the unit's unitframe.

UnitIsRaidOfficer\("unit"\) - Returns whether the specified unit is an officer in your raid.

[UnitIsSameServer](https://wow.gamepedia.com/API_UnitIsSameServer)\("unit"\) - Returns whether the specified unit is from the same server as the player's character.

REMOVED [UnitIsTapped](https://wow.gamepedia.com/API_UnitIsTapped)\("unit"\) - Returns true if the specified unit is tapped, false otherwise.

REMOVED [UnitIsTappedByPlayer](https://wow.gamepedia.com/API_UnitIsTappedByPlayer)\("unit"\) - Returns true if the specified unit is tapped by the player himself, otherwise false.

REMOVED [UnitIsTappedByAllThreatList](https://wow.gamepedia.com/API_UnitIsTappedByAllThreatList)\("unit"\) - Returns whether the specified unit is a community monster, i.e. whether all players engaged in combat with it will receive kill \(quest\) credit.

UnitIsTapDenied\(?\) -

[UnitIsTrivial](https://wow.gamepedia.com/API_UnitIsTrivial)\("unit"\) - Returns true if the specified unit is trivial \(Trivial means the unit is "grey" to the player. false otherwise.

UnitIsUnconscious\(?\) -

[UnitIsUnit](https://wow.gamepedia.com/API_UnitIsUnit)\("unit", "otherUnit"\) - Determine if two units are the same unit.

[UnitIsVisible](https://wow.gamepedia.com/API_UnitIsVisible)\("unit"\) - 1 if visible, nil if not

UnitIsWildBattlePet\(?\) -

UnitLeadsAnyGroup\(?\) -

[UnitLevel](https://wow.gamepedia.com/API_UnitLevel)\("unit"\) - Returns the level of a unit.

[UnitName](https://wow.gamepedia.com/API_UnitName)\("unit"\) - Returns the name \(and realm name\) of a unit.

UnitNumPowerBarTimers\(?\) -

[UnitOnTaxi](https://wow.gamepedia.com/API_UnitOnTaxi)\("unit"\) - Returns 1 if unit is on a taxi.

[UnitPVPName](https://wow.gamepedia.com/API_UnitPVPName)\("unit"\) - Returns unit's name with PvP rank prefix \(e.g., "Corporal Allianceguy"\).

[UnitPlayerControlled](https://wow.gamepedia.com/API_UnitPlayerControlled)\("unit"\) - Returns true if the specified unit is controlled by a player, false otherwise.

[UnitPlayerOrPetInParty](https://wow.gamepedia.com/API_UnitPlayerOrPetInParty)\("unit"\) - Returns 1 if the specified unit/pet is a member of the player's party, nil otherwise \(returns nil for "player" and "pet"\) - Added in 1.12

[UnitPlayerOrPetInRaid](https://wow.gamepedia.com/API_UnitPlayerOrPetInRaid)\("unit"\) - Returns 1 if the specified unit/pet is a member of the player's raid, nil otherwise \(returns nil for "player" and "pet"\) - Added in 1.12

[UnitPower](https://wow.gamepedia.com/API_UnitPower)\("unit"\[,type\]\) - Returns current power of the specified unit \(Replaces

[UnitMana](https://wow.gamepedia.com/API_UnitMana)\(\) as of WoW 3.0.2\)

UnitPowerBarTimerInfo\(?\) -

[UnitPowerMax](https://wow.gamepedia.com/API_UnitPowerMax)\("unit"\[,type\]\) - Returns max power of the specified unit \(Replaces [UnitManaMax](https://wow.gamepedia.com/API_UnitManaMax)\(\) as of WoW 3.0.2\)

[UnitPowerType](https://wow.gamepedia.com/API_UnitPowerType)\("unit"\) - Returns a number corresponding to the power type \(e.g., mana, rage or energy\) of the specified unit.

UnitPrestige\(?\) -

[UnitRace](https://wow.gamepedia.com/API_UnitRace)\("unit"\) - Returns the race name of the specified unit \(e.g., "Human" or "Troll"\).

[UnitRangedAttack](https://wow.gamepedia.com/API_UnitRangedAttack)\("unit"\) - Returns the ranged attack number of the unit.

[UnitRangedAttackPower](https://wow.gamepedia.com/API_UnitRangedAttackPower)\("unit"\) - Returns the ranged attack power of the unit.

[UnitRangedDamage](https://wow.gamepedia.com/API_UnitRangedDamage)\("unit"\) - Returns the ranged attack speed and damage of the unit.

[UnitRealmRelationship](https://wow.gamepedia.com/API_UnitRealmRelationship)\(?\) -

[UnitReaction](https://wow.gamepedia.com/API_UnitReaction)\("unit", "otherUnit"\) - Returns a number corresponding to the reaction \(aggressive, neutral or friendly\) of the first unit towards the second unit.

[UnitResistance](https://wow.gamepedia.com/API_UnitResistance)\("unit", "resistanceIndex"\) - Returns the resistance statistics relevant to the specified unit and resistance type.

[UnitSelectionColor](https://wow.gamepedia.com/API_UnitSelectionColor)\("unit"\) - Returns RGBA values for the color of a unit's name.

[UnitSetRole](https://wow.gamepedia.com/API_UnitSetRole)\(?\) -

[UnitSex](https://wow.gamepedia.com/API_UnitSex)\("unit"\) - Returns a code indicating the gender of the specified unit, if known. \(1=unknown, 2=male, 3=female\) ← changed in 1.11!

UnitShouldDisplayName\(?\) -

[UnitSpellHaste](https://wow.gamepedia.com/API_UnitSpellHaste)\("unit" or "name"\) - Returns the current spell haste percentage for a unit.

[UnitStagger](https://wow.gamepedia.com/API_UnitStagger)\(?\) -

[UnitStat](https://wow.gamepedia.com/API_UnitStat)\("unit", statIndex\) - Returns the statistics relevant to the specified unit and basic attribute \(e.g., strength or intellect\).

UnitThreatPercentageOfLead\(?\) -

[UnitThreatSituation](https://wow.gamepedia.com/API_UnitThreatSituation)\("unit", "mobUnit"\) - Returns the specified unit's threat status on a mob. \(added in [Patch 3.0](https://wow.gamepedia.com/Patch_3.0)\)

[UnitUsingVehicle](https://wow.gamepedia.com/API_UnitUsingVehicle)\("unit"\) - Returns whether the specified unit is currently using a vehicle \(including transitioning between seats\).

[UnitXP](https://wow.gamepedia.com/API_UnitXP)\("unit"\) - Returns the number of experience points the specified unit has in their current level. \(only works on your player\)

[UnitXPMax](https://wow.gamepedia.com/API_UnitXPMax)\("unit"\) - Returns the number of experience points the specified unit needs to reach their next level. \(only works on your player\)

