### 实例函数

###### 实例指战场实例,副本实例等.

[CanShowResetInstances](https://wow.gamepedia.com/API_CanShowResetInstances)\(\) - 确定玩家此刻是否可以重置实例。

[GetBattlefieldInstanceExpiration](https://wow.gamepedia.com/API_GetBattlefieldInstanceExpiration)\(\) - 获取战场实例的关闭计时器。

[GetBattlefieldInstanceRunTime](https://wow.gamepedia.com/API_GetBattlefieldInstanceRunTime)\(\) - 以毫秒为单位，自战场开始以来的时间（似乎是从服务器查询，因为它与time（）不同步）。

GetInstanceBootTimeRemaining\(\) - 获取用户从实例中弹出的时间（以秒为单位）。

[GetInstanceInfo](https://wow.gamepedia.com/API_GetInstanceInfo)\(\) - 获取有关当前实例的信息

[GetNumSavedInstances](https://wow.gamepedia.com/API_GetNumSavedInstances)\(\) - 获取用户当前已保存锁定数据的实例数。

[GetSavedInstanceInfo](https://wow.gamepedia.com/API_GetSavedInstanceInfo)\(index\) - 获取有关用户已保存锁定数据的实例的信息。

[IsInInstance](https://wow.gamepedia.com/API_IsInInstance)\(\) - 如果玩家在一个实例中，则返回1，以及实例的类型（pvp，raid等）。

[ResetInstances](https://wow.gamepedia.com/API_ResetInstances)\(\) - 重置实例。

[GetDifficultyInfo](https://wow.gamepedia.com/API_GetDifficultyInfo)\(\) - 返回有关难度的信息。

[GetDungeonDifficultyID](https://wow.gamepedia.com/API_GetDungeonDifficultyID)\(\) - 返回玩家当前的地下城难度设置（1,2,8）。

[SetDungeonDifficultyID](https://wow.gamepedia.com/API_SetDungeonDifficultyID)\(difficultyID\) - 设置玩家的地下城难度设置（适用于5人实例）。 查看 [difficultyID](https://wow.gamepedia.com/DifficultyID).

[GetRaidDifficultyID](https://wow.gamepedia.com/API_GetRaidDifficultyID)\(\) - 返回玩家当前的团本难度设置（1-14）。

[SetRaidDifficultyID](https://wow.gamepedia.com/API_SetRaidDifficultyID)\(difficultyID\) - 设置玩家团队副本难度设置（适用于10人，25人实例）。查看[difficultyID](https://wow.gamepedia.com/DifficultyID).

[GetInstanceLockTimeRemaining](https://wow.gamepedia.com/API_GetInstanceLockTimeRemaining)\(\) - 返回有关玩家当前进入的实例的实例锁定计时器的信息。

[GetInstanceLockTimeRemainingEncounter](https://wow.gamepedia.com/API_GetInstanceLockTimeRemainingEncounter)\(id\) - 返回有关玩家即将保存到的实例中的boss的信息。

