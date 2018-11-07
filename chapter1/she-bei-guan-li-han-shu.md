### 设备管理函数

###### 设备管理已添加到[补丁3.1.2](https://wow.gamepedia.com/Patch_3.1.2)中的UI中。

CanUseEquipmentSets\(\)

DeleteEquipmentSet\("name"\) - Forgets an equipment set.

EquipmentSetContainsLockedItems\("name"\) - Checks if some of the items in the set are currently locked \(pending client/server interaction\).

EquipmentManagerIgnoreSlotForSave\(slot\) - flags the slot to be ignored when saving an equipment set.

EquipmentManagerIsSlotIgnoredForSave\(\) -

EquipmentManagerUnignoreSlotForSave\(slot\) - removes the ignore flag from a slot when saving an equipment set.

EquipmentManagerClearIgnoredSlotsForSave\(\) - removes the ignore flag from all slots when saving an equipment set.

UI [EquipmentManager\_UnpackLocation](https://wow.gamepedia.com/API_EquipmentManager_UnpackLocation)\(location\) - Unpacks a location integer to determine the actual inventory location.

GetContainerItemEquipmentSetInfo\(\)

[GetNumEquipmentSets](https://wow.gamepedia.com/API_GetNumEquipmentSets)\(\) - Returns the number of saved equipment sets.

UI GetEquipmentSetIconInfo\(index\) - Returns information about available icons.

GetEquipmentSetIgnoreSlots\(\)

[GetEquipmentSetInfo](https://wow.gamepedia.com/API_GetEquipmentSetInfo)\(index\) - Returns information about an equipment set.

[GetEquipmentSetInfoByName](https://wow.gamepedia.com/API_GetEquipmentSetInfoByName)\("name"\) - Returns information about an equipment set.

[GetEquipmentSetItemIDs](https://wow.gamepedia.com/API_GetEquipmentSetItemIDs)\("name"\[, returnTable\]\) - Populates and returns a table with the item IDs.

[GetEquipmentSetLocations](https://wow.gamepedia.com/API_GetEquipmentSetLocations)\("name"\[, returnTable\]\) - Populates and returns a table with the item locations.

ModifyEquipmentSet\(\)

[PickupEquipmentSet](https://wow.gamepedia.com/API_PickupEquipmentSet)\(index\) - Places an equipment set on the cursor.

[PickupEquipmentSetByName](https://wow.gamepedia.com/API_PickupEquipmentSetByName)\("name"\) - Places an equipment set on the cursor.

[SaveEquipmentSet](https://wow.gamepedia.com/API_SaveEquipmentSet)\("name", iconIndex\) - Saves the currently equipped items in a set.

NOCOMBAT [UseEquipmentSet](https://wow.gamepedia.com/API_UseEquipmentSet)\("name"\) - Equips an equipment set.

