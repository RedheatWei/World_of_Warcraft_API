### 沟通函数

###### 这些是与其他玩家沟通的功能。另请参见“[通道函数](https://wow.gamepedia.com/World_of_Warcraft_API#Channel_Functions)”和“[聊天窗口函数](https://wow.gamepedia.com/World_of_Warcraft_API#Chat_Window_Functions)”部分。

[DoEmote](https://wow.gamepedia.com/API_DoEmote)\("emote",\["target"\]\) - 执行语音表情。

[GetDefaultLanguage](https://wow.gamepedia.com/API_GetDefaultLanguage)\("unit"\) - 返回登录后设备正在说话的默认语言。

[GetLanguageByIndex](https://wow.gamepedia.com/API_GetLanguageByIndex)\(index\) - 返回索引指定的语言。

[GetNumLanguages](https://wow.gamepedia.com/API_GetNumLanguages)\(\) - 返回角色可以说的语言数量（在2.4中重命名，以前输入错误的GetNumLaguages）。

[RandomRoll](https://wow.gamepedia.com/API_RandomRoll)\(low, high\) - 两个值之间是否随意滚动。

[SendAddonMessage](https://wow.gamepedia.com/API_SendAddonMessage)\("prefix", "text", "type" \[, "player"\]\) - 向隐藏的AddOn频道发送消息。- 在1.12中添加

[SendChatMessage](https://wow.gamepedia.com/API_SendChatMessage)\("msg",\[ "chatType",\[ "language",\[ "channel"\]\]\]\) - 发送聊天消息。

