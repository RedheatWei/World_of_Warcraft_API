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

[GetRuneCooldown](https://wow.gamepedia.com/API_GetRuneCooldown)\(id\) - 返回有关给定符文的冷却时间信息。

GetRuneCount\(slot\) - 返回给定槽中的符文数。（死亡骑士）

REMOVED [GetRuneType](https://wow.gamepedia.com/API_GetRuneType)\(id\) - 返回具有给定id的符文类型。

[GetTitleName](https://wow.gamepedia.com/API_GetTitleName)\([titleId](https://wow.gamepedia.com/TitleId)\) - 返回玩家当前的标题名称。

[GetXPExhaustion](https://wow.gamepedia.com/API_GetXPExhaustion)\(\) - 返回角色当前休息的XP，如果没有休息，则返回nil。

[HasFullControl](https://wow.gamepedia.com/API_HasFullControl)\(\)

[HasSoulstone](https://wow.gamepedia.com/API_HasSoulstone)\(\)

[IsFalling](https://wow.gamepedia.com/API_IsFalling)\(\) - 如果你的角色目前正在直线下滑，则返回1。

[IsFlying](https://wow.gamepedia.com/API_IsFlying)\(\) - 如果飞行则返回1，否则为零。

[IsFlyableArea](https://wow.gamepedia.com/API_IsFlyableArea)\(\) - 如果可以在这里飞行则返回1，否则返回nil。

[IsIndoors](https://wow.gamepedia.com/API_IsIndoors)\(\) - 如果你在室内，则返回1，否则为零。对于仍然可以安装的室内区域，返回nil。

[IsMounted](https://wow.gamepedia.com/API_IsMounted)\(\) - 如果已上坐骑，则返回1，否则返回nil。

[IsOutdoors](https://wow.gamepedia.com/API_IsOutdoors)\(\) -如果你在户外，则返回1，否则为零。对于仍然可以安装的室内区域，返回1。

[IsOutOfBounds](https://wow.gamepedia.com/API_IsOutOfBounds)\(\) - 如果你从地图上掉下来，则返回1。

[IsResting](https://wow.gamepedia.com/API_IsResting)\(\) - 如果你的角色当前正在休息，则返回1。

[IsStealthed](https://wow.gamepedia.com/API_IsStealthed)\(\) - 如果是潜行或阴影，则返回1，否则返回nil。

[IsSwimming](https://wow.gamepedia.com/API_IsSwimming)\(\) - 如果你的角色正在游泳，则返回1。

IsTitleKnown\(index\) - 如果标题对玩家有效，则返回1，否则返回0。

IsXPUserDisabled\(\) - 如果角色已禁用经验增益，则返回1。

[NotWhileDeadError](https://wow.gamepedia.com/API_NotWhileDeadError)\(\) - 生成一条错误消息，告诉您在死亡时无法执行此操作。

ResurrectHasSickness\(\) - 似乎在接受复活时会使用会给你复活的情感。

ResurrectHasTimer\(\) - 玩家是否必须在接受复活前等待。

ResurrectGetOfferer\(\) - 返回提供给您复活的人的姓名。

[RetrieveCorpse](https://wow.gamepedia.com/API_RetrieveCorpse)\(\) - 靠近尸体时复活。例如，跑回你身体后看到的“接受”按钮。

HW [SetCurrentTitle](https://wow.gamepedia.com/API_SetCurrentTitle)\([titleId](https://wow.gamepedia.com/TitleId)\) - 按ID设置用户的当前标题。.

TargetTotem\(\) - Added in 3.0.8

