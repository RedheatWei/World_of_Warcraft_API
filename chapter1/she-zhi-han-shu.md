### 设置函数

AntiAliasingSupported\(\) -

AutoChooseCurrentGraphicsSetting\(\) -

[CombatTextSetActiveUnit](https://wow.gamepedia.com/API_CombatTextSetActiveUnit)\(unit\) - 更改COMBAT\_TEXT\_UPDATE事件触发的实体。

[GetCVar](https://wow.gamepedia.com/API_GetCVar)\("cVar"\) -返回控制台变量的当前值。

GetCVarBitfield\("cVar", index\) -

GetCVarBool\("cVar"\) - 将cvar的值返回为1或nil，而不是要求您将cvar值与“0”或“1”进行比较

[GetCVarDefault](https://wow.gamepedia.com/API_GetCVarDefault)\("cVar"\) - 返回控制台变量的默认值。

GetCVarInfo\("cVar"\) - 返回 name, defaultValue, serverStoredAccountWide, serverStoredPerCharacter

GetCVarSettingValidity\(\) -

GetCurrentGraphicsSetting\(\) -

GetCurrentRefresh\(\) -

[GetCurrentResolution](https://wow.gamepedia.com/API_GetCurrentResolution)\(\) - 获取当前屏幕分辨率的索引。

GetDefaultVideoOption\(\) -

GetDefaultVideoOptions\(\) -

GetDefaultVideoQualityOption\(\) -

GetGamma\(\)

GetGraphicsAPIs\(\) -返回一个api cVars，d3d9，d3d11等表

GetGraphicsDropdownIndexByMasterIndex\(\) -

GetMaxRenderScale \(\) -

GetMonitorAspectRatio\(\) -

GetMonitorCount\(\) -

GetMonitorName\(\) -

[GetRefreshRates](https://wow.gamepedia.com/API_GetRefreshRates)\(x\)

[GetScreenResolutions](https://wow.gamepedia.com/API_GetScreenResolutions)\(\)

GetVideoCaps\(\)

GetVideoOptions\(\)

[IsThreatWarningEnabled](https://wow.gamepedia.com/API_IsThreatWarningEnabled)\(\) - 返回当前是否应显示威胁警告。

[RegisterCVar](https://wow.gamepedia.com/API_RegisterCVar)\("cVar"\[, value\]\) - 注册变量以与[GetCVar](https://wow.gamepedia.com/API_GetCVar)和[SetCVar](https://wow.gamepedia.com/API_SetCVar)函数一起使用。

[ResetTutorials](https://wow.gamepedia.com/API_ResetTutorials)\(\) 

[SetCVar](https://wow.gamepedia.com/API_SetCVar)\("cVar", value\[, "scriptCVar"\]\) - 在config.wtf中设置变量的值

SetEuropeanNumbers\(flag\) - 将小数点分隔符设置为逗号而不是点

SetGamma\(value\)

REMOVED [SetLayoutMode](https://wow.gamepedia.com/API_SetLayoutMode)\(\)

[SetScreenResolution](https://wow.gamepedia.com/API_SetScreenResolution)\(x\)

REMOVED [ShowCloak](https://wow.gamepedia.com/API_ShowCloak)\(flag\) - 设置是否显示玩家的披风。

REMOVED [ShowHelm](https://wow.gamepedia.com/API_ShowHelm)\(flag\) - 设置是否显示玩家的头盔。

UI ShowNumericThreat\(\) - 如果应在单位帧上显示详细的威胁信息，则返回1。

REMOVED [ShowingCloak](https://wow.gamepedia.com/API_ShowingCloak)\(\) - 如果显示玩家的披风，则返回1，否则返回nil。

REMOVED [ShowingHelm](https://wow.gamepedia.com/API_ShowingHelm)\(\) - 如果显示玩家的头盔，则返回1，否则返回nil。

  


