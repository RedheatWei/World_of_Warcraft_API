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

IsOnTournamentRealm\(\) - Returns true if currently on a tournament realm, nil otherwise.

[IsRightAltKeyDown](https://wow.gamepedia.com/API_IsRightAltKeyDown)\(\) - Returns true if the right alt key is currently depressed.

[IsRightControlKeyDown](https://wow.gamepedia.com/API_IsRightControlKeyDown)\(\) - Returns true if the right control key is currently depressed.

[IsRightShiftKeyDown](https://wow.gamepedia.com/API_IsRightShiftKeyDown)\(\) - Returns true if the right shift key is currently depressed.

[IsShiftKeyDown](https://wow.gamepedia.com/API_IsShiftKeyDown)\(\) - Returns true if the shift key is currently depressed.

IsStereoVideoAvailable\(\) - added in 3.0.8

[IsWindowsClient](https://wow.gamepedia.com/API_IsWindowsClient)\(\) - Returns true if WoW is being run on Windows.

OpeningCinematic\(\) - Shows the opening movie for a player's race

[PlayMusic](https://wow.gamepedia.com/API_PlayMusic)\(\) - Plays the specified mp3.

[PlaySound](https://wow.gamepedia.com/API_PlaySound)\(\) - Plays the specified built-in sound effect.

[PlaySoundFile](https://wow.gamepedia.com/API_PlaySoundFile)\(\) - Plays the specified sound file.

HW [ReloadUI](https://wow.gamepedia.com/API_ReloadUI)\(\) - Reloads the UI from source files

[RepopMe](https://wow.gamepedia.com/API_RepopMe)\(\) - The "Release Spirit" button. Sends you to the graveyard when dead.

[RequestTimePlayed](https://wow.gamepedia.com/API_RequestTimePlayed)\(\) - Request a summary of time played from the server.

[RestartGx](https://wow.gamepedia.com/API_RestartGx)\(\) - Restarts the graphical engine. Needed for things such as resolution changes to take effect.

[RunScript](https://wow.gamepedia.com/API_RunScript)\("script"\) - Execute "script" as a block of Lua code.

[Screenshot](https://wow.gamepedia.com/API_Screenshot)\(\) - Takes a screenshot.

UI [SecondsToTime](https://wow.gamepedia.com/API_SecondsToTime) - Converts a number of seconds into a readable days / hours / etc. formatted string.

[seterrorhandler](https://wow.gamepedia.com/API_seterrorhandler)\(function\) - Set the error handler to the given parameter.

StopCinematic\(\)

[StopMusic](https://wow.gamepedia.com/API_StopMusic)\(\) - Stops the currently playing mp3.

UI [UIParentLoadAddOn](https://wow.gamepedia.com/API_UIParentLoadAddOn)\("AddOnName"\) - Loads or Reloads the specified AddOn, and pops up an error message if it fails to load for any reason.

REMOVED UI [TakeScreenshot](https://wow.gamepedia.com/API_TakeScreenshot)\(\) - Takes a screenshot.

UI [\_ERRORMESSAGE](https://wow.gamepedia.com/API_ERRORMESSAGE)\(value\) - Displays the script error dialog with optional text

debuginfo\(\) - Output win32 debug text. Freeware debug message viewer:

[DebugView](http://www.sysinternals.com/Utilities/DebugView.html)\(Has no effect on live server.\)

UI [message](https://wow.gamepedia.com/API_message)\("text"\) - Displays a message box with your text message and an "Okay" button.

