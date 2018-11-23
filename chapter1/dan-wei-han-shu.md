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

[UnitAttackPower](https://wow.gamepedia.com/API_UnitAttackPower)\("unit"\) - 返回单位的近战攻击强度和修正值。

[UnitAttackSpeed](https://wow.gamepedia.com/API_UnitAttackSpeed)\("unit"\) - 返回每只手的单位近战攻击速度。

[UnitAura](https://wow.gamepedia.com/API_UnitAura)\("unit", index \[, filter\]\) - 返回有关单位的buff和debuff的信息。

UnitBattlePetLevel\(?\) -

[UnitBattlePetSpeciesID](https://wow.gamepedia.com/API_UnitBattlePetSpeciesID)\(?\) -

UnitBattlePetType\(?\) -

UnitBonusArmor\(?\) -

[UnitBuff](https://wow.gamepedia.com/API_UnitBuff)\("unit", index \[,raidFilter\]\) - 检索有关某个单位的buff的信息。（在2.0中更新）

[UnitCanAssist](https://wow.gamepedia.com/API_UnitCanAssist)\("unit", "otherUnit"\) - 指示第一个单位是否可以辅助第二个单位。

[UnitCanAttack](https://wow.gamepedia.com/API_UnitCanAttack)\("unit", "otherUnit"\) - 如果第一个单位可以攻击第二个单位，则返回true，否则返回false。

[UnitCanCooperate](https://wow.gamepedia.com/API_UnitCanCooperate)\("unit", "otherUnit"\) - 如果第一个单位可以与第二个单位配合，则返回true，否则返回false。

UnitCanPetBattle\(?\) -

[UnitClass](https://wow.gamepedia.com/API_UnitClass)\("unit"\) - 返回指定单位的职业（例如“战士”或“萨满”）。

UnitClassBase\(?\) -

[UnitClassification](https://wow.gamepedia.com/API_UnitClassification)\("unit"\) - 返回指定单位的分类（例如，“稀有”或“世界boss”）。

[UnitCreatureFamily](https://wow.gamepedia.com/API_UnitCreatureFamily)\("unit"\) - 返回指定单位的生物类型（例如“螃蟹”）。

[UnitCreatureType](https://wow.gamepedia.com/API_UnitCreatureType)\("unit"\) - 返回指定单位的生物的分类类型（例如，“野兽”）。

[UnitDamage](https://wow.gamepedia.com/API_UnitDamage)\("unit"\) - 返回与指定单位相关的损坏统计信息。

[UnitDebuff](https://wow.gamepedia.com/API_UnitDebuff)\("unit", index \[,raidFilter\]\) - 检索有关某个单位的debuff的信息。（在2.0中更新）

[UnitDefense](https://wow.gamepedia.com/API_UnitDefense)\("unit"\) - 返回指定单位的基本防御技能。

[UnitDetailedThreatSituation](https://wow.gamepedia.com/API_UnitDetailedThreatSituation)\("unit", "unitMob"\) - 返回有关指定单位对怪物的威胁的详细信息。 \(添加于 [Patch 3.0](https://wow.gamepedia.com/Patch_3.0)\)

[UnitDistanceSquared](https://wow.gamepedia.com/API_UnitDistanceSquared)\("unit"\) - 返回队伍中单位的平方距离

[UnitEffectiveLevel](https://wow.gamepedia.com/API_UnitEffectiveLevel)\(?\) -

[UnitExists](https://wow.gamepedia.com/API_UnitExists)\("unit"\) - 如果指定的单位存在，则返回1，否则返回nil。

[UnitFactionGroup](https://wow.gamepedia.com/API_UnitFactionGroup)\("unit"\) - 返回指定单元的阵营ID和名称。（例如“联盟”） - 返回的字符串与本地化无关（在文件路径中使用）

[UnitFullName](https://wow.gamepedia.com/API_UnitFullName)\(?\) -

UnitGetAvailableRoles\(?\) -

[UnitGetIncomingHeals](https://wow.gamepedia.com/API_UnitGetIncomingHeals)\("unit"\[, "healer"\]\) - 返回指定单位的预测治疗。

[UnitGetTotalAbsorbs](https://wow.gamepedia.com/API_UnitGetTotalAbsorbs)\("unit"\) - 返回在死亡之前该单位可以吸收的总伤害量。

[UnitGetTotalHealAbsorbs](https://wow.gamepedia.com/API_UnitGetTotalHealAbsorbs)\(?\) -

[UnitGroupRolesAssigned](https://wow.gamepedia.com/API_UnitGroupRolesAssigned)\("unit"\) - 返回通过地下城查找器形成的队伍中指定的角色。 \(添加于[Patch 3.3](https://wow.gamepedia.com/Patch_3.3)\)

[UnitGUID](https://wow.gamepedia.com/API_UnitGUID)\("unit"\) - 将GUID作为与新战斗日志使用的GUID匹配的指定单位的字符串返回。\(添加于 [Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

UnitHPPerStamina\(?\) -

[UnitHasIncomingResurrection](https://wow.gamepedia.com/API_UnitHasIncomingResurrection)\("unit"\) - 返回单位当前是否正在复活。 \([Patch 4.2.0](https://wow.gamepedia.com/Patch_4.2.0)\)

[UnitHasLFGDeserter](https://wow.gamepedia.com/API_UnitHasLFGDeserter)\("unit"\) - 返回该单元当前是否因为过早离开组而无法使用地下城查找器。（3.3.3）

[UnitHasLFGRandomCooldown](https://wow.gamepedia.com/API_UnitHasLFGRandomCooldown)\("unit"\) - 返回单位当前是否受随机地下城冷却时间的影响。（3.3.3）

UnitHasRelicSlot\("unit"\)

UnitHasVehiclePlayerFrameUI\(?\) -

[UnitHealth](https://wow.gamepedia.com/API_UnitHealth)\("unit"\) - 返回指定单位的当前血量

[UnitHealthMax](https://wow.gamepedia.com/API_UnitHealthMax)\("unit"\) - 返回指定单位最大血量

[UnitHonor](https://wow.gamepedia.com/API_UnitHonor)\("unit"\) - 返回单位在当前荣誉等级的荣誉点。

[UnitHonorLevel](https://wow.gamepedia.com/API_UnitHonorLevel)\("unit"\) - 返回单位的当前荣誉等级。

[UnitHonorMax](https://wow.gamepedia.com/API_UnitHonorMax)\("unit"\) - 返回当前荣誉等级的最大荣誉点。

UnitInBattleground\("unit"\) - 如果单位在战场，则返回单位索引，否则返回nil。

UnitInOtherParty\(?\) -

[UnitInParty](https://wow.gamepedia.com/API_UnitInParty)\("unit"\) - 如果单位是您的队友，则返回true。

UnitInPhase\(?\) -

[UnitInRaid](https://wow.gamepedia.com/API_UnitInRaid)\("unit"\) - 如果单位在raid / battleground中，则返回单位索引，否则返回nil。

UnitIsInMyGuild\("unit"\) - 返回指定单位是否与玩家角色在同一个公会中。

[UnitInRange](https://wow.gamepedia.com/API_UnitInRange)\("unit"\) -如果单位（仅限小队或团队）在典型法术范围内（如圣光闪现），则返回true。 \(added in [Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

UnitInVehicleHidesPetFrame\(?\) -

[UnitIsAFK](https://wow.gamepedia.com/API_UnitIsAFK)\("unit"\) - 仅适用于友方单位。

[UnitIsBattlePet](https://wow.gamepedia.com/API_UnitIsBattlePet)\(?\) -

UnitIsBattlePetCompanion\(?\) -

[UnitIsCharmed](https://wow.gamepedia.com/API_UnitIsCharmed)\("unit"\) - 如果指定的单位被魅惑，则返回true，否则返回false。

UnitIsConnected\("unit"\) - 如果指定的单元已连接，则返回1或npc，如果离线则返回nil，或者不是有效单位。

UnitIsControlling\(?\) -

UnitIsCorpse\("unit"\) - 如果指定的单位是尸体，则返回true，否则返回false。

[UnitIsDead](https://wow.gamepedia.com/API_UnitIsDead)\("unit"\) - 如果指定的单位死亡，则返回true，否则返回nil。

[UnitIsDeadOrGhost](https://wow.gamepedia.com/API_UnitIsDeadOrGhost)\("unit"\) - 如果指定的单位为死亡或灵魂状态，则返回true，否则返回nil。

[UnitIsDND](https://wow.gamepedia.com/API_UnitIsDND)\("unit"\) - 仅适用于友方单位。

[UnitIsEnemy](https://wow.gamepedia.com/API_UnitIsEnemy)\("unit", "otherUnit"\) - 如果指定的单位是敌人，则返回true，否则返回false。

[UnitIsFeignDeath](https://wow.gamepedia.com/API_UnitIsFeignDeath)\("unit"\) - 如果指定的单位（必须是你的小组成员）假装死亡，则返回true .--在2.1中添加

[UnitIsFriend](https://wow.gamepedia.com/API_UnitIsFriend)\("unit", "otherUnit"\) - 如果指定的单位是友方目标（同一阵营的玩家或友好的NPC），则返回true，否则返回false。

[UnitIsGhost](https://wow.gamepedia.com/API_UnitIsGhost)\("unit"\) - 如果指定的单位是灵魂状态，则返回true，否则返回false。

[UnitIsGroupAssistant](https://wow.gamepedia.com/API_UnitIsGroupAssistant)\(?\) -

UnitIsMercenary\(?\) -

UnitIsOtherPlayersBattlePet\(?\) -

UnitIsOtherPlayersPet\(?\) -

[UnitIsPVP](https://wow.gamepedia.com/API_UnitIsPVP)\("unit"\) - 如果指定的单位标记为PVP，则返回true，否则返回false。

[UnitIsPVPFreeForAll](https://wow.gamepedia.com/API_UnitIsPVPFreeForAll)\("unit"\) - 如果指定的单位标记为自由PVP，则返回true，否则返回false。

UnitIsPVPSanctuary\("unit"\) - 返回该单位是否在安全区域，因此不能被其他玩家攻击。

[UnitIsPlayer](https://wow.gamepedia.com/API_UnitIsPlayer)\("unit"\) - 如果指定的单位是玩家角色，则返回true，否则返回false。

[UnitIsPossessed](https://wow.gamepedia.com/API_UnitIsPossessed)\("unit"\) - 返回指定单位当前是否受另一个单位控制（即在施放精神控制时为“宠物”）。

UnitIsQuestBoss\("unit"\) - 如果指定的单位是击杀任务的“boss”（目标），则返回true。如果为true，则默认UI显示带有黄色“！”的屏蔽。在单位的单位框架上。

UnitIsRaidOfficer\("unit"\) - 返回指定的单位是否是raid中的管理。

[UnitIsSameServer](https://wow.gamepedia.com/API_UnitIsSameServer)\("unit"\) - 返回指定的单位是否与玩家角色在同一服务器上。

REMOVED [UnitIsTapped](https://wow.gamepedia.com/API_UnitIsTapped)\("unit"\) - 如果指定的单位被点击则返回true，否则返回false。

REMOVED [UnitIsTappedByPlayer](https://wow.gamepedia.com/API_UnitIsTappedByPlayer)\("unit"\) - 如果玩家自己点击指定的单位，则返回true，否则返回false。

REMOVED [UnitIsTappedByAllThreatList](https://wow.gamepedia.com/API_UnitIsTappedByAllThreatList)\("unit"\) - 返回指定单位是否为社区怪物，即与其进行战斗的所有玩家是否将获得杀戮（任务）信用。

UnitIsTapDenied\(?\) -

[UnitIsTrivial](https://wow.gamepedia.com/API_UnitIsTrivial)\("unit"\) - 如果指定的单位是Trivial，则返回true（Trivial表示单位对玩家是“灰色”。否则为false。\)

UnitIsUnconscious\(?\) -

[UnitIsUnit](https://wow.gamepedia.com/API_UnitIsUnit)\("unit", "otherUnit"\) - 确定两个单位是否是同一个单位。

[UnitIsVisible](https://wow.gamepedia.com/API_UnitIsVisible)\("unit"\) - 1如果可见，否则为零

UnitIsWildBattlePet\(?\) -

UnitLeadsAnyGroup\(?\) -

[UnitLevel](https://wow.gamepedia.com/API_UnitLevel)\("unit"\) - 返回单位的级别。

[UnitName](https://wow.gamepedia.com/API_UnitName)\("unit"\) - 返回单位的名称（和服务器名称）。

UnitNumPowerBarTimers\(?\) -

[UnitOnTaxi](https://wow.gamepedia.com/API_UnitOnTaxi)\("unit"\) - 如果单位在飞行点状态，则返回1。

[UnitPVPName](https://wow.gamepedia.com/API_UnitPVPName)\("unit"\) - 返回具有PvP等级前缀的单位名称（例如，“下士联盟”）。

[UnitPlayerControlled](https://wow.gamepedia.com/API_UnitPlayerControlled)\("unit"\) - 如果指定的单位由玩家控制，则返回true，否则返回false。

[UnitPlayerOrPetInParty](https://wow.gamepedia.com/API_UnitPlayerOrPetInParty)\("unit"\) - 如果指定的单位/宠物是玩家小队的成员，则返回1，否则返回nil（对于“玩家”和“宠物”返回nil） - 在1.12中添加

[UnitPlayerOrPetInRaid](https://wow.gamepedia.com/API_UnitPlayerOrPetInRaid)\("unit"\) - 如果指定的单位/宠物是玩家团队的成员，则返回1，否则返回nil（对于“玩家”和“宠物”返回nil） - 在1.12中添加

[UnitPower](https://wow.gamepedia.com/API_UnitPower)\("unit"\[,type\]\) - 返回指定单位的当前能量（从WoW 3.0.2开始替换[UnitMana](https://wow.gamepedia.com/API_UnitMana)\(\)）

UnitPowerBarTimerInfo\(?\) -

[UnitPowerMax](https://wow.gamepedia.com/API_UnitPowerMax)\("unit"\[,type\]\) - 返回指定单位的最大能量（从WoW 3.0.2开始替换[UnitManaMax](https://wow.gamepedia.com/API_UnitManaMax)\(\)）

[UnitPowerType](https://wow.gamepedia.com/API_UnitPowerType)\("unit"\) - 返回与指定单位的能量类型（例如，法力，愤怒或能量）对应的数字。

UnitPrestige\(?\) -

[UnitRace](https://wow.gamepedia.com/API_UnitRace)\("unit"\) - 返回指定单位的种族名称（例如，“人”或“巨魔”）。

[UnitRangedAttack](https://wow.gamepedia.com/API_UnitRangedAttack)\("unit"\) - 返回单位的远程攻击数值。

[UnitRangedAttackPower](https://wow.gamepedia.com/API_UnitRangedAttackPower)\("unit"\) - 返回单位的远程攻击强度。

[UnitRangedDamage](https://wow.gamepedia.com/API_UnitRangedDamage)\("unit"\) - 返回远程攻击速度和单位的伤害。

[UnitRealmRelationship](https://wow.gamepedia.com/API_UnitRealmRelationship)\(?\) -

[UnitReaction](https://wow.gamepedia.com/API_UnitReaction)\("unit", "otherUnit"\) - 返回对应于第一单位朝向第二单位的反应（仇恨，中立的或友好的）的数字。

[UnitResistance](https://wow.gamepedia.com/API_UnitResistance)\("unit", "resistanceIndex"\) - 返回与指定单位和伤害类型相关的抗性统计数据。

[UnitSelectionColor](https://wow.gamepedia.com/API_UnitSelectionColor)\("unit"\) - 返回单位名称颜色的RGBA值。

[UnitSetRole](https://wow.gamepedia.com/API_UnitSetRole)\(?\) -

[UnitSex](https://wow.gamepedia.com/API_UnitSex)\("unit"\) - 返回指示指定单位性别的代码（如果已知）。（1 =未知，2 =男性，3 =女性）←在1.11中改变了！

UnitShouldDisplayName\(?\) -

[UnitSpellHaste](https://wow.gamepedia.com/API_UnitSpellHaste)\("unit" or "name"\) - 返回单位的当前法术急速百分比。

[UnitStagger](https://wow.gamepedia.com/API_UnitStagger)\(?\) -

[UnitStat](https://wow.gamepedia.com/API_UnitStat)\("unit", statIndex\) - 返回与指定单位和基本属性（例如，力量或智力）相关的统计数据。

UnitThreatPercentageOfLead\(?\) -

[UnitThreatSituation](https://wow.gamepedia.com/API_UnitThreatSituation)\("unit", "mobUnit"\) - 返回指定单位对怪物的威胁状态。（在[补丁3.0](https://wow.gamepedia.com/Patch_3.0)中添加）

[UnitUsingVehicle](https://wow.gamepedia.com/API_UnitUsingVehicle)\("unit"\) - 返回指定单位当前是否正在使用载具（包括在座位之间转换）。

[UnitXP](https://wow.gamepedia.com/API_UnitXP)\("unit"\) - 返回指定单位在当前级别中的经验值数。（仅适用于您的角色）

[UnitXPMax](https://wow.gamepedia.com/API_UnitXPMax)\("unit"\) - 返回指定单位达到下一级别所需的经验值数。（仅适用于您的角色）

