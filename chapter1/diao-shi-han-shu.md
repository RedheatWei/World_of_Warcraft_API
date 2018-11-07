### 调试函数

AreDangerousScriptsAllowed\(?\) -

SetAllowDangerousScripts\(?\) -

ConsoleAddMessage\(message\) - added in 3.0.8

debugbreak\(?\) -

debugdump\(?\) -

debuginfo\(?\) -

debugload\(?\) -

debuglocals\(?\) -

debugprint\(?\) -

[debugprofilestart](https://wow.gamepedia.com/API_debugprofilestart)\(\) - 在调试期间启动一个用于分析的计时器。

[debugprofilestop](https://wow.gamepedia.com/API_debugprofilestop)\(\) - 返回自上次调用debugprofilestart\(\)以来的时间（以毫秒为单位）

[debugstack](https://wow.gamepedia.com/API_debugstack)\(start, count1, count2\) - 返回当前调用堆栈的字符串表示形式（从1.9开始）

debugtimestamp\(?\) -

FrameXML\_Debug\(flag\) - 设置输出到/ WoW Folder/Logs/FrameXML.log的FrameXML日志记录状态

UI [getprinthandler](https://wow.gamepedia.com/API_getprinthandler)\(\) - 返回当前处理print\(\)输出的函数。

UI [print](https://wow.gamepedia.com/API_print)\(...\) - 使用提供的值调用当前打印输出处理程序;默认情况下，将值打印到默认聊天框架。

UI [setprinthandler](https://wow.gamepedia.com/API_setprinthandler)\(func\) - 更改函数处理print\(\)输出。

UI tostringall\(...\) - 将传递的参数转换并返回给string。

[wipe](https://wow.gamepedia.com/API_wipe)\(table\) - 从表中删除所有键/值对;也可用作table.wipe\(\)。

