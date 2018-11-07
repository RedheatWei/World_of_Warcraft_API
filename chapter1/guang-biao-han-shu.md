### 光标函数

[AutoEquipCursorItem](https://wow.gamepedia.com/API_AutoEquipCursorItem)\(\) - 使光标上的装备配备上。

[ClearCursor](https://wow.gamepedia.com/API_ClearCursor)\(\) - 清除光标从光标拖动的任何项目。- 在1.12中添加

[CursorCanGoInSlot](https://wow.gamepedia.com/API_CursorCanGoInSlot)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 如果光标当前持有的项目可以进入给定的库存（设备）插槽，则返回true。

[CursorHasItem](https://wow.gamepedia.com/API_CursorHasItem)\(\) - 如果光标当前包含项目，则返回true。

CursorHasMoney\(\) - 如果光标当前持有货币，则返回true。

CursorHasSpell\(\) - 如果光标当前持有一个技能，则返回true。

[DeleteCursorItem](https://wow.gamepedia.com/API_DeleteCursorItem)\(\) - 销毁光标上的项目。

[DropCursorMoney](https://wow.gamepedia.com/API_DropCursorMoney)\(\) - 减少光标持有的金额。

[DropItemOnUnit](https://wow.gamepedia.com/API_DropItemOnUnit)\("unit"\) - 将项目从光标拖放到单元上。

[EquipCursorItem](https://wow.gamepedia.com/API_EquipCursorItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - Equips the currently picked up item to a specific inventory slot.

[GetCursorInfo](https://wow.gamepedia.com/API_GetCursorInfo)\(\) - Returns information about what the cursor is holding.

[GetCursorMoney](https://wow.gamepedia.com/API_GetCursorMoney) - Returns the amount of money held by the cursor.

[GetCursorPosition](https://wow.gamepedia.com/API_GetCursorPosition)\(\) - Returns the cursor's position on the screen.

[HideRepairCursor](https://wow.gamepedia.com/API_HideRepairCursor)\(\) - Hides the repair cursor.

[InRepairMode](https://wow.gamepedia.com/API_InRepairMode)\(\) - Returns true if your cursor is in repair mode.

NOCOMBAT [PickupAction](https://wow.gamepedia.com/API_PickupAction)\(slot\) - Drags an action out of the specified quickbar slot and holds it on the cursor.

[PickupBagFromSlot](https://wow.gamepedia.com/API_PickupBagFromSlot)\(slot\) - Picks up the bag from the specified slot, placing it in the cursor. If an item is already picked up, this places the item into the specified slot, swapping the items if needed.

[PickupContainerItem](https://wow.gamepedia.com/API_PickupContainerItem)\([bagID](https://wow.gamepedia.com/BagId), slot\) -

[PickupInventoryItem](https://wow.gamepedia.com/API_PickupInventoryItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - "Picks up" an item from the player's worn inventory.

[PickupItem](https://wow.gamepedia.com/API_PickupItem)\(itemId or "itemString" or "itemName" or "itemLink"\)

NOCOMBAT [PickupMacro](https://wow.gamepedia.com/API_PickupMacro)\("macroName" or index\) - Places the specified macro onto the cursor.

[PickupMerchantItem](https://wow.gamepedia.com/API_PickupMerchantItem)\(index\) - Places the item onto the cursor. If the cursor already has an item, the item in the cursor will be sold.

NOCOMBAT [PickupPetAction](https://wow.gamepedia.com/API_PickupPetAction)\(slot\) - Drags an action from the specified pet action bar slot into the cursor.

[PickupPlayerMoney](https://wow.gamepedia.com/API_PickupPlayerMoney) - Picks up an amount of money from the player.

NOCOMBAT [PickupSpell](https://wow.gamepedia.com/API_PickupSpell)\(spellID\) - Places the specified spell onto the cursor.

[PickupStablePet](https://wow.gamepedia.com/API_PickupStablePet)\(index\) - ?.

[PickupTradeMoney](https://wow.gamepedia.com/API_PickupTradeMoney)\(amount\)

[PlaceAction](https://wow.gamepedia.com/API_PlaceAction)\(slot\) - Drops an action from the cursor into the specified quickbar slot.

[PutItemInBackpack](https://wow.gamepedia.com/API_PutItemInBackpack)\(\) - attempts to place item in backpack \(bag slot 0\).

[PutItemInBag](https://wow.gamepedia.com/API_PutItemInBag)\(inventoryId\) - attempts to place item in a specific bag.

[ResetCursor](https://wow.gamepedia.com/API_ResetCursor)\(\) -

[SetCursor](https://wow.gamepedia.com/API_SetCursor)\("cursor"\) - Path to a texture to use as the cursor image \(must be 32x32 pixels\) or one of the built-in cursor tokens or nil.

ShowContainerSellCursor\(index, slot\) -

UI [ShowInspectCursor](https://wow.gamepedia.com/API_ShowInspectCursor)\(\) - Change the cursor to the magnifying glass inventory inspection cursor.

ShowInventorySellCursor\(\) - ?.

REMOVED [ShowMerchantSellCursor](https://wow.gamepedia.com/API_ShowMerchantSellCursor)\(\) - Changes the cursor to the merchant sell cursor.

[ShowRepairCursor](https://wow.gamepedia.com/API_ShowRepairCursor)\(\) -

[SplitContainerItem](https://wow.gamepedia.com/API_SplitContainerItem)\(bagID, slot, amount\) - Picks up part of a stack.



