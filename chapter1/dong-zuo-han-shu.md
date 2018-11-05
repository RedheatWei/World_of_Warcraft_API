### 动作函数

###### 这些功能是使用动作按钮操作的功能（常规玩家动作可能在下面的“[活动功能”](https://wow.gamepedia.com/World_of_Warcraft_API#Activity_Functions)部分中）。

PROTECTED UI [ActionButtonDown](https://wow.gamepedia.com/API_ActionButtonDown)\(id\) - 按指定的操作按钮。（2.0受保护）

PROTECTED UI [ActionButtonUp](https://wow.gamepedia.com/API_ActionButtonUp)\(id\) - 释放指定的操作按钮。（2.0受保护）

[ActionHasRange](https://wow.gamepedia.com/API_ActionHasRange)\(slot\) - 确定指定的操作是否是范围限制（如果是则为1，否则为nil）

PROTECTED [CameraOrSelectOrMoveStart](https://wow.gamepedia.com/API_CameraOrSelectOrMoveStart)\(\) - 在3D世界中开始“左键单击”。（1.10  - 受保护）

PROTECTED [CameraOrSelectOrMoveStop](https://wow.gamepedia.com/API_CameraOrSelectOrMoveStop)\(\[stickyFlag\]\) - 结束3D世界中的“左键单击”。（1.10  - 受保护）

NOCOMBAT [ChangeActionBarPage](https://wow.gamepedia.com/API_ChangeActionBarPage)\(page\) - 更改当前操作栏页面。

[GetActionBarPage](https://wow.gamepedia.com/API_GetActionBarPage)\(\) - 返回当前操作栏页面。CURRENT\_ACTIONBAR\_PAGE已过时。

[GetActionBarToggles](https://wow.gamepedia.com/API_GetActionBarToggles)\(\) - 返回每个操作栏的切换。

[GetActionCharges](https://wow.gamepedia.com/API_GetActionCharges)\(slot\) - 返回有关能量累积玩家能量充能的信息。

[GetActionCooldown](https://wow.gamepedia.com/API_GetActionCooldown)\(slot\) - 这将返回指定动作按钮的冷却值。

[GetActionCount](https://wow.gamepedia.com/API_GetActionCount)\(slot\) - 获取动作按钮的计数（绷带/药水/等），如果没有则返回0或不适用。

[GetActionInfo](https://wow.gamepedia.com/API_GetActionInfo)\(slot\) - 返回类型，id，子类型。

[GetActionText](https://wow.gamepedia.com/API_GetActionText)\(slot\) - 获取操作的文本标签（宏等），如果没有则返回nil。

[GetActionTexture](https://wow.gamepedia.com/API_GetActionTexture)\(slot\) -获取指定操作的纹理路径。

[GetBonusBarOffset](https://wow.gamepedia.com/API_GetBonusBarOffset)\(\) - 确定要显示的额外动作条。

[GetMouseButtonClicked](https://wow.gamepedia.com/API_GetMouseButtonClicked)\(\) -返回触发鼠标按下/向上/单击/双击事件的按钮的名称。（在2.0.3中添加）

[GetPossessInfo](https://wow.gamepedia.com/API_GetPossessInfo)\(index\) - 返回纹理，名称，是否启用。

[HasAction](https://wow.gamepedia.com/API_HasAction)\(slot\) - 如果玩家在指定的按钮中有动作，则返回1，否则返回nil。

[IsActionInRange](https://wow.gamepedia.com/API_IsActionInRange)\(slot\) - 测试一个动作是否在范围内（1 =是，0 =否，nil =不适用）。

[IsAttackAction](https://wow.gamepedia.com/API_IsAttackAction)\(slot\) - 如果动作按钮是“攻击”动作（在战斗期间闪烁）则返回1，否则返回零。

[IsAutoRepeatAction](https://wow.gamepedia.com/API_IsAutoRepeatAction)\(slot\) - 如果某个操作是自动重复，则返回1，否则返回nil。

[IsCurrentAction](https://wow.gamepedia.com/API_IsCurrentAction)\(slot\) - 如果某个操作是当前正在进行的操作，则返回1，否则返回nil。

[IsConsumableAction](https://wow.gamepedia.com/API_IsConsumableAction)\(slot\) -如果某个动作按钮是消耗品（即有一个计数），则返回1，否则返回零。

[IsEquippedAction](https://wow.gamepedia.com/API_IsEquippedAction)\(slot\) - 如果配备了动作（即连接到必须装备的物品），则返回1，否则返回零。

[IsUsableAction](https://wow.gamepedia.com/API_IsUsableAction)\(slot\) - 如果当前可以使用某个操作，则返回1，否则返回nil。

[PetHasActionBar](https://wow.gamepedia.com/API_PetHasActionBar)\(\) - 确定玩家是否有带动作栏的宠物。

NOCOMBAT [PickupAction](https://wow.gamepedia.com/API_PickupAction)\(slot\) - 从指定的快速栏槽中拖出一个动作并将其保持在光标上。

NOCOMBAT [PickupPetAction](https://wow.gamepedia.com/API_PickupPetAction)\(slot\) -将指定宠物操作栏插槽中的操作拖动到光标中。

[PlaceAction](https://wow.gamepedia.com/API_PlaceAction)\(slot\) - 将光标中的操作拖放到指定的快捷方式插槽中。

[SetActionBarToggles](https://wow.gamepedia.com/API_SetActionBarToggles)\(show1, show2, show3, show4\[, alwaysShow\]\) - 为每个操作栏设置show toggle  - 在1.12中添加'alwaysShow'

StopAttack\(\) - 如果当前处于活动状态，则关闭自动攻击。没有效果是因为玩家目前没有自动攻击活动。

PROTECTED [TurnOrActionStart](https://wow.gamepedia.com/API_TurnOrActionStart)\(\) - 在3D世界中开始“右键单击”。（1.10  - 受保护）

PROTECTED [TurnOrActionStop](https://wow.gamepedia.com/API_TurnOrActionStop)\(\) - 在3D世界中停止“右键单击”。（1.10  - 受保护）

PROTECTED [UseAction](https://wow.gamepedia.com/API_UseAction)\(slot\[, checkCursor\[, onSelf\]\]\) - 这指示接口使用与指定ID相关联的操作，可选地在玩家上（无论目标）（2.0  - 受保护）。

