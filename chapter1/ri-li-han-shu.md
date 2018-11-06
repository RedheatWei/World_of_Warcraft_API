### 日历函数

HW [CalendarAddEvent](https://wow.gamepedia.com/API_CalendarAddEvent)\(\) - 保存所选事件（仅限新事件，需要硬件输入才能调用）

CalendarCanAddEvent\(\) - 如果玩家可以添加事件，则返回true

CalendarCanSendInvite\(\) - 如果玩家可以发送邀请，则返回true

CalendarCloseEvent\(\) - 关闭所选事件而不保存

CalendarContextDeselectEvent\(\) - 添加于3.0.8

CalendarContextEventCanComplain\(monthOffset, day, eventIndex\) - 如果玩家可以将事件报告为垃圾邮件，则返回true

CalendarContextEventCanEdit\(monthOffset, day, eventIndex\) - 如果玩家可以编辑事件，则返回true

CalendarContextEventCanRemove\(monthOffset, day, eventIndex\) - 如果玩家可以移除事件，则返回true。

CalendarContextEventClipboard\(\)

CalendarContextEventComplain\(monthOffset, day, eventIndex\) - 将该事件报告为垃圾邮件

CalendarContextEventCopy\(monthOffset, day, eventIndex\) - 将事件复制到剪贴板

CalendarContextEventGetCalendarType\(\) - ?

CalendarContextEventPaste\(monthOffset, day\) - 将剪贴板事件粘贴到日期

CalendarContextEventRemove\(monthOffset, day, eventIndex\) - 删除事件

CalendarContextEventSignUp\(\) - ?

CalendarContextGetEventIndex\(\) - 添加于3.0.8

CalendarContextInviteAvailable\(monthOffset, day, eventIndex\) - 接受邀请参加活动

CalendarContextInviteDecline\(monthOffset, day, eventIndex\) - 拒绝活动的邀请

CalendarContextInviteIsPending\(monthOffset, day, eventIndex\) - 如果玩家未响应活动邀请，则返回true

CalendarContextInviteTentative\(\) - ?

CalendarContextInviteType - ?

CalendarContextInviteModeratorStatus\(monthOffset, day, eventIndex\) - ?

CalendarContextInviteRemove\(monthOffset, day, eventIndex\) - 从日历中删除事件

CalendarContextInviteStatus\(monthOffset, day, eventIndex\) - 返回邀请状态

CalendarContextSelectEvent\(monthOffset, day, eventIndex\) - 添加于3.0.8

CalendarDefaultGuildFilter\(\) - 返回最小等级和最大等级

CalendarEventAvailable\(\) - 接受当前公开活动的邀请

CalendarEventCanEdit\(\) - 如果可以编辑事件，则返回true

CalendarEventCanModerate - ?

CalendarEventClearAutoApprove\(\) - 关闭自动确认

CalendarEventClearLocked\(\) - 解锁事件

CalendarEventClearModerator\(\)

CalendarEventDecline\(\) - 拒绝当前打开的事件的邀请

CalendarEventGetCalendarType\(\) - ?

[CalendarEventGetInvite](https://wow.gamepedia.com/API_CalendarEventGetInvite)\(inviteIndex\) -  返回当前打开的事件的被邀请者的状态信息

CalendarEventGetInviteResponseTime\(inviteIndex\) - ?

CalendarEventGetInviteSortCriterion\(\) - 返回标准，翻转

[CalendarEventGetNumInvites](https://wow.gamepedia.com/API_CalendarEventGetNumInvites)\(\) - 返回当前打开的事件的被邀请者数量

CalendarEventGetRepeatOptions\(\) - 返回选项1,选项2

CalendarEventGetSelectedInvite\(\) - 返回邀请索引

CalendarEventGetStatusOptions\(\) - Returns ??

CalendarEventGetTextures\(eventType\) - 返回标题1, 文本1, 经验等级1, 标题2, 文本2, 经验等级2, ...

CalendarEventGetTypes\(\) - 返回名称1,名称2, ...

CalendarEventGetTypesDisplayOrdered\(\)

CalendarEventHasPendingInvite\(\) - 如果玩家对当前所选事件有未答复的邀请，则返回true

CalendarEventHaveSettingsChanged\(\) - 如果已修改当前打开的事件，则返回true

[CalendarEventInvite](https://wow.gamepedia.com/API_CalendarEventInvite)\("player"\) - 邀请玩家参加当前选定的活动

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

CalendarEventSetStatus\(index, status\) - 将玩家的邀请状态设置为当前事件

CalendarEventSetTextureID\(textureIndex\)

CalendarEventSetTime\(hour, minute\)

CalendarEventSetTitle\(title\)

[CalendarEventSetType](https://wow.gamepedia.com/API_CalendarEventSetType)\(type\)

CalendarEventSignUp\(\) - ?

CalendarEventSortInvites\(criterion\)

CalendarEventTentative\(\) - ?

[CalendarGetAbsMonth](https://wow.gamepedia.com/API_CalendarGetAbsMonth)\(\) - returns month, year

[CalendarGetDate](https://wow.gamepedia.com/API_CalendarGetDate)\(\) - 只在PLAYER\_ENTERING\_WORLD事件后调用

[CalendarGetDayEvent](https://wow.gamepedia.com/API_CalendarGetDayEvent)\(monthOffset, day, eventIndex\)

[CalendarGetDayEventSequenceInfo](https://wow.gamepedia.com/API_CalendarGetDayEventSequenceInfo) - 检索有关指定事件的信息。

CalendarGetEventIndex\(\) - 返回月偏移,天,索引

[CalendarGetEventInfo](https://wow.gamepedia.com/API_CalendarGetEventInfo)\(\) - 返回有关使用CalendarOpenEvent\(\)选择的事件的详细信息

CalendarGetFirstPendingInvite\(monthOffset, day\) - 返回事件索引

CalendarGetGuildEventInfo\(eventId\) -

CalendarGetGuildEventSelectionInfo\(index\)

CalendarGetHolidayInfo\(monthOffset, day, eventIndex\) - 返回假日名称，假日描述，日历图标

CalendarGetMaxCreateDate\(\) - 返回 maxWeekday, maxMonth, maxDay, maxYear

CalendarGetMaxDate\(\) - 返回 maxWeekday, maxMonth, maxDay, maxYear

[CalendarGetMinDate](https://wow.gamepedia.com/API_CalendarGetMinDate)\(\) - 返回 minWeekday, minMonth, minDay, minYear

CalendarGetMinHistoryDate\(\) - 返回 minWeekday, minMonth, minDay, minYear

[CalendarGetMonth](https://wow.gamepedia.com/API_CalendarGetMonth)\(\[monthOffset\]\) - 返回 month, year

[CalendarGetMonthNames](https://wow.gamepedia.com/API_CalendarGetMonthNames)\(\) - 返回月份名称列表

[CalendarGetNumDayEvents](https://wow.gamepedia.com/API_CalendarGetNumDayEvents)\(monthOffset\[, day\]\)

CalendarGetNumGuildEvents\(\)

CalendarGetNumPendingInvites\(\) - returns count

CalendarGetRaidInfo \(monthOffset, day, eventIndex\) - 返回名称,日历类型, raidID, 时 分, 难度

CalendarGetWeekdayNames\(\) - 返回工作日名称列表

CalendarIsActionPending\(\) - 返回是否等待

CalendarMassInviteGuild\(minLevel, maxLevel, rank\) - ?

[CalendarNewEvent](https://wow.gamepedia.com/API_CalendarNewEvent)\(\) - 创建并选择一个新事件

CalendarNewGuildAnnouncement\(\) - ?

CalendarNewGuildEvent\(minLevel, maxLevel, minRank\) - 用指定的公会成员替换所选新事件的邀请列表

[CalendarOpenEvent](https://wow.gamepedia.com/API_CalendarOpenEvent)\(monthOffset, day, eventIndex\) - 选择一个已有的事件

CalendarRemoveEvent\(\) - 在日历中移除选中的事件\(仅限受邀者\)

CalendarSetAbsMonth\(month, year\) - 设置使用月份偏移的函数的引用月份和年份

CalendarSetMonth\(monthOffset\)

CalendarUpdateEvent\(\) - 保存选择的事件 \(仅限存在的事件,需要硬件输入调用\)

[OpenCalendar](https://wow.gamepedia.com/API_OpenCalendar)\(\) - 在服务器请求日历信息. 不启动日历框架. \(添加于3.0.8\)

