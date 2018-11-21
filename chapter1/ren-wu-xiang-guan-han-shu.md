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

[GetQuestReward](https://wow.gamepedia.com/API_GetQuestReward)\(rewardIndex\) - 用指定的任务奖励完成任务。

[GetQuestsCompleted](https://wow.gamepedia.com/API_GetQuestsCompleted)\(\[table\]\) - 返回已完成任务的表。

[GetQuestTagInfo](https://wow.gamepedia.com/API_GetQuestTagInfo)\(questID\) - 返回有关指定任务的标记信息。

GetQuestText - 获取当前任务的描述。

[GetQuestTimers](https://wow.gamepedia.com/API_GetQuestTimers) - 返回当前正在进行的所有任务计时器。

GetRewardMoney\(\) - 返回完成面板中显示的任务所奖励的铜金额。

[GetRewardSpell](https://wow.gamepedia.com/API_GetRewardSpell)\(\) - 返回当前在面板窗口中为任务完成查询所获得的技能的名称和纹理。

REMOVED GetRewardTalents\(\) - 返回当前面板窗口中任务完成任务的人数。 

[GetRewardText](https://wow.gamepedia.com/API_GetRewardText)\(\) - 返回在玩家点击“完成任务”之前由NPC显示的任务奖励文本。

GetRewardTitle\(\) - 返回当前显示的任务授予的标题。

[GetRewardXP](https://wow.gamepedia.com/API_GetRewardXP)\(\) - 返回当前显示的文本授予的经验数量。

[GetTitleText](https://wow.gamepedia.com/API_GetTitleText) - 在与NPC谈论它时，检索任务的标题。

IsCurrentQuestFailed - ?.

[IsQuestCompletable](https://wow.gamepedia.com/API_IsQuestCompletable) - 如果可以完成任务，则返回true。

[IsQuestFlaggedCompleted](https://wow.gamepedia.com/API_IsQuestFlaggedCompleted)\(questID\) - 确定任务是否已完成。

IsQuestWatched\(questIndex\) - 确定是否监视指定的任务。

[IsUnitOnQuest](https://wow.gamepedia.com/API_IsUnitOnQuest)\(questIndex, "unit"\) - 确定指定的单位是否在给定的任务中。

IsWorldQuestWatched\(questId\) - 确定是否跟踪了世界任务ID

IsUnitOnQuestByQuestID\(questId, "unit"\) - 确定指定的单位是否在给定的任务中。

[QuestChooseRewardError](https://wow.gamepedia.com/API_QuestChooseRewardError) - 当任务选择奖励方法不起作用时引发错误。

QuestFlagsPVP\(\) - 确定任务是否会在接受时标记您的PvP。

[QuestGetAutoAccept](https://wow.gamepedia.com/API_QuestGetAutoAccept)\(\) - 返回是否自动接受最后提供的任务。（3.3.0）

[QuestIsDaily](https://wow.gamepedia.com/API_QuestIsDaily)\(\) - 返回提供的任务是否为每日任务。（3.3.3）

[QuestIsWeekly](https://wow.gamepedia.com/API_QuestIsWeekly)\(\) - 返回提供的任务是否为每周任务。（3.3.3）

[QuestLogPushQuest](https://wow.gamepedia.com/API_QuestLogPushQuest) - 在任务日志中启动当前查看的任务的共享。

[RemoveQuestWatch](https://wow.gamepedia.com/API_RemoveQuestWatch)\(questIndex\) - 通过questIndex删除任务监视。

RemoveWorldQuestWatch\(questId\) - 从监视器中移除世界任务。

SelectActiveQuest - 从NPC中选择一个活动任务（仅在QUEST\_GREETING事件之后可用）。

SelectAvailableQuest - 从NPC中选择一个可用的任务（仅在QUEST\_GREETING事件后可用）。

[SelectQuestLogEntry](https://wow.gamepedia.com/API_SelectQuestLogEntry) - 设置大多数GetQuest函数所需的选定任务。

[SetAbandonQuest](https://wow.gamepedia.com/API_SetAbandonQuest) - [AbandonQuest](https://wow.gamepedia.com/API_AbandonQuest) 前调用

REMOVED [ShiftQuestWatches](https://wow.gamepedia.com/API_ShiftQuestWatches)\(id1, id2\) - 交换两个观察任务的顺序。（3.3.3）

[SortQuestWatches](https://wow.gamepedia.com/API_SortQuestWatches)\(\) - 根据接近度对观察到的任务进行排序，并返回自上次排序后订单是否发生变化。（3.3.3）

