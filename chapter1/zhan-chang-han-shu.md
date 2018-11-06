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

GetBattlefieldMapIconScale\(\) - 战场小地图地标刻度尺.

[GetBattlefieldPortExpiration](https://wow.gamepedia.com/API_GetBattlefieldPortExpiration)\(index\) - 获取战场到期前的剩余秒数。

[GetBattlefieldScore](https://wow.gamepedia.com/API_GetBattlefieldScore)\(index\) - 获取有关玩家的分数信息。

[GetBattlefieldStatData](https://wow.gamepedia.com/API_GetBattlefieldStatData)\(playerIndex, slotIndex\) - 从特定于战场的列中获取玩家的信息（如战歌峡谷旗帜捕获）。

[GetBattlefieldStatInfo](https://wow.gamepedia.com/API_GetBattlefieldStatInfo)\(index\) - 获取记分板的战场特定列。

[GetBattlefieldStatus](https://wow.gamepedia.com/API_GetBattlefieldStatus)\(index\) - 获取战场的当前状态。

[GetBattlefieldTimeWaited](https://wow.gamepedia.com/API_GetBattlefieldTimeWaited)\(index\) - 获取以毫秒为单位在队列中等待时间。

[GetBattlefieldWinner](https://wow.gamepedia.com/API_GetBattlefieldWinner)\(\) - 获取战场胜利者。

[GetBattlegroundInfo](https://wow.gamepedia.com/API_GetBattlegroundInfo)\(index\) - 返回战场类型的信息。

[GetMaxBattlefieldID](https://wow.gamepedia.com/API_GetMaxBattlefieldID)\(\) - 返回可以排队的最大战场数。

GetNumBattlefieldFlagPositions\(\) - 获取GetBattlefieldFlagPosition\(\)中可用的标志位置数。

[GetNumBattlefieldScores](https://wow.gamepedia.com/API_GetNumBattlefieldScores)\(\) -返回战场记分牌中分数\(玩家\)列表。

[GetNumBattlefieldStats](https://wow.gamepedia.com/API_GetNumBattlefieldStats)\(\) -获取特定于战场的列数。

[GetNumWorldStateUI](https://wow.gamepedia.com/API_GetNumWorldStateUI)\(\) - 获取WorldState UI的数量。

[GetWorldStateUIInfo](https://wow.gamepedia.com/API_GetWorldStateUIInfo)\(index\) - 在战场中获得分数和旗帜状态。

IsPVPTimerRunning\(\)

PROTECTED [JoinBattlefield](https://wow.gamepedia.com/API_JoinBattlefield)\(index\[, joinAs\]\) - 无论是单人还是团体，都可以为战场排队。

[LeaveBattlefield](https://wow.gamepedia.com/API_LeaveBattlefield)\(\) - 离开现在的战场

ReportPlayerIsPVPAFK\("unit"\) - 在战场中将指定的玩家报告为AFK。

[RequestBattlefieldScoreData](https://wow.gamepedia.com/API_RequestBattlefieldScoreData)\(\) - 请求GetBattlefieldScore\(\)的新数据。

[RequestBattlegroundInstanceInfo](https://wow.gamepedia.com/API_RequestBattlegroundInstanceInfo)\(index\) - 请求有关战场可用实例的数据。

[SetBattlefieldScoreFaction](https://wow.gamepedia.com/API_SetBattlefieldScoreFaction)\(\[faction\]\) - 将阵营设置为在战场记分牌上显示。

