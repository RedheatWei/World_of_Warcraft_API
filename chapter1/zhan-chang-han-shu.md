### 战场函数

[AcceptAreaSpiritHeal](https://wow.gamepedia.com/API_AcceptAreaSpiritHeal)\(\) - 接受灵魂治疗.

[AcceptBattlefieldPort](https://wow.gamepedia.com/API_AcceptBattlefieldPort)\(index\[, acceptFlag\]\) - 接受或拒绝提供的战场端口。

[CancelAreaSpiritHeal](https://wow.gamepedia.com/API_CancelAreaSpiritHeal)\(\) - 取消灵魂治疗.

[CanJoinBattlefieldAsGroup](https://wow.gamepedia.com/API_CanJoinBattlefieldAsGroup)\(\) - 如果玩家不能为战场进行团体加入，则返回nil。

CheckSpiritHealerDist\(\) - 如果你在灵魂医者的范围内死亡，则返回true。

[GetAreaSpiritHealerTime](https://wow.gamepedia.com/API_GetAreaSpiritHealerTime)\(\) - 返回灵魂治疗下一次复活的剩余时间。

[GetBattlefieldEstimatedWaitTime](https://wow.gamepedia.com/API_GetBattlefieldEstimatedWaitTime)\(index\) - 获得进入战场的估计等待时间。

[GetBattlefieldFlagPosition](https://wow.gamepedia.com/API_GetBattlefieldFlagPosition)\(index\) - 获取标志的地图位置和纹理。

[GetBattlefieldInstanceExpiration](https://wow.gamepedia.com/API_GetBattlefieldInstanceExpiration)\(\) - 获取战场实例的关闭计时器。

[GetBattlefieldInstanceRunTime](https://wow.gamepedia.com/API_GetBattlefieldInstanceRunTime)\(\) - 以毫秒为单位，自战场开始以来的时间（似乎是从服务器查询，因为它与time\(\)不同步）。

GetBattlefieldMapIconScale\(\) - Scale of the landmark icons on the battlefield minimap.

[GetBattlefieldPortExpiration](https://wow.gamepedia.com/API_GetBattlefieldPortExpiration)\(index\) - Get the remaining seconds before the battlefield port expires.

[GetBattlefieldScore](https://wow.gamepedia.com/API_GetBattlefieldScore)\(index\) - Get score information about a player.

[GetBattlefieldStatData](https://wow.gamepedia.com/API_GetBattlefieldStatData)\(playerIndex, slotIndex\) - Get information for a player from a column thats specific to a battleground \(like Warsong Gulch flag captures\).

[GetBattlefieldStatInfo](https://wow.gamepedia.com/API_GetBattlefieldStatInfo)\(index\) - Get the battleground specific column for the score board.

[GetBattlefieldStatus](https://wow.gamepedia.com/API_GetBattlefieldStatus)\(index\) - Get the battlefield's current status.

[GetBattlefieldTimeWaited](https://wow.gamepedia.com/API_GetBattlefieldTimeWaited)\(index\) - Get time waited in queue in milliseconds.

[GetBattlefieldWinner](https://wow.gamepedia.com/API_GetBattlefieldWinner)\(\) - Get the battlefields winner.

[GetBattlegroundInfo](https://wow.gamepedia.com/API_GetBattlegroundInfo)\(index\) - Returns information about a battleground type.

[GetMaxBattlefieldID](https://wow.gamepedia.com/API_GetMaxBattlefieldID)\(\) - Returns the max number of battlefields you can queue for.

GetNumBattlefieldFlagPositions\(\) - Get the number of flag positions available from GetBattlefieldFlagPosition\(\).

[GetNumBattlefieldScores](https://wow.gamepedia.com/API_GetNumBattlefieldScores)\(\) - Returns the number of scores\(players\) listed in the battlefield scoreboard.

[GetNumBattlefieldStats](https://wow.gamepedia.com/API_GetNumBattlefieldStats)\(\) - Get the number of battleground specific columns.

[GetNumWorldStateUI](https://wow.gamepedia.com/API_GetNumWorldStateUI)\(\) - Get the number of WorldState UI's.

[GetWorldStateUIInfo](https://wow.gamepedia.com/API_GetWorldStateUIInfo)\(index\) - Get score and flag status within a battlefield.

IsPVPTimerRunning\(\)

PROTECTED [JoinBattlefield](https://wow.gamepedia.com/API_JoinBattlefield)\(index\[, joinAs\]\) - Queue for a battleground either solo or as a group.

[LeaveBattlefield](https://wow.gamepedia.com/API_LeaveBattlefield)\(\) - Leave the current battlefield

ReportPlayerIsPVPAFK\("unit"\) - Reports the specified player as AFK in a battleground.

[RequestBattlefieldScoreData](https://wow.gamepedia.com/API_RequestBattlefieldScoreData)\(\) - Request new data for GetBattlefieldScore\(\).

[RequestBattlegroundInstanceInfo](https://wow.gamepedia.com/API_RequestBattlegroundInstanceInfo)\(index\) - Requests data about the available instances of a battleground.

[SetBattlefieldScoreFaction](https://wow.gamepedia.com/API_SetBattlefieldScoreFaction)\(\[faction\]\) - Set the faction to show on the battlefield scoreboard.



