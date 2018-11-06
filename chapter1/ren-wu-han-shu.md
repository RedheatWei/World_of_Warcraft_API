### 人物函数

[AcceptResurrect](https://wow.gamepedia.com/API_AcceptResurrect)\(\) - 玩家接受来自其他玩家的请求以使他自己复活。

[AcceptXPLoss](https://wow.gamepedia.com/API_AcceptXPLoss)\(\) - 接受由灵魂医者重生的耐久性损失。（该名称是sprit res是XP丢失时的残余。）

CheckBinderDist\(\) - Check whether the player is close enough to interact with the Hearthstone binder.

ConfirmBinder\(\) - Confirm the request to set the binding of the player's Hearthstone.

[DeclineResurrect](https://wow.gamepedia.com/API_DeclineResurrect)\(\) - Decline the request from another player to resurrect him/herself.

PROTECTED [DestroyTotem](https://wow.gamepedia.com/API_DestroyTotem)\(slot\) - Destroys a totem/minion.

[GetBindLocation](https://wow.gamepedia.com/API_GetBindLocation)\(\) - Get the name of the location for your Hearthstone.

[GetComboPoints](https://wow.gamepedia.com/API_GetComboPoints)\(\) - Get the current number of combo points.

GetCorpseRecoveryDelay\(\) - Time left before a player can accept a resurrection.

[GetCurrentTitle](https://wow.gamepedia.com/API_GetCurrentTitle)\(\) - Returns the player's current [titleId](https://wow.gamepedia.com/TitleId)

.[GetMirrorTimerInfo](https://wow.gamepedia.com/API_GetMirrorTimerInfo)\(id\) - returns information about a mirror timer \(exhaustion, breath and feign death timers\)

[GetMirrorTimerProgress](https://wow.gamepedia.com/API_GetMirrorTimerProgress)\(id\) - returns the current value of a mirror timer \(exhaustion, breath and feign death timers\)

[GetMoney](https://wow.gamepedia.com/API_GetMoney)\(\) - Returns an integer value of your held money in copper.

[GetNumTitles](https://wow.gamepedia.com/API_GetNumTitles)\(\) - Returns the maximum [titleId](https://wow.gamepedia.com/TitleId).

GetPowerRegen\(\) - Returns normal and combat power regeneration rates.

[GetPVPDesired](https://wow.gamepedia.com/API_GetPVPDesired)\(\) - Returns whether the player has permanently turned on their PvP flag.

[GetRangedCritChance](https://wow.gamepedia.com/API_GetRangedCritChance)\(\) - Returns the players ranged critical strike chance.

GetReleaseTimeRemaining\(\) - Returns the amount of time left before your ghost is pulled from your body.

GetResSicknessDuration\(\)

[GetRestState](https://wow.gamepedia.com/API_GetRestState)\(\) - Returns information about a player's rest state. \(saved up experience bonus\)

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

