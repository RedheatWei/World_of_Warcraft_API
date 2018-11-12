### 公会函数

[AcceptGuild](https://wow.gamepedia.com/API_AcceptGuild)\(\) - The player accepts the invitation to join a guild.

[BuyGuildCharter](https://wow.gamepedia.com/API_BuyGuildCharter)\("guildName"\) - Purchases a guild charter for guildName.

CanEditGuildEvent\(\) - Returns true if you are allowed to edit guild events \(in the calendar\),

CanEditGuildInfo\(\) - Returns true if you are allowed to edit the guild info

[CanEditMOTD](https://wow.gamepedia.com/API_CanEditMOTD)\(\) - Returns true if you are allowed to edit the guild motd.

CanEditOfficerNote\(\) - Returns true if you are allowed to edit a guild member's officer note.

CanEditPublicNote\(\) - Returns true if you are allowed to edit a guild member's public note.

[CanGuildDemote](https://wow.gamepedia.com/API_CanGuildDemote)\(\) - Returns true if you are allowed to demote a guild member.

[CanGuildInvite](https://wow.gamepedia.com/API_CanGuildInvite)\(\) - Returns true if you are allowed to invite a new member to the guild.

[CanGuildPromote](https://wow.gamepedia.com/API_CanGuildPromote)\(\) - Returns true if you are allowed to demote a guild member.

CanGuildRemove\(\) - Returns true if you are allowed to remove a guild member.

[CanReplaceGuildMaster](https://wow.gamepedia.com/API_CanReplaceGuildMaster)\(\) - Returns whether you can impeach the Guild Master due to inactivity.

[CanViewOfficerNote](https://wow.gamepedia.com/API_CanViewOfficerNote)\(\) - Returns true if you are allowed to view a Officer Note.

CloseGuildRegistrar\(\) - ?.

CloseGuildRoster\(\) - ?.

CloseTabardCreation\(\) - ?.

[DeclineGuild](https://wow.gamepedia.com/API_DeclineGuild)\(\) - The player declines the invitation to join a guild.

[GetGuildApplicantInfo](https://wow.gamepedia.com/API_GetGuildApplicantInfo)\(index\) - Returns information about a guild applicant.

GetGuildCharterCost\(\) - Returns the cost of purchasing a guild charter.

GetGuildEventInfo\(index\) - Returns the event information. \(Added in 2.3\)

[GetGuildFactionInfo](https://wow.gamepedia.com/API_GetGuildFactionInfo)\(\) - Returns the guild name and faction standing of the player.

[GetGuildInfo](https://wow.gamepedia.com/API_GetGuildInfo)\("unit"\) - This function returns the name of the guild unit belongs to.

GetGuildInfoText\(\) - Returns the persistant Guild Information data. \(added in 1.9\)

REMOVED GetGuildRosterContribution\(index\) - Returns weekly and total XP as well as weekly and total rank.

REMOVED GetGuildRosterLargestContribution\(\) - Returns max weekly XP and max total XP.

GetGuildRosterLargestAchievementPoints\(\) - Returns max achievements points.

[GetGuildRosterInfo](https://wow.gamepedia.com/API_GetGuildRosterInfo)\(index\) - This function is used to get info on members in the guild.

[GetGuildRosterLastOnline](https://wow.gamepedia.com/API_GetGuildRosterLastOnline)\(index\) - Returns time since last online for indexth member in current sort order.

[GetGuildRosterMOTD](https://wow.gamepedia.com/API_GetGuildRosterMOTD)\(\) - Returns guild's MOTD.

[GetGuildRosterSelection](https://wow.gamepedia.com/API_GetGuildRosterSelection)\(\) - Returns the index of the current selected guild member.

[GetGuildRosterShowOffline](https://wow.gamepedia.com/API_GetGuildRosterShowOffline)\(\) - Returns true if showing offline members of the guild.

[GetGuildTradeSkillInfo](https://wow.gamepedia.com/API_GetGuildTradeSkillInfo)

\(index\) - Returns the tradeskill index for a guild tradeskill using the index from GetNumGuildTradeSkill

[GetNumGuildApplicants](https://wow.gamepedia.com/API_GetNumGuildApplicants)

\(\) - Returns the total number of guild applicants.

GetNumGuildEvents\(\) - Returns the number of guild events. \(Added in 2.3\)

[GetNumGuildMembers](https://wow.gamepedia.com/API_GetNumGuildMembers)\(\) - Returns the number of total and online guild members.

GetNumGuildTradeSkill\(\) - Returns the number of tradeskills available to the guild UI

GetTabardCreationCost\(\) - Returns cost in coppers.

GetTabardInfo\(\) -?.

GuildControlAddRank\("name"\) - Add another rank called "name". Only Guildmaster.

[GuildControlDelRank](https://wow.gamepedia.com/API_GuildControlDelRank)\("name"\) - Delete rank "name". Only Guildmaster.

GuildControlGetNumRanks\(\) - Returns number of ranks after guild frame open. Any guild member can use this.

[GuildControlGetRankFlags](https://wow.gamepedia.com/API_GuildControlGetRankFlags)\(\) - Returns list of values for each permission for a select rank \(default rank 1\).

[GuildControlGetRankName](https://wow.gamepedia.com/API_GuildControlGetRankName)\(index\) - Returns name of the rank at index. Any guild member can use this.

[GuildControlSaveRank](https://wow.gamepedia.com/API_GuildControlSaveRank)\("name"\) - Saves the permissions for rank "name". Only Guildmaster.

[GuildControlSetRank](https://wow.gamepedia.com/API_GuildControlSetRank)\(rank\) - Sets the currently selected rank to view.

[GuildControlSetRankFlag](https://wow.gamepedia.com/API_GuildControlSetRankFlag)\(index, enabled\) - Enable/disable permission for an action at index. Only Guildmaster.

[GuildDemote](https://wow.gamepedia.com/API_GuildDemote)\("name"\) - Demotes a player "name".

[GuildDisband](https://wow.gamepedia.com/API_GuildDisband)\(\) - Disbands at once your guild. You must be the guild's leader to do so. Be careful, no warning is given prior disbanding.

[GuildInfo](https://wow.gamepedia.com/API_GuildInfo)\(\) - Displays information about the guild you are a member of.

[GuildInvite](https://wow.gamepedia.com/API_GuildInvite)\("name"\) - Invites a player to your guild.

[GuildLeave](https://wow.gamepedia.com/API_GuildLeave)\(\) - Removes you from your current guild.

[GuildPromote](https://wow.gamepedia.com/API_GuildPromote)\("name"\) - Promotes a player "name".

[GuildRoster](https://wow.gamepedia.com/API_GuildRoster)\(\) - Fetches the guild list and fires a GUILD\_ROSTER\_UPDATE event.

[GuildRosterSetOfficerNote](https://wow.gamepedia.com/API_GuildRosterSetOfficerNote)\(index, "note"\) - Sets the officer note at index to "note".

[GuildRosterSetPublicNote](https://wow.gamepedia.com/API_GuildRosterSetPublicNote)\(index, "note"\) - Sets the public note at index to "note".

[GuildSetMOTD](https://wow.gamepedia.com/API_GuildSetMOTD)\("note"\) - Set Guild Message of the Day to "note".

[GuildSetLeader](https://wow.gamepedia.com/API_GuildSetLeader)\("name"\) - Transfers guild leadership to another character.

GuildUninvite\("name"\) - Removes the member "name".

[IsGuildLeader](https://wow.gamepedia.com/API_IsGuildLeader)\("name"\) - Determine if player "name" is a guild master.

[IsInGuild](https://wow.gamepedia.com/API_IsInGuild)\(\) - Lets you know whether you are in a guild.

QueryGuildEventLog\(\) - Fetches the guild event list and fires a GUILD\_EVENT\_LOG\_UPDATE event. \(Added in 2.3\)

[ReplaceGuildMaster](https://wow.gamepedia.com/API_ReplaceGuildMaster)\(\) - Impeaches the current Guild Master.

[RequestGuildApplicantsList](https://wow.gamepedia.com/API_RequestGuildApplicantsList)\(\) - Requests information about guild applicants.

[SetGuildInfoText](https://wow.gamepedia.com/API_SetGuildInfoText)\(\) - Sets the persistant Guild Information data. Limit is 500 letters \(GuildInfoEditBox is limited to this number\). Longer texts are possible, but will be reseted during the day. \(added in 1.9\)

[SetGuildRosterSelection](https://wow.gamepedia.com/API_SetGuildRosterSelection)\(index\) - Selects/deselects a guild member according current sorting order.

[SetGuildRosterShowOffline](https://wow.gamepedia.com/API_SetGuildRosterShowOffline)\(enabled\) - Sets/Resets the show offline members flag.

[SortGuildRoster](https://wow.gamepedia.com/API_SortGuildRoster)\("sort"\) - Sorts guildroster according "sort". Any unknown values sort on "name".

