### 实例函数

[CanShowResetInstances](https://wow.gamepedia.com/API_CanShowResetInstances)\(\) - 确定玩家此刻是否可以重置实例。

[GetBattlefieldInstanceExpiration](https://wow.gamepedia.com/API_GetBattlefieldInstanceExpiration)\(\) - Get shutdown timer for the battlefield instance.

[GetBattlefieldInstanceRunTime](https://wow.gamepedia.com/API_GetBattlefieldInstanceRunTime)\(\) - In milliseconds, the time since battleground started \(seems to be queried from server because it is not in sync with time\(\)\).

GetInstanceBootTimeRemaining\(\) - Gets the time in seconds after which the player will be ejected from an instance.

[GetInstanceInfo](https://wow.gamepedia.com/API_GetInstanceInfo)\(\) - Gets informations about the current Instance

[GetNumSavedInstances](https://wow.gamepedia.com/API_GetNumSavedInstances)\(\) - Gets the number of instances for which the player currently has lockout data saved.

[GetSavedInstanceInfo](https://wow.gamepedia.com/API_GetSavedInstanceInfo)\(index\) - Gets information about an instance for which the player has saved lockout data.

[IsInInstance](https://wow.gamepedia.com/API_IsInInstance)\(\) - Returns 1 if the player is in an instance, as well as the type of instance \(pvp, raid, etc.\).

[ResetInstances](https://wow.gamepedia.com/API_ResetInstances)\(\) - Reset instances.

[GetDifficultyInfo](https://wow.gamepedia.com/API_GetDifficultyInfo)\(\) - Returns information about a difficulty.

[GetDungeonDifficultyID](https://wow.gamepedia.com/API_GetDungeonDifficultyID)\(\) - Returns the player's current Dungeon Difficulty setting \(1, 2, 8\).

[SetDungeonDifficultyID](https://wow.gamepedia.com/API_SetDungeonDifficultyID)\(difficultyID\) - Sets the player's Dungeon Difficulty setting \(for the 5-man instances\). See [difficultyID](https://wow.gamepedia.com/DifficultyID).

[GetRaidDifficultyID](https://wow.gamepedia.com/API_GetRaidDifficultyID)\(\) - Returns the player's current Raid Difficulty setting \(1-14\).

[SetRaidDifficultyID](https://wow.gamepedia.com/API_SetRaidDifficultyID)\(difficultyID\) - Sets the players Raid Difficulty settings \(for 10-man, 25-man instances\). See [difficultyID](https://wow.gamepedia.com/DifficultyID).

[GetInstanceLockTimeRemaining](https://wow.gamepedia.com/API_GetInstanceLockTimeRemaining)\(\) - Returns information about the instance lock timer for the instance the player is currently entering.

[GetInstanceLockTimeRemainingEncounter](https://wow.gamepedia.com/API_GetInstanceLockTimeRemainingEncounter)\(id\) - Returns information about bosses in the instance the player is about to be saved to.



