### 系统函数

[ConsoleExec](https://wow.gamepedia.com/API_ConsoleExec)\("command"\) - 执行控制台命令。

DetectWowMouse\(\) - 试图探测魔兽世界的MMO鼠标。

[GetBuildInfo](https://wow.gamepedia.com/API_GetBuildInfo)\(\) - 返回有关当前客户端构建的信息

geterrorhandler\(\) - 返回当前设置的错误处理程序。

GetCurrentKeyBoardFocus\(\) - 返回当前处理键盘事件的\[editbox\]小部件。

REMOVED [GetExistingLocales](https://wow.gamepedia.com/API_GetExistingLocales)\(\) - 返回已安装语言包的列表。

[GetFramerate](https://wow.gamepedia.com/API_GetFramerate)\(\) - 返回当前帧速率（全精度）

[GetGameTime](https://wow.gamepedia.com/API_GetGameTime)\(\) - 返回游戏中的时间。

[GetLocale](https://wow.gamepedia.com/API_GetLocale)\(\) - 返回客户端区域设置，例如'enUS'。

[GetCursorPosition](https://wow.gamepedia.com/API_GetCursorPosition)\(\) - 返回光标在屏幕上的位置。

[GetNetStats](https://wow.gamepedia.com/API_GetNetStats)\(\) - 获取带宽和延迟网络信息。

[GetRealmName](https://wow.gamepedia.com/API_GetRealmName)\(\) - 返回用户登录的服务器的名称

[GetScreenHeight](https://wow.gamepedia.com/API_GetScreenHeight)\(\) - 以像素为单位返回窗口的高度。

[GetScreenWidth](https://wow.gamepedia.com/API_GetScreenWidth)\(\) - 返回窗口的宽度（以像素为单位）。

UI [GetText](https://wow.gamepedia.com/API_GetText)\(\) - 用于本地化一些客户端文本。

[GetTime](https://wow.gamepedia.com/API_GetTime)\(\) - 以秒为单位返回系统正常运行时间（毫秒精度）。

[IsAltKeyDown](https://wow.gamepedia.com/API_IsAltKeyDown)\(\) - 如果当前按下alt键，则返回true。

InCinematic\(\)

[IsControlKeyDown](https://wow.gamepedia.com/API_IsControlKeyDown)\(\) - 如果当前按下控制键，则返回true。

IsDebugBuild\(\) - ?

IsDesaturateSupported\(\) - ?

[IsLeftAltKeyDown](https://wow.gamepedia.com/API_IsLeftAltKeyDown)\(\) - 如果当前按下左Alt键，则返回true。

[IsLeftControlKeyDown](https://wow.gamepedia.com/API_IsLeftControlKeyDown)\(\) - 如果当前按下左ctrl键，则返回true。

[IsLeftShiftKeyDown](https://wow.gamepedia.com/API_IsLeftShiftKeyDown)\(\) - 如果当前按下左shift键，则返回true。

[IsLinuxClient](https://wow.gamepedia.com/API_IsLinuxClient)\(\) - Boolean  - 如果在Linux上运行WoW，则返回true。

IsLoggedIn\(\) - 在PLAYER\_LOGIN事件触发之前返回nil，之后返回1。

[IsMacClient](https://wow.gamepedia.com/API_IsMacClient)\(\) - 如果在Mac上运行WoW，则返回true。

IsOnTournamentRealm\(\) - 如果当前在锦标赛领域，则返回true，否则返回nil。

[IsRightAltKeyDown](https://wow.gamepedia.com/API_IsRightAltKeyDown)\(\) - 如果当前按下右Alt键，则返回true。

[IsRightControlKeyDown](https://wow.gamepedia.com/API_IsRightControlKeyDown)\(\) - 如果当前按下右控制键，则返回true。

[IsRightShiftKeyDown](https://wow.gamepedia.com/API_IsRightShiftKeyDown)\(\) - 如果当前按下右移键，则返回true。

[IsShiftKeyDown](https://wow.gamepedia.com/API_IsShiftKeyDown)\(\) - 如果当前按下shift键，则返回true。

IsStereoVideoAvailable\(\) - 添加于3.0.8

[IsWindowsClient](https://wow.gamepedia.com/API_IsWindowsClient)\(\) - 如果在Windows上运行WoW，则返回true。

OpeningCinematic\(\) - 显示玩家比赛的开场电影

[PlayMusic](https://wow.gamepedia.com/API_PlayMusic)\(\) - 播放指定的mp3。

[PlaySound](https://wow.gamepedia.com/API_PlaySound)\(\) - 播放指定的内置音效。

[PlaySoundFile](https://wow.gamepedia.com/API_PlaySoundFile)\(\) - 播放指定的声音文件。

HW [ReloadUI](https://wow.gamepedia.com/API_ReloadUI)\(\) - 从源文件重新加载UI

[RepopMe](https://wow.gamepedia.com/API_RepopMe)\(\) - “释放灵魂”按钮。死后会把你送到墓地。

[RequestTimePlayed](https://wow.gamepedia.com/API_RequestTimePlayed)\(\) - 请求从服务器播放的时间摘要。

[RestartGx](https://wow.gamepedia.com/API_RestartGx)\(\) - 重新启动图形引擎。需要诸如分辨率更改才能生效。

[RunScript](https://wow.gamepedia.com/API_RunScript)\("script"\) - 执行“script”作为Lua代码块。

[Screenshot](https://wow.gamepedia.com/API_Screenshot)\(\) - 截图。

UI [SecondsToTime](https://wow.gamepedia.com/API_SecondsToTime) - 将数秒转换为可读日/小时/等格式化字符串。

[seterrorhandler](https://wow.gamepedia.com/API_seterrorhandler)\(function\) - 将错误处理程序设置为给定参数。

StopCinematic\(\)

[StopMusic](https://wow.gamepedia.com/API_StopMusic)\(\) - 停止当前播放的mp3。

UI [UIParentLoadAddOn](https://wow.gamepedia.com/API_UIParentLoadAddOn)\("AddOnName"\) - 加载或重新加载指定的AddOn，如果因任何原因无法加载，则会弹出错误消息。

REMOVED UI [TakeScreenshot](https://wow.gamepedia.com/API_TakeScreenshot)\(\) - 截图

UI [\_ERRORMESSAGE](https://wow.gamepedia.com/API_ERRORMESSAGE)\(value\) - 显示带有可选文本的脚本错误对话框

debuginfo\(\) - 输出win32调试文本。免费软件调试消息查看器： [DebugView](http://www.sysinternals.com/Utilities/DebugView.html)\(对实时服务器没有影响.\)

UI [message](https://wow.gamepedia.com/API_message)\("text"\) - 显示带有消息和“正常”按钮的消息框。

