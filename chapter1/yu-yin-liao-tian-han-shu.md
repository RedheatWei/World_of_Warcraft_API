### 语音聊天函数

###### 这些功能在[补丁2.2](https://wow.gamepedia.com/Patch_2.2)中引入。

[AddMute](https://wow.gamepedia.com/API_AddMute)\("name"\)

[AddOrDelMute](https://wow.gamepedia.com/API_AddOrDelMute)\("unit"\)

ChannelSilenceAll\(\)

ChannelSilenceVoice\(\)

ChannelUnSilenceAll\(\)

ChannelUnSilenceVoice\(\)

ChannelVoiceOff\(\)

ChannelVoiceOn\(\)

[DelMute](https://wow.gamepedia.com/API_DelMute)\("name"\)

DisplayChannelVoiceOff\(\)

DisplayChannelVoiceOn\(\)

GetActiveVoiceChannel\(\)

[GetChannelDisplayInfo](https://wow.gamepedia.com/API_GetChannelDisplayInfo)\(id\) - 根据给定的id返回通道的名称。

[GetNumVoiceSessions](https://wow.gamepedia.com/API_GetNumVoiceSessions)\(\) - 返回客户端当前所在的语音会话数。忽略“世界”类别下的语音会话数。

GetSelectedDisplayChannel\(\)

GetSelectedMute\(\)

GetMuteName\(id\) - 返回静音玩家的名称。

GetMuteStatus\("unit", "channel"\) - 返回特定单位当前是否在特定通道中静音。

GetNumMutes\(\) - 返回您当前已静音的人数。

GetVoiceCurrentSessionID\(\)

[GetVoiceSessionInfo](https://wow.gamepedia.com/API_GetVoiceSessionInfo)\(id\) - 根据给定的id返回语音会话的名称。不适用于“世界”类别下的频道。

GetVoiceStatus\("unit"\)

IsMuted\("name"\)

IsSilenced\(\)

[IsVoiceChatAllowed](https://wow.gamepedia.com/API_IsVoiceChatAllowed)\(\) - 如果服务器允许启用语音聊天，则返回1，否则返回nil

IsVoiceChatEnabled\(\) - 如果您的客户端启用了语音聊天，则返回1，否则返回nil

[SetActiveVoiceChannelBySessionID](https://wow.gamepedia.com/API_SetActiveVoiceChannelBySessionID)\(id\) - 将活动语音会话设置为给定ID的会话。

SetActiveVoiceChannel\(\)

SetSelectedDisplayChannel\(\)

SetSelectedMute\(\)

UnitIsSilenced\(\)

UnitIsTalking\(\)

VoiceChat\_ActivatePrimaryCaptureCallback\(\)

VoiceChat\_GetCurrentMicrophoneSignalLevel\(\)

VoiceChat\_IsPlayingLoopbackSound\(\)

VoiceChat\_IsRecordingLoopbackSound\(\)

VoiceChat\_PlayLoopbackSound\(\)

VoiceChat\_RecordLoopbackSound\(\)

VoiceChat\_StartCapture\(\)

VoiceChat\_StopCapture\(\)

VoiceChat\_StopPlayingLoopbackSound\(\)

VoiceChat\_StopRecordingLoopbackSound\(\)

VoiceEnumerateCaptureDevices\(\)

VoiceEnumerateOutputDevices\(\)

VoiceGetCurrentCaptureDevice\(\)

VoiceGetCurrentOutputDevice\(\)

[VoiceIsDisabledByClient](https://wow.gamepedia.com/API_VoiceIsDisabledByClient)\(\)

VoicePushToTalkStart\(\)

VoicePushToTalkStop\(\)

VoiceSelectCaptureDevice\(\)

VoiceSelectOutputDevice\(\)

