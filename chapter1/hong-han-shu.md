### 宏函数

NOCOMBAT [CreateMacro](https://wow.gamepedia.com/API_CreateMacro)\("name", icon, "body", perCharacter, isLocal\) - 创建一个新宏. \(added in 2.0\)

CursorHasMacro\(\) - 如果光标当前正在拖动宏，则返回1. \(added in 2.0.3\)

DeleteMacro\(id or "name"\) -删除一个宏.

NOCOMBAT [EditMacro](https://wow.gamepedia.com/API_EditMacro)\(index, "name", iconIndex, "body", isLocal, perCharacter\) - 保存宏. \(added in 2.0\)

[GetMacroBody](https://wow.gamepedia.com/API_GetMacroBody)\(id or "name"\) - 返回宏的主体（宏文本）。

[GetMacroIndexByName](https://wow.gamepedia.com/API_GetMacroIndexByName)\("name"\) - 返回宏索引。

[GetMacroInfo](https://wow.gamepedia.com/API_GetMacroInfo)\(id or "name"\) - 返回“name”，“iconTexture”，“body”，isLocal。

GetMacroIcons\(table\) - 返回可用宏纹理路径的数组（但不是项目图标）。

GetMacroItemIcons\(table\) - 返回可用宏纹理路径（项目图标）的数组。

[GetNumMacros](https://wow.gamepedia.com/API_GetNumMacros)\(\) - 返回用户拥有的宏数。

[PickupMacro](https://wow.gamepedia.com/API_PickupMacro)\(id or "name"\) - 拿起一个宏按钮图标。

PROTECTED [RunMacro](https://wow.gamepedia.com/API_RunMacro)\(id or "name"\) - 运行一个宏.

PROTECTED [RunMacroText](https://wow.gamepedia.com/API_RunMacroText)\("macro"\) - 将给定的字符串解释为宏并运行它。

[SecureCmdOptionParse](https://wow.gamepedia.com/API_SecureCmdOptionParse)\("command"\) - 用于评估宏中的条件，返回适当的选择。

PROTECTED StopMacro\(\) - 停止当前正在执行的宏。





