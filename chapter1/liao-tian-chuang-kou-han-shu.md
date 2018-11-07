### 聊天窗口函数

###### 这些是特定于聊天窗口管理的功能。另请参见“[通道功能](https://wow.gamepedia.com/World_of_Warcraft_API#Channel_Functions)和[通信功能](https://wow.gamepedia.com/World_of_Warcraft_API#Communication_Functions)”部分。

[AddChatWindowChannel](https://wow.gamepedia.com/API_AddChatWindowChannel)\(chatFrameIndex, "channel"\) - 在特定的聊天框架中显示聊天频道。

[AddChatWindowMessages](https://wow.gamepedia.com/API_AddChatWindowMessages) - 将消息传递组添加到指定的聊天窗口。

[ChangeChatColor](https://wow.gamepedia.com/API_ChangeChatColor)\("channelName", r, g, b\) - 更新一种聊天消息的颜色

UI [ChatFrame\_AddChannel](https://wow.gamepedia.com/API_ChatFrame_AddChannel)\(chatFrame, "channelName"\) - 在聊天框架中激活频道。

UI [ChatFrame\_AddMessageEventFilter](https://wow.gamepedia.com/API_ChatFrame_AddMessageEventFilter)\("event", filterFunc\) - 添加聊天消息过滤。（在2.4中添加）

UI [ChatFrame\_GetMessageEventFilters](https://wow.gamepedia.com/API_ChatFrame_GetMessageEventFilters)\("event"\) - 返回聊天消息过滤列表。（在2.4中添加）

UI [ChatFrame\_OnHyperlinkShow](https://wow.gamepedia.com/API_ChatFrame_OnHyperlinkShow)\(reference, link, button\) - 当用户点击聊天链接时调用。

UI [ChatFrame\_RemoveMessageEventFilter](https://wow.gamepedia.com/API_ChatFrame_RemoveMessageEventFilter)\("event", filterFunc\) - 注销聊天消息过滤。（在2.4中添加）

[GetAutoCompleteResults](https://wow.gamepedia.com/API_GetAutoCompleteResults)\("text", include, exclude, maxResults\[, cursorPosition\]\) - 返回与给定前缀字符串和指定要求匹配的可能玩家名称。

[GetChatTypeIndex](https://wow.gamepedia.com/API_GetChatTypeIndex)\(type\) - 获取某种聊天消息的数字ID。

[GetChatWindowChannels](https://wow.gamepedia.com/API_GetChatWindowChannels)\(index\) - 获取聊天窗口收到的聊天频道。

[GetChatWindowInfo](https://wow.gamepedia.com/API_GetChatWindowInfo)\(index\) - 获取有关聊天窗口的设置信息。

[GetChatWindowMessages](https://wow.gamepedia.com/API_GetChatWindowMessages)\(index\) - 获取聊天窗口收到的聊天消息类型。

[JoinChannelByName](https://wow.gamepedia.com/API_JoinChannelByName)\("channel"\[, "password"\[, frameId\]\]\) - 加入指定的聊天频道。（使用可选密码，并注册指定帧）（在1.9中更新）

[LoggingChat](https://wow.gamepedia.com/API_LoggingChat)\(newState\) - 获取或设置是否启用了对Logs\WoWChatLog.txt的日志记录聊天。

[LoggingCombat](https://wow.gamepedia.com/API_LoggingCombat)\(newState\) - 获取或设置是否启用了对Logs\WoWCombatLog.txt的日志记录战斗。

[RemoveChatWindowChannel](https://wow.gamepedia.com/API_RemoveChatWindowChannel)\(chatFrameIndex, "channel"\) - 使聊天频道在特定的聊天框中不可见（隐藏）。

[RemoveChatWindowMessages](https://wow.gamepedia.com/API_RemoveChatWindowMessages)\(chatFrameIndex,"messageGroup"\) - 从此窗口中删除一组聊天消息。

这些函数在重新加载UI后应用（索引1为常规，索引2为战斗日志）：

SetChatWindowAlpha\(index,alpha\) - 设置聊天框 &lt;index&gt;的Alpha值（透明度）（alpha  -  0-100）

SetChatWindowColor\(index, r, g, b\) - 设置聊天窗口的背景颜色。（r/g/b  -  0-255）

SetChatWindowDocked\(index,docked\) - 设置是否停靠聊天窗口。（停靠 -  0/1）

SetChatWindowLocked\(index,locked\) - 设置聊天框 &lt;index&gt;以使其可移动或不移动。（锁定 -  0/1）

SetChatWindowName\(index,"name"\) - 设置聊天框的Alpha值。

SetChatWindowShown\(index,shown\) - 显示或隐藏聊天框 &lt;index&gt;，具体取决于&lt;shown&gt;的值（显示为 -  0/1）

SetChatWindowSize\(index,size\) - 设置聊天窗口的字体大小。（大小 - 默认14）

SetChatWindowUninteractable\(id, isUninteractable\) - 添加于3.0.8

