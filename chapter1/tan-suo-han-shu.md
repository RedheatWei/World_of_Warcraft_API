### 探索函数

###### 另见[Gossip功能](https://wow.gamepedia.com/World_of_Warcraft_API#Gossip_Functions)

[AbandonQuest](https://wow.gamepedia.com/API_AbandonQuest) - Abandon the specified quest.

[AcceptQuest](https://wow.gamepedia.com/API_AcceptQuest) - Accept the specified quest.

[AddAutoQuestPopUp](https://wow.gamepedia.com/API_AddAutoQuestPopUp)\(QuestID,Type\) - Adds quest to an internal list of quests for offer/completion popup notification. \(4.0.1\)

[AddQuestWatch](https://wow.gamepedia.com/API_AddQuestWatch)\(questIndex\[, watchTime\]\) - Add a quest to the watch list.

AddWorldQuestWatch\(questId\) - Adds a world quest to the watch list.

CloseQuest\(\) - Closes the shown quest.

[CollapseQuestHeader](https://wow.gamepedia.com/API_CollapseQuestHeader) - Collapses a quest header.

[CompleteQuest](https://wow.gamepedia.com/API_CompleteQuest) - Complete the specified quest.

[ConfirmAcceptQuest](https://wow.gamepedia.com/API_ConfirmAcceptQuest) - Accepts an offered quest that has been started by a party member; usually escort quests. \(Might only be available after QUEST\_ACCEPT\_CONFIRM event.\)

[DeclineQuest](https://wow.gamepedia.com/API_DeclineQuest)- Declines the currently offered quest.

[ExpandQuestHeader](https://wow.gamepedia.com/API_ExpandQuestHeader) - Expands a quest header.

[GetAbandonQuestName](https://wow.gamepedia.com/API_GetAbandonQuestName) - Gets the name of a quest while it is being abandoned.

GetActiveLevel\(index\) - Gets the level of an active quest \(only available after QUEST\_GREETING event\).

GetActiveTitle\(index\) - Gets the title of an active quest \(only available after QUEST\_GREETING event\).

[GetAutoQuestPopUp](https://wow.gamepedia.com/API_GetAutoQuestPopUp)\(Index\) - Retrieves quest info by index that added using [AddAutoQuestPopUp](https://wow.gamepedia.com/API_AddAutoQuestPopUp). \(4.0.1\)

GetAvailableLevel\(index\) - Gets the level of an available quest \(only available after QUEST\_GREETING event\).

[GetAvailableQuestInfo](https://wow.gamepedia.com/API_GetAvailableQuestInfo)\(index\) - Returns metadata \(quest type\) about an available quest. \(added in 3.3.3\)

GetAvailableTitle\(index\) - Gets the title of an available quest \(only available after QUEST\_GREETING event\).

GetDailyQuestsCompleted - Return the current number of daily quests completed today.

GetGreetingText\(\)

GetNumActiveQuests - Gets the number of currently active quests from this NPC \(only available after QUEST\_GREETING event\).

[GetNumAutoQuestPopUps](https://wow.gamepedia.com/API_GetNumAutoQuestPopUps)\(\) - Retrieves number of quests added via [AddAutoQuestPopUp](https://wow.gamepedia.com/API_AddAutoQuestPopUp). \(4.0.1\)

GetNumAvailableQuests - Gets the number of currently available quests from this NPC \(only available after QUEST\_GREETING event\).

[GetNumQuestChoices](https://wow.gamepedia.com/API_GetNumQuestChoices) - Returns the number of rewards available for choice for quest currently in gossip window.

[GetNumQuestItems](https://wow.gamepedia.com/API_GetNumQuestItems) - Returns the number of items necessary to complete a particular quest.

[GetNumQuestLeaderBoards](https://wow.gamepedia.com/API_GetNumQuestLeaderBoards)\(\[questIndex\]\) - Returns the number of available quest objectives.

[GetNumQuestLogChoices](https://wow.gamepedia.com/API_GetNumQuestLogChoices) - Returns the number of options someone has when getting a quest item.

[GetNumQuestLogEntries](https://wow.gamepedia.com/API_GetNumQuestLogEntries) - Returns the number of entries in the quest log.

[GetNumQuestLogRewards](https://wow.gamepedia.com/API_GetNumQuestLogRewards) - Returns the count of the rewards for a particular quest. \(7.0.3\)

GetNumQuestLogRewardSpells - Returns the number of spell rewards for the current selected quest.

[GetNumQuestRewards](https://wow.gamepedia.com/API_GetNumQuestRewards) - Returns number of reward items \(those that you always get\) for quest currently in gossip window.

GetNumQuestWatches\(\) - Returns the number of quest watches active.

GetObjectiveText\(\) - Gets the objective of the current quest.

[GetProgressText](https://wow.gamepedia.com/API_GetProgressText)\(\) - Returns quest progress text, displayed by the NPC before the player pressed "Continue".

[GetQuestBackgroundMaterial](https://wow.gamepedia.com/API_GetQuestBackgroundMaterial) - Returns the material string associated with the particular quest.

[GetQuestGreenRange](https://wow.gamepedia.com/API_GetQuestGreenRange)\(\) - Return for how many levels below you quests and mobs remain "green" \(i.e. yield xp\)

[GetQuestID](https://wow.gamepedia.com/API_GetQuestID) - Returns the ID of the quest most recently displayed in a gossip frame, even after that frame is closed.

[GetQuestIndexForTimer](https://wow.gamepedia.com/API_GetQuestIndexForTimer)\(timerID\) - Gets the quest log index of a quest being timed.

[GetQuestIndexForWatch](https://wow.gamepedia.com/API_GetQuestIndexForWatch)\(watchIndx\) - Return the quest index for the specified watch

[GetQuestItemInfo](https://wow.gamepedia.com/API_GetQuestItemInfo) - Returns basic information about the reward/choice/required item for quest currently in gossip window.

[GetQuestItemLink](https://wow.gamepedia.com/API_GetQuestItemLink) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for a selected quest reward/choice/required item for quest currently in gossip window.

[GetQuestLink](https://wow.gamepedia.com/API_GetQuestLink)\(index\) - Returns a [QuestLink](https://wow.gamepedia.com/QuestLink) for a quest

[GetQuestLogChoiceInfo](https://wow.gamepedia.com/API_GetQuestLogChoiceInfo) - Returns a bunch of data about a quest reward choice from the quest log.

GetQuestLogGroupNum\(\) - Returns suggested number of players for quest selected currently in log or 0 if there's no suggestion.

[GetQuestLogIndexByID](https://wow.gamepedia.com/API_GetQuestLogIndexByID)\(questID\) - Returns the index of the specified questID in the quest log.

[GetQuestLogItemLink](https://wow.gamepedia.com/API_GetQuestLogItemLink) - Returns item link for selected quest reward/choice/required item from quest log.

[GetQuestLogLeaderBoard](https://wow.gamepedia.com/API_GetQuestLogLeaderBoard)\(ldrIndex\[, questIndex\]\) - Gets information about the objectives for a quest.

[GetQuestLogPushable](https://wow.gamepedia.com/API_GetQuestLogPushable) - Returns true if the currently loaded quest in the quest window can be shared.

[GetQuestLogQuestText](https://wow.gamepedia.com/API_GetQuestLogQuestText)- Returns the description and objectives required for the specified quest.

GetQuestLogRequiredMoney - Returns amount of money required for quest completion from quest log.

[GetQuestLogRewardInfo](https://wow.gamepedia.com/API_GetQuestLogRewardInfo) - Returns a pile of reward item info from the quest log.

[GetQuestLogRewardMoney](https://wow.gamepedia.com/API_GetQuestLogRewardMoney) - Returns a number representing the amount of copper returned by a particular quest.

[GetQuestLogRewardSpell](https://wow.gamepedia.com/API_GetQuestLogRewardSpell) - Returns name and texture of spell awarded for quest completion from quest log.

REMOVED GetQuestLogRewardTalents - Returns number of talents awarded for quest completion from quest log.

[GetQuestLogSelection](https://wow.gamepedia.com/API_GetQuestLogSelection) - Returns a number associated with the QuestLogSelection index.

[GetQuestLogTimeLeft](https://wow.gamepedia.com/API_GetQuestLogTimeLeft) - Returns the seconds remaining on the current quest timer.

[GetQuestLogTitle](https://wow.gamepedia.com/API_GetQuestLogTitle)\(index\) - Returns verbose data about a particular quest log entry: level requirement, tag, suggested group, completed status, etc.

GetQuestMoneyToGet - Returns amount of money required for quest currently displayed in gossip.

[GetQuestResetTime](https://wow.gamepedia.com/API_GetQuestResetTime) - Returns number of seconds until quest reset.

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

