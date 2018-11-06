### 日历函数

HW [CalendarAddEvent](https://wow.gamepedia.com/API_CalendarAddEvent)\(\) - 保存所选事件（仅限新事件，需要硬件输入才能调用）

CalendarCanAddEvent\(\) - 如果玩家可以添加事件，则返回true

CalendarCanSendInvite\(\) - 如果玩家可以发送邀请，则返回true

CalendarCloseEvent\(\) - 关闭所选事件而不保存

CalendarContextDeselectEvent\(\) - 添加于3.0.8

CalendarContextEventCanComplain\(monthOffset, day, eventIndex\) - 如果玩家可以将事件报告为垃圾邮件，则返回true

CalendarContextEventCanEdit\(monthOffset, day, eventIndex\) - 如果玩家可以编辑事件，则返回true

CalendarContextEventCanRemove\(monthOffset, day, eventIndex\) - Returns true if player can remove event.

CalendarContextEventClipboard\(\)

CalendarContextEventComplain\(monthOffset, day, eventIndex\) - Reports the event as spam

CalendarContextEventCopy\(monthOffset, day, eventIndex\) - Copies the event to the clipboard

CalendarContextEventGetCalendarType\(\) - ?

CalendarContextEventPaste\(monthOffset, day\) - Pastes the clipboard event to the date

CalendarContextEventRemove\(monthOffset, day, eventIndex\) - Deletes the event

CalendarContextEventSignUp\(\) - ?

CalendarContextGetEventIndex\(\) - added in 3.0.8

CalendarContextInviteAvailable\(monthOffset, day, eventIndex\) - Accepts the invitation to the event

CalendarContextInviteDecline\(monthOffset, day, eventIndex\) - Declines the invitation to the event

CalendarContextInviteIsPending\(monthOffset, day, eventIndex\) - Returns true if the player hasn't responded to the event invite

CalendarContextInviteTentative\(\) - ?

CalendarContextInviteType - ?

CalendarContextInviteModeratorStatus\(monthOffset, day, eventIndex\) - ?

CalendarContextInviteRemove\(monthOffset, day, eventIndex\) - Removes the event from the calendar

CalendarContextInviteStatus\(monthOffset, day, eventIndex\) - returns inviteStatus

CalendarContextSelectEvent\(monthOffset, day, eventIndex\) - added in 3.0.8

CalendarDefaultGuildFilter\(\) - returns minLevel, maxLevel

CalendarEventAvailable\(\) - Accepts the inviation to the currently open event

CalendarEventCanEdit\(\) - Returns true if the event can be edited

CalendarEventCanModerate - ?

CalendarEventClearAutoApprove\(\) - Turns off automatic confirmations

CalendarEventClearLocked\(\) - Unlocks the event

CalendarEventClearModerator\(\)

CalendarEventDecline\(\) - Declines the invitation to the currently open event

CalendarEventGetCalendarType\(\) - ?

[CalendarEventGetInvite](https://wow.gamepedia.com/API_CalendarEventGetInvite)\(inviteIndex\) - Returns status information for an invitee for the currently opened event

CalendarEventGetInviteResponseTime\(inviteIndex\) - ?

CalendarEventGetInviteSortCriterion\(\) - returns criterion, reverse

[CalendarEventGetNumInvites](https://wow.gamepedia.com/API_CalendarEventGetNumInvites)\(\) - Returns the number of invitees for the currently opened event

CalendarEventGetRepeatOptions\(\) - Returns opt1, opt2

CalendarEventGetSelectedInvite\(\) - returns inviteIndex

CalendarEventGetStatusOptions\(\) - Returns ??

CalendarEventGetTextures\(eventType\) - Returns title1, tex1, expLvl1, title2, tex2, expLvl2, ...

CalendarEventGetTypes\(\) - Returns name1, name2, ...

CalendarEventGetTypesDisplayOrdered\(\)

CalendarEventHasPendingInvite\(\) - Returns true if the player has an unanswered invitation to the currently selected event

CalendarEventHaveSettingsChanged\(\) - Returns true if the currently open event has been modified

[CalendarEventInvite](https://wow.gamepedia.com/API_CalendarEventInvite)\("player"\) - Invite player to currently selected event

CalendarEventIsModerator\(\) - ?

CalendarEventRemoveInvite\(inviteIndex\)

CalendarEventSelectInvite\(inviteIndex\)

CalendarEventSetAutoApprove\(\)

[CalendarEventSetDate](https://wow.gamepedia.com/API_CalendarEventSetDate)\(month, day, year\)

CalendarEventSetDescription\(description\)

CalendarEventSetLocked\(\)

CalendarEventSetLockoutDate\(lockoutDate\) - ??

CalendarEventSetLockoutTime\(lockoutTime\) - ??

CalendarEventSetModerator\(index\)

CalendarEventSetRepeatOption\(repeatoption\)

CalendarEventSetSize - ??

CalendarEventSetStatus\(index, status\) - Sets the invitation status of a player to the current event

CalendarEventSetTextureID\(textureIndex\)

CalendarEventSetTime\(hour, minute\)

CalendarEventSetTitle\(title\)

[CalendarEventSetType](https://wow.gamepedia.com/API_CalendarEventSetType)\(type\)

CalendarEventSignUp\(\) - ?

CalendarEventSortInvites\(criterion\)

CalendarEventTentative\(\) - ?

[CalendarGetAbsMonth](https://wow.gamepedia.com/API_CalendarGetAbsMonth)\(\) - returns month, year

[CalendarGetDate](https://wow.gamepedia.com/API_CalendarGetDate)\(\) - Call this only after PLAYER\_ENTERING\_WORLD event

[CalendarGetDayEvent](https://wow.gamepedia.com/API_CalendarGetDayEvent)\(monthOffset, day, eventIndex\)

[CalendarGetDayEventSequenceInfo](https://wow.gamepedia.com/API_CalendarGetDayEventSequenceInfo) - Retrieve information about the specified event.

CalendarGetEventIndex\(\) - returns monthOffset, day, index

[CalendarGetEventInfo](https://wow.gamepedia.com/API_CalendarGetEventInfo)\(\) - Returns detailed information about an event selected with CalendarOpenEvent\(\)

CalendarGetFirstPendingInvite\(monthOffset, day\) - returns eventIndex

CalendarGetGuildEventInfo\(eventId\) -

CalendarGetGuildEventSelectionInfo\(index\)

CalendarGetHolidayInfo\(monthOffset, day, eventIndex\) - Returns Holiday Name, Holiday Description, Calendar Icon

CalendarGetMaxCreateDate\(\) - returns maxWeekday, maxMonth, maxDay, maxYear

CalendarGetMaxDate\(\) - returns maxWeekday, maxMonth, maxDay, maxYear

[CalendarGetMinDate](https://wow.gamepedia.com/API_CalendarGetMinDate)\(\) - returns minWeekday, minMonth, minDay, minYear

CalendarGetMinHistoryDate\(\) - returns minWeekday, minMonth, minDay, minYear

[CalendarGetMonth](https://wow.gamepedia.com/API_CalendarGetMonth)\(\[monthOffset\]\) - returns month, year

[CalendarGetMonthNames](https://wow.gamepedia.com/API_CalendarGetMonthNames)\(\) - returns a list of the month names

[CalendarGetNumDayEvents](https://wow.gamepedia.com/API_CalendarGetNumDayEvents)\(monthOffset\[, day\]\)

CalendarGetNumGuildEvents\(\)

CalendarGetNumPendingInvites\(\) - returns count

CalendarGetRaidInfo \(monthOffset, day, eventIndex\) - returns name, calendarType, raidID, hour, minute, difficulty

CalendarGetWeekdayNames\(\) - returns a list of the weekday names

CalendarIsActionPending\(\) - returns isPending

CalendarMassInviteGuild\(minLevel, maxLevel, rank\) - ?

[CalendarNewEvent](https://wow.gamepedia.com/API_CalendarNewEvent)\(\) - Creates and selected a new event

CalendarNewGuildAnnouncement\(\) - ?

CalendarNewGuildEvent\(minLevel, maxLevel, minRank\) - Replaces the invite list of the selected new event with the specified guild members

[CalendarOpenEvent](https://wow.gamepedia.com/API_CalendarOpenEvent)\(monthOffset, day, eventIndex\) - Selects an existing event

CalendarRemoveEvent\(\) - Removes the selected event from the calendar \(invitees only\)

CalendarSetAbsMonth\(month, year\) - Sets the reference month and year for functions which use a month offset

CalendarSetMonth\(monthOffset\)

CalendarUpdateEvent\(\) - Saves the selected event \(existing events only, requires hardware input to call\)

[OpenCalendar](https://wow.gamepedia.com/API_OpenCalendar)\(\) - Requests calendar information from the server. Does not open the calendar frame. \(added in 3.0.8\)

