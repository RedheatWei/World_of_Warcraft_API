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

[GetSpellBookItemName](https://wow.gamepedia.com/API_GetSpellBookItemName)\(spellID, "bookType"\) - 返回玩家法术书中法术的法术名称和法术等级。

[GetSpellBookItemTexture](https://wow.gamepedia.com/API_GetSpellBookItemTexture)\(spellID, "bookType"\) - 返回玩家法术书中法术的法术图标fileId。

GetSpellBookItemTextureFileName\(spellID, "bookType"\) - 返回玩家法术书中法术的法术图标纹理。

[GetSpellCharges](https://wow.gamepedia.com/API_GetSpellCharges)\(spellId \| spellName\) - 返回有关能量累积玩家能力的消耗的信息。

[GetSpellCooldown](https://wow.gamepedia.com/API_GetSpellCooldown)\(spellName \| spellID, "bookType"\) - Retrieves data on the cooldown of a specific spell.

GetSpellDescription\(spellId\) - Returns the spell description.

[GetSpellInfo](https://wow.gamepedia.com/API_GetSpellInfo)\(spellId \| spellName \| spellLink\) - Returns the spell's name, rank, iconFileDataID, cast time, min and max ranges, and spellID.

[GetSpellLink](https://wow.gamepedia.com/API_GetSpellLink)\(spellName, spellRank\) - Returns the spell's link. \(2.4\)

[GetSpellPowerCost](https://wow.gamepedia.com/API_GetSpellPowerCost)\(spellId \| spellName\) - Returns information about a spell's resource cost.

[GetSpellTabInfo](https://wow.gamepedia.com/API_GetSpellTabInfo)\(spellbookTabNum\) - Returns information about the specified spellbook tab.

[GetSpellTexture](https://wow.gamepedia.com/API_GetSpellTexture)\(spellId \| spellName\) - Returns the fileId used for the spell's icon.

[GetSpellTextureFileName](https://wow.gamepedia.com/API_GetSpellTextureFileName)\(spellId \| spellName\) - Returns the texture used for the spell's icon.

[GetTotemInfo](https://wow.gamepedia.com/API_GetTotemInfo)\(slot\) - Returns information about a totem.

[IsAttackSpell](https://wow.gamepedia.com/API_IsAttackSpell)\(spell\) - Returns 1 if the spell is the "Attack" spell.

IsAutoRepeatSpell\(spell\) -

[IsPassiveSpell](https://wow.gamepedia.com/API_IsPassiveSpell)\(spellID, "bookType"\) - Returns whether the icon in your spellbook is a Passive ability. Formerly IsSpellPassive\(spell\).

[IsSpellInRange](https://wow.gamepedia.com/API_IsSpellInRange)\("spellName", \[unit\]\) - Is nil for no valid target, 0 for out of range, 1 for in range.

[IsSpellKnown](https://wow.gamepedia.com/API_IsSpellKnown)\(spellID, isPetSpell\) - Returns whether the player \(or pet\) knows the given spell.

[IsSpellOverlayed](https://wow.gamepedia.com/API_IsSpellOverlayed)\(spellID\) - Returns whether the spell is currently affected by a proc \(glow highlighting\).

[IsUsableSpell](https://wow.gamepedia.com/API_IsUsableSpell)\("spellName" \| spellID \| spellIndex, "bookType"\) - Determines whether a spell can be used by the player character.

[PickupSpell](https://wow.gamepedia.com/API_PickupSpell)\("spellName" \| spellID, "bookType"\) - Loads an action button onto the cursor to be dropped into a quickbar slot.

UI [QueryCastSequence](https://wow.gamepedia.com/API_QueryCastSequence)\("sequence"\) - Returns index, item, spell for the spell/item that will be used next if the cast sequence is executed.

PROTECTED [SetMultiCastSpell](https://wow.gamepedia.com/API_SetMultiCastSpell)\(actionID,spellID\) - Assigns a spellID to a multicast \(totem bar\) actionID. \(added in 3.2\)

[SpellCanTargetUnit](https://wow.gamepedia.com/API_SpellCanTargetUnit)\("unit"\) - Returns true if the spell awaiting target selection can be cast on the specified unit.

SpellHasRange\(spell\) - Returns true if the specified spell has a ranged effect \(i.e. requires a target\).

[SpellIsTargeting](https://wow.gamepedia.com/API_SpellIsTargeting)\(\) - Returns true if a spell has been cast and is awaiting target selection.

PROTECTED [SpellStopCasting](https://wow.gamepedia.com/API_SpellStopCasting)\(\) - Stops the current spellcast.

PROTECTED [SpellStopTargeting](https://wow.gamepedia.com/API_SpellStopTargeting)\(\) - Cancels the spell awaiting target selection.

PROTECTED [SpellTargetUnit](https://wow.gamepedia.com/API_SpellTargetUnit)\("unit"\) - Casts the spell awaiting target selection on the specified unit.

PROTECTED ToggleSpellAutocast\("spellName" \| spellId, bookType\) - Toggles whether the specified spell should autocast or not. This is used for some pet abilities.

[UnitCastingInfo](https://wow.gamepedia.com/API_UnitCastingInfo)\("unit"\) - Returns information about the spell currently being cast by the specified unit.

[UnitChannelInfo](https://wow.gamepedia.com/API_UnitChannelInfo)\("unit"\) - Returns information about the spell currently being channeled by the specified unit.

