### 设备管理函数

###### 设备管理已添加到[补丁3.1.2](https://wow.gamepedia.com/Patch_3.1.2)中的UI中。

CanUseEquipmentSets\(\)

DeleteEquipmentSet\("name"\) - 遗忘一套设备.

EquipmentSetContainsLockedItems\("name"\) - 检查集合中的某些项目当前是否已锁定（待处理的客户端/服务器交互）。

EquipmentManagerIgnoreSlotForSave\(slot\) - 标记保存设备集时要忽略的插槽。

EquipmentManagerIsSlotIgnoredForSave\(\) -

EquipmentManagerUnignoreSlotForSave\(slot\) - 保存设备集时从插槽中删除忽略标志。

EquipmentManagerClearIgnoredSlotsForSave\(\) - 保存设备集时，从所有插槽中删除忽略标志。

UI [EquipmentManager\_UnpackLocation](https://wow.gamepedia.com/API_EquipmentManager_UnpackLocation)\(location\) - 解包位置整数以确定实际库存位置。

GetContainerItemEquipmentSetInfo\(\)

[GetNumEquipmentSets](https://wow.gamepedia.com/API_GetNumEquipmentSets)\(\) - 返回已保存设备组的数量。

UI GetEquipmentSetIconInfo\(index\) - 返回有关可用图标的信息。

GetEquipmentSetIgnoreSlots\(\)

[GetEquipmentSetInfo](https://wow.gamepedia.com/API_GetEquipmentSetInfo)\(index\) - 返回有关设备集的信息。

[GetEquipmentSetInfoByName](https://wow.gamepedia.com/API_GetEquipmentSetInfoByName)\("name"\) - 返回有关设备集的信息。

[GetEquipmentSetItemIDs](https://wow.gamepedia.com/API_GetEquipmentSetItemIDs)\("name"\[, returnTable\]\) - 使用物品ID填充并返回一个表。

[GetEquipmentSetLocations](https://wow.gamepedia.com/API_GetEquipmentSetLocations)\("name"\[, returnTable\]\) - 填充并返回包含项位置的表。

ModifyEquipmentSet\(\)

[PickupEquipmentSet](https://wow.gamepedia.com/API_PickupEquipmentSet)\(index\) - 在光标上放置一个设备。

[PickupEquipmentSetByName](https://wow.gamepedia.com/API_PickupEquipmentSetByName)\("name"\) - 在光标上放置一个设备。

[SaveEquipmentSet](https://wow.gamepedia.com/API_SaveEquipmentSet)\("name", iconIndex\) - 将当前配备的物品保存在一组中。

NOCOMBAT [UseEquipmentSet](https://wow.gamepedia.com/API_UseEquipmentSet)\("name"\) - 配备一套设备。

