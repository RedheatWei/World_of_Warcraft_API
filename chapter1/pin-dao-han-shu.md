### 频道函数

###### 这些是特定于频道的聊天函数。另请参见[聊天窗口函数](https://wow.gamepedia.com/World_of_Warcraft_API#Chat_Window_Functions)和[通信函数](https://wow.gamepedia.com/World_of_Warcraft_API#Communication_Functions)部分。

[AddChatWindowChannel](https://wow.gamepedia.com/API_AddChatWindowChannel)\(chatFrameIndex, "channel"\) - 在特定的ChatFrame中显示聊天频道。

[ChannelBan](https://wow.gamepedia.com/API_ChannelBan)\("channel", "name"\) - 禁止指定频道的玩家。

[ChannelInvite](https://wow.gamepedia.com/API_ChannelInvite)\("channel", "name"\) - 邀请指定的用户加入频道。

[ChannelKick](https://wow.gamepedia.com/API_ChannelKick)\("channel", "name"\) - 从频道中踢出指定的用户。

[ChannelModerator](https://wow.gamepedia.com/API_ChannelModerator)\("channel", "name"\) - 将指定的玩家设置为频道所有者。

[ChannelMute](https://wow.gamepedia.com/API_ChannelMute)\("channel", "name"\) - 关闭指定玩家在频道中发言的能力。

[ChannelToggleAnnouncements](https://wow.gamepedia.com/API_ChannelToggleAnnouncements)\("channel"\) - 切换频道以打开或关闭通知。

[ChannelUnban](https://wow.gamepedia.com/API_ChannelUnban)\("channel", "name"\) - 启用指定玩家在频道中发言的能力.

[ChannelUnmoderator](https://wow.gamepedia.com/API_ChannelUnmoderator)\("channel", "name"\) - 取消指定用户的频道所有者状态.

[ChannelUnmute](https://wow.gamepedia.com/API_ChannelUnmute)\("channel", "name"\) - 从通道取消指定用户静音。

[DisplayChannelOwner](https://wow.gamepedia.com/API_DisplayChannelOwner)\("channel"\) - 在默认聊天中显示指定频道的所有者。

[EnumerateServerChannels](https://wow.gamepedia.com/API_EnumerateServerChannels)\(\) - 检索所有可用的服务器频道（取决于区域）。

[GetChannelList](https://wow.gamepedia.com/API_GetChannelList)\(\) - 检索已加入的频道。

[GetChannelName](https://wow.gamepedia.com/API_GetChannelName)\("channel" or index\) - 检索特定频道名称.

[GetChatWindowChannels](https://wow.gamepedia.com/API_GetChatWindowChannels)\(index\) - 获取聊天窗口收到的聊天频道。

[JoinChannelByName](https://wow.gamepedia.com/API_JoinChannelByName)\("channel"\[, "password"\[, frameId\]\]\) - 加入指定的聊天频道（使用可选密码，并注册指定的帧）（在1.9中更新）。

[JoinPermanentChannel](https://wow.gamepedia.com/API_JoinPermanentChannel)\("channel"\[, "password"\[, frameId\]\]\) - 永久加入指定的聊天频道（使用可选密码，并注册指定的帧）

[JoinTemporaryChannel](https://wow.gamepedia.com/API_JoinTemporaryChannel)\("channel"\[, "password"\[, frameId\]\]\) - 临时加入指定的聊天频道（使用可选密码，并注册指定的帧）

[LeaveChannelByName](https://wow.gamepedia.com/API_LeaveChannelByName)\("channel"\) -离开指定名称的通道。

[ListChannelByName](https://wow.gamepedia.com/API_ListChannelByName)\(channelMatch\) - 列出给定频道中的成员到聊天窗口。

[ListChannels](https://wow.gamepedia.com/API_ListChannels)\(\) - 将所有频道列入聊天窗口。

[RemoveChatWindowChannel](https://wow.gamepedia.com/API_RemoveChatWindowChannel)\(chatFrameIndex, "channel"\) - 使聊天频道在特定的ChatFrame中不可见（隐藏）。

[SendChatMessage](https://wow.gamepedia.com/API_SendChatMessage)\("msg",\[ "chatType",\[ "language",\[ "channel"\]\]\]\) - 发送聊天消息.

[SetChannelOwner](https://wow.gamepedia.com/API_SetChannelOwner)\("channel", "name"\) - 设置频道所有者.

[SetChannelPassword](https://wow.gamepedia.com/API_SetChannelPassword)\("channel", "password"\) - 更改当前频道的密码。

