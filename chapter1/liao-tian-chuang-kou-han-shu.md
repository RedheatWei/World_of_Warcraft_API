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

[GetChatWindowInfo](https://wow.gamepedia.com/API_GetChatWindowInfo)\(index\) - Get setup information about a chat window.

[GetChatWindowMessages](https://wow.gamepedia.com/API_GetChatWindowMessages)\(index\) - Get the chat message types received by a chat window.

[JoinChannelByName](https://wow.gamepedia.com/API_JoinChannelByName)\("channel"\[, "password"\[, frameId\]\]\) - Join the specified chat channel. \(with optional password, and register for specified frame\) \(updated in 1.9\)

[LoggingChat](https://wow.gamepedia.com/API_LoggingChat)\(newState\) - Gets or sets whether logging chat to Logs\WoWChatLog.txt is enabled.

[LoggingCombat](https://wow.gamepedia.com/API_LoggingCombat)\(newState\) - Gets or sets whether logging combat to Logs\WoWCombatLog.txt is enabled.

[RemoveChatWindowChannel](https://wow.gamepedia.com/API_RemoveChatWindowChannel)\(chatFrameIndex, "channel"\) - Make a chat channel invisible \(hidden\) in a specific ChatFrame.

[RemoveChatWindowMessages](https://wow.gamepedia.com/API_RemoveChatWindowMessages)\(chatFrameIndex,"messageGroup"\) - Remove a set of chat messages from this window.

These functions get applied after Reload UI \(index 1 is General and index 2 is Combat Log\):

SetChatWindowAlpha\(index,alpha\) - Sets the Alpha value\(transparency\) of ChatFrame&lt;index&gt; \(alpha - 0-100\)

SetChatWindowColor\(index, r, g, b\) - Sets the background color of a a chat window. \(r/g/b - 0-255\)

SetChatWindowDocked\(index,docked\) - Set whether a chat window is docked. \(docked - 0/1\)

SetChatWindowLocked\(index,locked\) - Sets ChatFrame&lt;index&gt; so that it is or is not movable. \(locked - 0/1\)

SetChatWindowName\(index,"name"\) - Sets the alpha value of ChatFrame.

SetChatWindowShown\(index,shown\) - Shows or Hides ChatFrame&lt;index&gt; depending on value of &lt;shown&gt; \(shown - 0/1\)

SetChatWindowSize\(index,size\) - Sets the font size of a chat window. \(size - default 14\)

SetChatWindowUninteractable\(id, isUninteractable\) - added in 3.0.8

