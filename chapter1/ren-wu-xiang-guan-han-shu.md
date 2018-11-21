### 任务函数

###### 另见[Gossip功能](https://wow.gamepedia.com/World_of_Warcraft_API#Gossip_Functions)

[AbandonQuest](https://wow.gamepedia.com/API_AbandonQuest) - 放弃指定的任务。

[AcceptQuest](https://wow.gamepedia.com/API_AcceptQuest) - 接受指定的任务。

[AddAutoQuestPopUp](https://wow.gamepedia.com/API_AddAutoQuestPopUp)\(QuestID,Type\) - 为任务/完成弹出通知添加任务内部任务列表。（4.0.1）

[AddQuestWatch](https://wow.gamepedia.com/API_AddQuestWatch)\(questIndex\[, watchTime\]\) - 在监视列表中添加任务。

AddWorldQuestWatch\(questId\) - 向观察列表添加世界任务。

CloseQuest\(\) - 关闭显示的任务。

[CollapseQuestHeader](https://wow.gamepedia.com/API_CollapseQuestHeader) - 折叠任务标题。

[CompleteQuest](https://wow.gamepedia.com/API_CompleteQuest) - 完成指定的任务。

[ConfirmAcceptQuest](https://wow.gamepedia.com/API_ConfirmAcceptQuest) - 接受由成员开始的提议任务;通常护送任务。（可能仅在QUEST\_ACCEPT\_CONFIRM事件之后可用。）

[DeclineQuest](https://wow.gamepedia.com/API_DeclineQuest)- 拒绝当前提供的任务。

[ExpandQuestHeader](https://wow.gamepedia.com/API_ExpandQuestHeader) - 扩展任务标题。

[GetAbandonQuestName](https://wow.gamepedia.com/API_GetAbandonQuestName) - 获取任务在被放弃时的名称。

GetActiveLevel\(index\) - 获取活动任务的级别（仅在QUEST\_GREETING事件之后可用）。

GetActiveTitle\(index\) - 获取活动任务的标题（仅在QUEST\_GREETING事件之后可用）。

[GetAutoQuestPopUp](https://wow.gamepedia.com/API_GetAutoQuestPopUp)\(Index\) - 使用[AddAutoQuestPopUp](https://wow.gamepedia.com/API_AddAutoQuestPopUp)添加的索引检索任务信息。（4.0.1）

GetAvailableLevel\(index\) - 获取可用任务的级别（仅在QUEST\_GREETING事件之后可用）。

[GetAvailableQuestInfo](https://wow.gamepedia.com/API_GetAvailableQuestInfo)\(index\) - 返回有关可用任务的元数据（任务类型）。（在3.3.3中添加）

GetAvailableTitle\(index\) - 获取可用任务的标题（仅在QUEST\_GREETING事件之后可用）。

GetDailyQuestsCompleted - 返回当前完成的每日任务数量。

GetGreetingText\(\)

GetNumActiveQuests - 从此NPC获取当前活动任务的数量（仅在QUEST\_GREETING事件之后可用）。

[GetNumAutoQuestPopUps](https://wow.gamepedia.com/API_GetNumAutoQuestPopUps)\(\) - 检索通过[AddAutoQuestPopUp](https://wow.gamepedia.com/API_AddAutoQuestPopUp)添加的任务数量。（4.0.1）

GetNumAvailableQuests - 获取此NPC中当前可用任务的数量（仅在QUEST\_GREETING事件后可用）。

[GetNumQuestChoices](https://wow.gamepedia.com/API_GetNumQuestChoices) - 返回当前面板窗口中可供选择的任务奖励数。

[GetNumQuestItems](https://wow.gamepedia.com/API_GetNumQuestItems) - 返回完成特定任务所需的项目数。

[GetNumQuestLeaderBoards](https://wow.gamepedia.com/API_GetNumQuestLeaderBoards)\(\[questIndex\]\) - 返回可用任务目标的数量。

[GetNumQuestLogChoices](https://wow.gamepedia.com/API_GetNumQuestLogChoices) - 返回获得任务项目时某人拥有的选项数量。

[GetNumQuestLogEntries](https://wow.gamepedia.com/API_GetNumQuestLogEntries) - 返回任务日志中的条目数。

[GetNumQuestLogRewards](https://wow.gamepedia.com/API_GetNumQuestLogRewards) - 返回特定任务的奖励计数。（7.0.3）

GetNumQuestLogRewardSpells - 返回当前所选任务的法术奖励数。

[GetNumQuestRewards](https://wow.gamepedia.com/API_GetNumQuestRewards) - 返回当前面板窗口中的任务奖励项目（您总是得到的奖励项目）。

GetNumQuestWatches\(\) - 返回活动的任务监视的数量。

GetObjectiveText\(\) - 获取当前任务的目标。

[GetProgressText](https://wow.gamepedia.com/API_GetProgressText)\(\) - 返回在玩家按下“继续”之前由NPC显示的任务进度文本。

[GetQuestBackgroundMaterial](https://wow.gamepedia.com/API_GetQuestBackgroundMaterial) - 返回与特定任务关联的材质字符串。

[GetQuestGreenRange](https://wow.gamepedia.com/API_GetQuestGreenRange)\(\) - 返回你下面多少级别的任务和怪物保持“绿色”（即产量xp）

[GetQuestID](https://wow.gamepedia.com/API_GetQuestID) - 返回最近在面板框架中显示的任务的ID，即使该框架关闭后也是如此。

[GetQuestIndexForTimer](https://wow.gamepedia.com/API_GetQuestIndexForTimer)\(timerID\) - 获取正在计时的任务的任务日志索引。

[GetQuestIndexForWatch](https://wow.gamepedia.com/API_GetQuestIndexForWatch)\(watchIndx\) - 返回指定监视的任务索引

[GetQuestItemInfo](https://wow.gamepedia.com/API_GetQuestItemInfo) - 返回当前面板窗口中有关任务的奖励/选择/必需项目的基本信息。

[GetQuestItemLink](https://wow.gamepedia.com/API_GetQuestItemLink) - 返回当前面板窗口中任务的所选任务奖励/选择/所需项目的[itemLink](https://wow.gamepedia.com/ItemLink)。

[GetQuestLink](https://wow.gamepedia.com/API_GetQuestLink)\(index\) - 返回任务的[QuestLink](https://wow.gamepedia.com/QuestLink)

[GetQuestLogChoiceInfo](https://wow.gamepedia.com/API_GetQuestLogChoiceInfo) - 从任务日志返回一系列有关任务奖励选择的数据。

GetQuestLogGroupNum\(\) - 返回当前在日志中选择的任务的建议玩家数量，如果没有建议则返回0。

[GetQuestLogIndexByID](https://wow.gamepedia.com/API_GetQuestLogIndexByID)\(questID\) - 返回任务日志中指定的questID的索引。

[GetQuestLogItemLink](https://wow.gamepedia.com/API_GetQuestLogItemLink) - 从任务日志返回所选任务奖励/选择/必需项目的项目链接。

[GetQuestLogLeaderBoard](https://wow.gamepedia.com/API_GetQuestLogLeaderBoard)\(ldrIndex\[, questIndex\]\) - 获取有关任务目标的信息。

[GetQuestLogPushable](https://wow.gamepedia.com/API_GetQuestLogPushable) - 如果可以共享任务窗口中当前加载的任务，则返回true。

[GetQuestLogQuestText](https://wow.gamepedia.com/API_GetQuestLogQuestText)- 返回指定任务所需的描述和目标。

GetQuestLogRequiredMoney - 从任务日志返回任务完成所需的金额。

[GetQuestLogRewardInfo](https://wow.gamepedia.com/API_GetQuestLogRewardInfo) - 从任务日志返回一堆奖励项目信息。

[GetQuestLogRewardMoney](https://wow.gamepedia.com/API_GetQuestLogRewardMoney) - 返回表示特定任务返回的铜量的数字。

[GetQuestLogRewardSpell](https://wow.gamepedia.com/API_GetQuestLogRewardSpell) - 从任务日志返回为任务完成而获得的法术的名称和纹理。

REMOVED GetQuestLogRewardTalents - 从任务日志返回为任务完成而获得的天赋数量。

[GetQuestLogSelection](https://wow.gamepedia.com/API_GetQuestLogSelection) - 返回与QuestLogSelection索引关联的数字。

[GetQuestLogTimeLeft](https://wow.gamepedia.com/API_GetQuestLogTimeLeft) - 返回当前任务计时器剩余的秒数。

[GetQuestLogTitle](https://wow.gamepedia.com/API_GetQuestLogTitle)\(index\) - 返回有关特定任务日志条目的详细数据：级别要求，标记，建议组，已完成状态等。

GetQuestMoneyToGet - 返回当前在面板中显示的任务所需的金额。

[GetQuestResetTime](https://wow.gamepedia.com/API_GetQuestResetTime) - 返回任务重置前的秒数。

[GetQuestReward](https://wow.gamepedia.com/API_GetQuestReward)\(rewardIndex\) - Completes the quest with the specified quest reward.

[GetQuestsCompleted](https://wow.gamepedia.com/API_GetQuestsCompleted)\(\[table\]\) - Returns table of completed quests.

[GetQuestTagInfo](https://wow.gamepedia.com/API_GetQuestTagInfo)\(questID\) - Returns tag information about the specified quest.

GetQuestText - Gets the description of the current quest.

[GetQuestTimers](https://wow.gamepedia.com/API_GetQuestTimers) - Returns all of the quest timers currently in progress.

GetRewardMoney\(\) - Returns a amount of copper rewarded for completion of quest displayed in gossip.

[GetRewardSpell](https://wow.gamepedia.com/API_GetRewardSpell)\(\) - Returns name and texture of spell awarded for quest completion for quest currently in gossip window.

REMOVED GetRewardTalents\(\) - Returns number of talents awarded for quest completion for quest currently in gossip window.

[GetRewardText](https://wow.gamepedia.com/API_GetRewardText)\(\) - Returns quest reward text, displayed by the NPC before the player hits "Complete Quest".

GetRewardTitle\(\) - Returns the title awarded by the currently displayed quest.

[GetRewardXP](https://wow.gamepedia.com/API_GetRewardXP)\(\) - Returns the amount of experience awarded by the currently displayed text.

[GetTitleText](https://wow.gamepedia.com/API_GetTitleText) - Retrieves the title of the quest while talking to the NPC about it.

IsCurrentQuestFailed - ?.

[IsQuestCompletable](https://wow.gamepedia.com/API_IsQuestCompletable) - Returns true if a quest is possible to complete.

[IsQuestFlaggedCompleted](https://wow.gamepedia.com/API_IsQuestFlaggedCompleted)\(questID\) - Determine if a quest has been completed.

IsQuestWatched\(questIndex\) - Determine if the specified quest is watched.

[IsUnitOnQuest](https://wow.gamepedia.com/API_IsUnitOnQuest)\(questIndex, "unit"\) - Determine if the specified unit is on the given quest.

IsWorldQuestWatched\(questId\) - Determine if the world quest id is tracked

IsUnitOnQuestByQuestID\(questId, "unit"\) - Determine if the specified unit is on the given quest.

[QuestChooseRewardError](https://wow.gamepedia.com/API_QuestChooseRewardError) - Throws an error when the quest choose reward method doesn't work.

QuestFlagsPVP\(\) - Determine if the quest will flag you you for PvP when accepted.

[QuestGetAutoAccept](https://wow.gamepedia.com/API_QuestGetAutoAccept)\(\) - Returns whether the last-offered quest was automatically accepted. \(3.3.0\)

[QuestIsDaily](https://wow.gamepedia.com/API_QuestIsDaily)\(\) - Returns whether the offered quest is a daily quest. \(3.3.3\)

[QuestIsWeekly](https://wow.gamepedia.com/API_QuestIsWeekly)\(\) - Returns whether the offered quest is a weekly quest. \(3.3.3\)

[QuestLogPushQuest](https://wow.gamepedia.com/API_QuestLogPushQuest) - Initiates the sharing of the currently viewed quest in the quest log.

[RemoveQuestWatch](https://wow.gamepedia.com/API_RemoveQuestWatch)\(questIndex\) - Removes a quest watch by questIndex.

RemoveWorldQuestWatch\(questId\) - Removes a world quest from the watch.

SelectActiveQuest - Selects an active quest from the NPC \(only available after QUEST\_GREETING event\).

SelectAvailableQuest - Selects an available quest from the NPC \(only available after QUEST\_GREETING event\).

[SelectQuestLogEntry](https://wow.gamepedia.com/API_SelectQuestLogEntry) - Sets the selected quest, required for most GetQuest functions.

[SetAbandonQuest](https://wow.gamepedia.com/API_SetAbandonQuest) - Called before [AbandonQuest](https://wow.gamepedia.com/API_AbandonQuest).

REMOVED [ShiftQuestWatches](https://wow.gamepedia.com/API_ShiftQuestWatches)\(id1, id2\) - Exchanges the order of two watched quests. \(3.3.3\)

[SortQuestWatches](https://wow.gamepedia.com/API_SortQuestWatches)\(\) - Sorts the watched quests according to proximity and returns whether the order changed since last sorting. \(3.3.3\)

