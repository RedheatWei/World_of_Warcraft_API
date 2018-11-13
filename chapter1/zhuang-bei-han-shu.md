### 装备函数

这些功能管理您的“装备”，即装备的物品。也可以查看[容器/包裹函数](https://wow.gamepedia.com/World_of_Warcraft_API#Container.2FBag_Functions)和[银行函数](https://wow.gamepedia.com/World_of_Warcraft_API#Bank_Functions)

[AutoEquipCursorItem](https://wow.gamepedia.com/API_AutoEquipCursorItem)\(\) - 使光标上的装备配备。

[BankButtonIDToInvSlotID](https://wow.gamepedia.com/API_BankButtonIDToInvSlotID)\(buttonID, isBag\) - 根据装备槽ID返回银行按钮或包的ID号。

[CancelPendingEquip](https://wow.gamepedia.com/API_CancelPendingEquip)\(index\) - 此功能用于取消待定装备。

[ConfirmBindOnUse](https://wow.gamepedia.com/API_ConfirmBindOnUse)\(\)

[ContainerIDToInventoryID](https://wow.gamepedia.com/API_ContainerIDToInventoryID)\([bagID](https://wow.gamepedia.com/BagId)\)

[CursorCanGoInSlot](https://wow.gamepedia.com/API_CursorCanGoInSlot)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 如果光标当前持有的项目可以进入给定的装备（装备）插槽，则返回true。

[EquipCursorItem](https://wow.gamepedia.com/API_EquipCursorItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\)

[EquipPendingItem](https://wow.gamepedia.com/API_EquipPendingItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 装备指定装备槽中当前待处理的装备绑定或拾取绑定项目。（内置 - 不要使用。）

[GetAverageItemLevel](https://wow.gamepedia.com/API_GetAverageItemLevel)\(\) - 返回角色的当前实装和虚装装等.

[GetInventoryAlertStatus](https://wow.gamepedia.com/API_GetInventoryAlertStatus)\(index\) - 返回描述装备项目“状态”的几个代码之一。

[GetInventoryItemBroken](https://wow.gamepedia.com/API_GetInventoryItemBroken)\("unit", invSlot\) - 确定装备是否已损坏（无耐久性）。

[GetInventoryItemCooldown](https://wow.gamepedia.com/API_GetInventoryItemCooldown)\("unit", invSlot\) - 获取装备的冷却时间信息。

[GetInventoryItemCount](https://wow.gamepedia.com/API_GetInventoryItemCount)\("unit", invSlot\) - 确定装备槽中项目的数量。

[GetInventoryItemDurability](https://wow.gamepedia.com/API_GetInventoryItemDurability)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 返回装备的最大和剩余耐久性点。

REMOVED [GetInventoryItemGems](https://wow.gamepedia.com/API_GetInventoryItemGems)\(invSlot\) - 返回指定装备槽装备中插入的宝石的项ID。

[GetInventoryItemID](https://wow.gamepedia.com/API_GetInventoryItemID)\("unit", invSlot\) - 返回指定装备槽中项目装备ID。

[GetInventoryItemLink](https://wow.gamepedia.com/API_GetInventoryItemLink)\("unit", invSlot\) - 返回装备项目的[itemLink](https://wow.gamepedia.com/ItemLink).

[GetInventoryItemQuality](https://wow.gamepedia.com/API_GetInventoryItemQuality)\("unit", invSlot\) - 返回装备项目的品质。

[GetInventoryItemTexture](https://wow.gamepedia.com/API_GetInventoryItemTexture)\("unit", invSlot\) - 返回装备项目的纹理。

[GetInventorySlotInfo](https://wow.gamepedia.com/API_GetInventorySlotInfo)\([invSlotName](https://wow.gamepedia.com/InventorySlotName)\) - 获取指定装备槽的信息（插槽ID和纹理）

[GetWeaponEnchantInfo](https://wow.gamepedia.com/API_GetWeaponEnchantInfo)\(\) - 返回有关主要武器附魔和副武器附魔的信息。

[HasWandEquipped](https://wow.gamepedia.com/API_HasWandEquipped)\(\) - 如果配备了魔杖，则返回1，否则返回false。

[IsInventoryItemLocked](https://wow.gamepedia.com/API_IsInventoryItemLocked)\(id\) - 返回装备是否被锁定，通常是等待待处理的操作。

[OffhandHasWeapon](https://wow.gamepedia.com/API_OffhandHasWeapon)\(\) - 确定你的副手是否携带武器。

[PickupBagFromSlot](https://wow.gamepedia.com/API_PickupBagFromSlot)\(slot\) - 从指定的插槽中取出物品，将其放在光标中。如果已拾取某个项目，则会将该项目放入指定的插槽中，并根据需要交换项目。

[PickupInventoryItem](https://wow.gamepedia.com/API_PickupInventoryItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 从玩家的磨损库存中“挑选”一件物品。

UpdateInventoryAlertStatus\(\)

PROTECTED [UseInventoryItem](https://wow.gamepedia.com/API_UseInventoryItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 使用指定插槽中的物品.

