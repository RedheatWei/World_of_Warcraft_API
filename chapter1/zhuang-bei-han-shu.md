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

[GetAverageItemLevel](https://wow.gamepedia.com/API_GetAverageItemLevel)\(\) - Return the character's current average iLevel and current average iLevel equipped.

[GetInventoryAlertStatus](https://wow.gamepedia.com/API_GetInventoryAlertStatus)\(index\) - Returns one of several codes describing the "status" of an equipped item.

[GetInventoryItemBroken](https://wow.gamepedia.com/API_GetInventoryItemBroken)\("unit", invSlot\) - Determine if an inventory item is broken \(no durability\).

[GetInventoryItemCooldown](https://wow.gamepedia.com/API_GetInventoryItemCooldown)\("unit", invSlot\) - Get cooldown information for an inventory item.

[GetInventoryItemCount](https://wow.gamepedia.com/API_GetInventoryItemCount)\("unit", invSlot\) - Determine the quantity of an item in an inventory slot.

[GetInventoryItemDurability](https://wow.gamepedia.com/API_GetInventoryItemDurability)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - Returns the maximum and remaining durability points for an inventory item.

REMOVED [GetInventoryItemGems](https://wow.gamepedia.com/API_GetInventoryItemGems)\(invSlot\) - Returns item ids of the gems socketed in the item in the specified inventory slot.

[GetInventoryItemID](https://wow.gamepedia.com/API_GetInventoryItemID)\("unit", invSlot\) - Returns the item id of the item in the specified inventory slot.

[GetInventoryItemLink](https://wow.gamepedia.com/API_GetInventoryItemLink)\("unit", invSlot\) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for an inventory \(equipped\) item.

[GetInventoryItemQuality](https://wow.gamepedia.com/API_GetInventoryItemQuality)\("unit", invSlot\) - Return the quality of an inventory item.

[GetInventoryItemTexture](https://wow.gamepedia.com/API_GetInventoryItemTexture)\("unit", invSlot\) - Return the texture for an inventory item.

[GetInventorySlotInfo](https://wow.gamepedia.com/API_GetInventorySlotInfo)\([invSlotName](https://wow.gamepedia.com/InventorySlotName)\) - Get the info for a named inventory slot \(slot ID and texture\)

[GetWeaponEnchantInfo](https://wow.gamepedia.com/API_GetWeaponEnchantInfo)\(\) - Return information about main and offhand weapon enchantments.

[HasWandEquipped](https://wow.gamepedia.com/API_HasWandEquipped)\(\) - Returns 1 if a wand is equipped, false otherwise.

[IsInventoryItemLocked](https://wow.gamepedia.com/API_IsInventoryItemLocked)\(id\) - Returns whether an inventory item is locked, usually as it awaits pending action.

[OffhandHasWeapon](https://wow.gamepedia.com/API_OffhandHasWeapon)\(\) - Determine if your offhand carries a weapon.

[PickupBagFromSlot](https://wow.gamepedia.com/API_PickupBagFromSlot)\(slot\) - Picks up the bag from the specified slot, placing it in the cursor. If an item is already picked up, this places the item into the specified slot, swapping the items if needed.

[PickupInventoryItem](https://wow.gamepedia.com/API_PickupInventoryItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - "Picks up" an item from the player's worn inventory.

UpdateInventoryAlertStatus\(\)

PROTECTED [UseInventoryItem](https://wow.gamepedia.com/API_UseInventoryItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - Use an item in a specific inventory slot.

  


