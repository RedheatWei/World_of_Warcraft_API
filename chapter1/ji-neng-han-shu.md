### 技能函数

PROTECTED [CastShapeshiftForm](https://wow.gamepedia.com/API_CastShapeshiftForm)\(index\)

PROTECTED [CastSpell](https://wow.gamepedia.com/API_CastSpell)\(spellIndex, "bookType"\) - 在指定的技能书槽中释放技能。

PROTECTED [CastSpellByName](https://wow.gamepedia.com/API_CastSpellByName)\("name"\[, "target"\]\) - 按显示名称施放指定的技能。

[GetMultiCastTotemSpells](https://wow.gamepedia.com/API_GetMultiCastTotemSpells)\(totemslot\) - 返回适用于指定图腾插槽（1-4）的spellID列表（在3.2中添加）

[GetNumShapeshiftForms](https://wow.gamepedia.com/API_GetNumShapeshiftForms)\(\)

[GetNumSpellTabs](https://wow.gamepedia.com/API_GetNumSpellTabs)\(\) - 返回用户技能书中的标签总数。

[GetQuestLogRewardSpell](https://wow.gamepedia.com/API_GetQuestLogRewardSpell) - ?.

[GetRewardSpell](https://wow.gamepedia.com/API_GetRewardSpell) - ?.

[GetShapeshiftForm](https://wow.gamepedia.com/API_GetShapeshiftForm)\(unknown\) - 返回当前形式/立场的从零开始的索引

[GetShapeshiftFormCooldown](https://wow.gamepedia.com/API_GetShapeshiftFormCooldown)\(index\)

[GetShapeshiftFormID](https://wow.gamepedia.com/API_GetShapeshiftFormID)\(\) - 将当前的变身形式作为常量返回。如果玩家没有变形，则返回零。

[GetShapeshiftFormInfo](https://wow.gamepedia.com/API_GetShapeshiftFormInfo)\(index\) - 检索有关可用ShapeshiftForm或姿态的信息。

[GetSpellAutocast](https://wow.gamepedia.com/API_GetSpellAutocast)\("spellName" \| spellId, bookType\) - 检查指定的技能是否自动释放。

[GetSpellBookItemInfo](https://wow.gamepedia.com/API_GetSpellBookItemInfo)\(spellID, "bookType"\) - 返回玩家技能书中技能的类型和技能ID。

[GetSpellBookItemName](https://wow.gamepedia.com/API_GetSpellBookItemName)\(spellID, "bookType"\) - 返回玩家技能书中技能的名称和技能等级。

[GetSpellBookItemTexture](https://wow.gamepedia.com/API_GetSpellBookItemTexture)\(spellID, "bookType"\) - 返回玩家技能书中技能的图标fileId。

GetSpellBookItemTextureFileName\(spellID, "bookType"\) - 返回玩家技能书中技能的图标纹理。

[GetSpellCharges](https://wow.gamepedia.com/API_GetSpellCharges)\(spellId \| spellName\) - 返回有关能量累积玩家能力的消耗的信息。

[GetSpellCooldown](https://wow.gamepedia.com/API_GetSpellCooldown)\(spellName \| spellID, "bookType"\) - 检索特定技能的冷却时间数据。

GetSpellDescription\(spellId\) - 返回技能描述.

[GetSpellInfo](https://wow.gamepedia.com/API_GetSpellInfo)\(spellId \| spellName \| spellLink\) - 返回技能的名称，等级，iconFileDataID，施法时间，最小和最大范围以及spellID。

[GetSpellLink](https://wow.gamepedia.com/API_GetSpellLink)\(spellName, spellRank\) - 返回技能连接. \(2.4\)

[GetSpellPowerCost](https://wow.gamepedia.com/API_GetSpellPowerCost)\(spellId \| spellName\) - 返回有关技能资源成本的信息。

[GetSpellTabInfo](https://wow.gamepedia.com/API_GetSpellTabInfo)\(spellbookTabNum\) - 返回有关指定的技能书选项卡的信息。

[GetSpellTexture](https://wow.gamepedia.com/API_GetSpellTexture)\(spellId \| spellName\) - 返回用于该技能图标的fileId。

[GetSpellTextureFileName](https://wow.gamepedia.com/API_GetSpellTextureFileName)\(spellId \| spellName\) - 返回用于该技能图标的纹理。

[GetTotemInfo](https://wow.gamepedia.com/API_GetTotemInfo)\(slot\) - 返回有关图腾的信息。

[IsAttackSpell](https://wow.gamepedia.com/API_IsAttackSpell)\(spell\) - 如果该技能是“攻击”技能，则返回1。

IsAutoRepeatSpell\(spell\) -

[IsPassiveSpell](https://wow.gamepedia.com/API_IsPassiveSpell)\(spellID, "bookType"\) - 返回法术书中的图标是否为被动技能。以前是IsSpellPassive\(\)。

[IsSpellInRange](https://wow.gamepedia.com/API_IsSpellInRange)\("spellName", \[unit\]\) - nil表示无效目标，0表示超出范围，1表示范围。

[IsSpellKnown](https://wow.gamepedia.com/API_IsSpellKnown)\(spellID, isPetSpell\) - 返回玩家（或宠物）是否学会给定的技能。

[IsSpellOverlayed](https://wow.gamepedia.com/API_IsSpellOverlayed)\(spellID\) - 返回该技能当前是否受到proc（发光突出显示）的影响。

[IsUsableSpell](https://wow.gamepedia.com/API_IsUsableSpell)\("spellName" \| spellID \| spellIndex, "bookType"\) - 确定玩家角色是否可以使用该技能。

[PickupSpell](https://wow.gamepedia.com/API_PickupSpell)\("spellName" \| spellID, "bookType"\) - 在光标上加载一个操作按钮，将其放入快速栏插槽中。

UI [QueryCastSequence](https://wow.gamepedia.com/API_QueryCastSequence)\("sequence"\) - 返回执行强制转换序列时将使用的技能/项目的索引，项目，法术。

PROTECTED [SetMultiCastSpell](https://wow.gamepedia.com/API_SetMultiCastSpell)\(actionID,spellID\) - 将spellID分配给多播（图腾栏）actionID。（在3.2中添加）

[SpellCanTargetUnit](https://wow.gamepedia.com/API_SpellCanTargetUnit)\("unit"\) - 如果等待目标选择的技能可以在指定单位上施放，则返回true。

SpellHasRange\(spell\) - 如果指定的技能具有远程效果（即需要目标），则返回true。

[SpellIsTargeting](https://wow.gamepedia.com/API_SpellIsTargeting)\(\) - 如果施放了一个技能并且正在等待目标选择，则返回true。

PROTECTED [SpellStopCasting](https://wow.gamepedia.com/API_SpellStopCasting)\(\) - 停止当前的施法。

PROTECTED [SpellStopTargeting](https://wow.gamepedia.com/API_SpellStopTargeting)\(\) - 取消等待目标选择的技能。

PROTECTED [SpellTargetUnit](https://wow.gamepedia.com/API_SpellTargetUnit)\("unit"\) - 在指定单位上施放等待目标选择的技能。

PROTECTED ToggleSpellAutocast\("spellName" \| spellId, bookType\) - 切换指定的技能是否应该自动释放。这用于一些宠物能力。

[UnitCastingInfo](https://wow.gamepedia.com/API_UnitCastingInfo)\("unit"\) - 返回有关指定单位当前正在施放的技能的信息。

[UnitChannelInfo](https://wow.gamepedia.com/API_UnitChannelInfo)\("unit"\) - 返回有关当前由指定单位引导的技能的信息。

