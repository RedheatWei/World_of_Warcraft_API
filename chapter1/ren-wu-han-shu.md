### 人物函数

[AcceptResurrect](https://wow.gamepedia.com/API_AcceptResurrect)\(\) - 玩家接受来自其他玩家的请求以使他自己复活。

[AcceptXPLoss](https://wow.gamepedia.com/API_AcceptXPLoss)\(\) - 接受由灵魂医者重生的耐久性损失。（该名称是sprit res是XP丢失时的残余。）

CheckBinderDist\(\) - 检查玩家是否足够接近旅店老板

ConfirmBinder\(\) - 确认设置玩家炉石的绑定的请求。

[DeclineResurrect](https://wow.gamepedia.com/API_DeclineResurrect)\(\) - 拒绝其他玩家要求复活他自己的请求。

PROTECTED [DestroyTotem](https://wow.gamepedia.com/API_DestroyTotem)\(slot\) - 摧毁图腾/仆从.

[GetBindLocation](https://wow.gamepedia.com/API_GetBindLocation)\(\) - 获取炉石的位置名称。

[GetComboPoints](https://wow.gamepedia.com/API_GetComboPoints)\(\) - 获取当前的连击点数。

GetCorpseRecoveryDelay\(\) - 在玩家复活剩余的时间。

[GetCurrentTitle](https://wow.gamepedia.com/API_GetCurrentTitle)\(\) - 返回玩家当前的[titleId](https://wow.gamepedia.com/TitleId)

.[GetMirrorTimerInfo](https://wow.gamepedia.com/API_GetMirrorTimerInfo)\(id\) - 返回有关镜像计时器的信息（耗尽，呼吸和假死亡计时器）

[GetMirrorTimerProgress](https://wow.gamepedia.com/API_GetMirrorTimerProgress)\(id\) - 返回镜像计时器的当前值（耗尽，呼吸和假死亡计时器）

[GetMoney](https://wow.gamepedia.com/API_GetMoney)\(\) - 返回您持有的铜币的整数值。

[GetNumTitles](https://wow.gamepedia.com/API_GetNumTitles)\(\) -返回最大[titleId](https://wow.gamepedia.com/TitleId).

GetPowerRegen\(\) - 返回正常和战斗力再生率。

[GetPVPDesired](https://wow.gamepedia.com/API_GetPVPDesired)\(\) - 返回玩家是否已永久打开其PvP标志。

[GetRangedCritChance](https://wow.gamepedia.com/API_GetRangedCritChance)\(\) -返回玩家远程爆击几率。

GetReleaseTimeRemaining\(\) - 返回灵魂被从身体中拉出之前剩余的时间。

GetResSicknessDuration\(\)

[GetRestState](https://wow.gamepedia.com/API_GetRestState)\(\) - 返回有关玩家休息状态的信息。（积攒经验奖励）

[GetRuneCooldown](https://wow.gamepedia.com/API_GetRuneCooldown)\(id\) - Returns cooldown information about a given rune.

GetRuneCount\(slot\) - Returns the number of Runes in the given slot. \(Death Knight\)

REMOVED [GetRuneType](https://wow.gamepedia.com/API_GetRuneType)\(id\) - Returns the type of rune with the given id.

[GetTitleName](https://wow.gamepedia.com/API_GetTitleName)\([titleId](https://wow.gamepedia.com/TitleId)\) - Returns the player's current title name.

[GetXPExhaustion](https://wow.gamepedia.com/API_GetXPExhaustion)\(\) - Returns your character's current rested XP, nil if character is not rested.

[HasFullControl](https://wow.gamepedia.com/API_HasFullControl)\(\)

[HasSoulstone](https://wow.gamepedia.com/API_HasSoulstone)\(\)

[IsFalling](https://wow.gamepedia.com/API_IsFalling)\(\) - Returns 1 if your character is currently plummeting to their doom.

[IsFlying](https://wow.gamepedia.com/API_IsFlying)\(\) - Returns 1 if flying, otherwise nil.

[IsFlyableArea](https://wow.gamepedia.com/API_IsFlyableArea)\(\) - Returns 1 if it is possible to fly here, nil otherwise.

[IsIndoors](https://wow.gamepedia.com/API_IsIndoors)\(\) - Returns 1 if you are indoors, otherwise nil. Returns nil for indoor areas where you can still mount.

[IsMounted](https://wow.gamepedia.com/API_IsMounted)\(\) - Returns 1 if mounted, otherwise nil.

[IsOutdoors](https://wow.gamepedia.com/API_IsOutdoors)\(\) - Returns 1 if you are outdoors, otherwise nil. Returns 1 for indoor areas where you can still mount.

[IsOutOfBounds](https://wow.gamepedia.com/API_IsOutOfBounds)\(\) - Returns 1 if you fell off the map.

[IsResting](https://wow.gamepedia.com/API_IsResting)\(\) - Returns 1 if your character is currently resting.

[IsStealthed](https://wow.gamepedia.com/API_IsStealthed)\(\) - Returns 1 if stealthed or shadowmeld, otherwise nil.

[IsSwimming](https://wow.gamepedia.com/API_IsSwimming)\(\) - Returns 1 if your character is currently swimming.

IsTitleKnown\(index\) - Returns 1 if the title is valid for the player, otherwise 0.

IsXPUserDisabled\(\) - Returns 1 if the character has disabled experience gain.

[NotWhileDeadError](https://wow.gamepedia.com/API_NotWhileDeadError)\(\) - Generates an error message saying you cannot do that while dead.

ResurrectHasSickness\(\) - Appears to be used when accepting a resurrection will give you resurrection sickessness.

ResurrectHasTimer\(\) - Does the player have to wait before accepting a resurrection.

ResurrectGetOfferer\(\) - Returns the name of the person offering to resurrect you.

[RetrieveCorpse](https://wow.gamepedia.com/API_RetrieveCorpse)\(\) - Resurrects when near corpse. e.g., The "Accept" button one sees after running back to your body.

HW [SetCurrentTitle](https://wow.gamepedia.com/API_SetCurrentTitle)\([titleId](https://wow.gamepedia.com/TitleId)\) - Sets the player's current title by id.

TargetTotem\(\) - Added in 3.0.8

