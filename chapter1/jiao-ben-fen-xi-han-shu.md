### 脚本分析函数

###### 注意：默认情况下禁用CPU分析，因为它有一些开销。CPU分析由scriptProfile cvar控制，它在会话中持续存在，并在UI重新加载后生效。内存分析始终可用。补丁2.1中添加了这些功能。

[GetAddOnCPUUsage](https://wow.gamepedia.com/API_GetAddOnCPUUsage)\(index or "name"\) - 返回指定AddOn使用的总时间。这将返回由UpdateAddOnCPUUsage（）计算的缓存值。

GetAddOnMemoryUsage\(index or "name"\) - 查询插件的内存使用（以K为单位，精度为1字节） - 返回由UpdateAddOnMemoryUsage（）计算的缓存值。

GetEventCPUUsage\(\["event"\]\) - 返回已使用的时间和触发指定事件的次数。如果省略'event'，则时间和计数将是所有事件的总计。

[GetFrameCPUUsage](https://wow.gamepedia.com/API_GetFrameCPUUsage)\(frame\[, includeChildren\]\) - 返回任何帧的脚本处理程序使用的时间和函数调用的数量。如果'includeChildren'为真或省略，则时间和通话计数也将包括所有帧的子项的处理程序。

GetFunctionCPUUsage\(function\[, includeSubroutines\]\) - 返回使用的时间和调用指定函数的次数。如果'includeSubroutines'为真或省略，则时间包括函数花费的时间和函数调用的子程序。如果它是假的，那么时间只是代码在函数本身中实际花费的时间。

GetScriptCPUUsage\(\) -返回脚本系统使用的总时间

ResetCPUUsage\(\) - 将所有CPU分析统计信息重置为零。

UpdateAddOnCPUUsage\(\) - 扫描分析数据并更新每个插件统计信息

UpdateAddOnMemoryUsage\(\) - 扫描内存分析数据并更新每个附加组件统计信息

