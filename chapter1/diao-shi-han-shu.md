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

FrameXML\_Debug\(flag\) - Sets FrameXML logging state which is output to /WoW Folder/Logs/FrameXML.log

UI [getprinthandler](https://wow.gamepedia.com/API_getprinthandler)\(\) - Returns the function currently handling print\(\) output.

UI [print](https://wow.gamepedia.com/API_print)\(...\) - Calls the current print output handler with the provided values; by default printing the values to the default chat frame.

UI [setprinthandler](https://wow.gamepedia.com/API_setprinthandler)\(func\) - Changes the function handling print\(\) output.

UI tostringall\(...\) - Converts and returns the passed arguments to string.

[wipe](https://wow.gamepedia.com/API_wipe)\(table\) - removes all key/value pairs from a table; also available as table.wipe\(\).

