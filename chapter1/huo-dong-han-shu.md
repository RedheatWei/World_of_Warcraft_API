### 活动函数

###### 此部分用于使玩家做某事的功能（并且在其他地方没有涉及，并且不仅仅是确认步骤）。

[AcceptDuel](https://wow.gamepedia.com/API_AcceptDuel)\(\) - 玩家接受决斗。

PROTECTED [AttackTarget](https://wow.gamepedia.com/API_AttackTarget)\(\) - 攻击目标单位。

[CancelDuel](https://wow.gamepedia.com/API_CancelDuel)\(\) - 拒绝决斗的邀请。

[CancelLogout](https://wow.gamepedia.com/API_CancelLogout)\(\) - 取消退出计时器（从野外或退出）。

CancelSummon\(\) - 拒绝召唤请求。

[ConfirmSummon](https://wow.gamepedia.com/API_ConfirmSummon)\(\) - 接受召唤请求。

PROTECTED [DescendStop](https://wow.gamepedia.com/API_DescendStop)\(\) - 玩家停止下降（游泳或飞行时）

[Dismount](https://wow.gamepedia.com/API_Dismount)\(\) - 玩家卸下当前的坐骑。

PROTECTED [ForceQuit](https://wow.gamepedia.com/API_ForceQuit)\(\) - 立即退出游戏，绕过计时器。

[GetSheathState](https://wow.gamepedia.com/API_GetSheathState)\(\) - 返回玩家武器的鞘状态。

[GetPVPTimer](https://wow.gamepedia.com/API_GetPVPTimer)\(\) - 返回PvP标志消失之前的时间量。

GetSummonConfirmAreaName\(\) - 返回你被召唤的区域的名称。

[GetSummonConfirmSummoner](https://wow.gamepedia.com/API_GetSummonConfirmSummoner)\(\) - 返回召唤你的玩家的名字。

GetSummonConfirmTimeLeft\(\) - 返回挂起的召唤到期之前剩余的时间量。

PROTECTED [Logout](https://wow.gamepedia.com/API_Logout)\(\) - 将用户退出游戏。

PROTECTED [Quit](https://wow.gamepedia.com/API_Quit)\(\) - 退出游戏，不是Lua脚本。

[RandomRoll](https://wow.gamepedia.com/API_RandomRoll)\(min, max\) - 两个值之间是否随意滚动。

[SetPVP](https://wow.gamepedia.com/API_SetPVP)\(enable\) - 设置玩家PVP模式（1表示启用，nil最终关闭）。

PROTECTED [SitStandOrDescendStart](https://wow.gamepedia.com/API_SitStandOrDescendStart)\(\) - 玩家坐，站或下降。

[StartDuel](https://wow.gamepedia.com/API_StartDuel)\("name"\) - 挑战某人进行决斗（按名称）

[TogglePVP](https://wow.gamepedia.com/API_TogglePVP)\(\) - 切换PVP状态

[ToggleSheath](https://wow.gamepedia.com/API_ToggleSheath)\(\) - 切换护套或未护套武器。

UseSoulstone\(\) - 使用活跃的灵魂石在死后复活自己。也适用于具有轮回的萨满祭司。

