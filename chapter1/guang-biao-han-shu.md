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

[EquipCursorItem](https://wow.gamepedia.com/API_EquipCursorItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 将当前拾取的项目装入特定的库存槽。

[GetCursorInfo](https://wow.gamepedia.com/API_GetCursorInfo)\(\) - 返回有关游标持有内容的信息。

[GetCursorMoney](https://wow.gamepedia.com/API_GetCursorMoney) - 返回光标持有的金额。

[GetCursorPosition](https://wow.gamepedia.com/API_GetCursorPosition)\(\) - 返回光标在屏幕上的位置。

[HideRepairCursor](https://wow.gamepedia.com/API_HideRepairCursor)\(\) - 隐藏修复光标。

[InRepairMode](https://wow.gamepedia.com/API_InRepairMode)\(\) - 如果光标处于修复模式，则返回true。

NOCOMBAT [PickupAction](https://wow.gamepedia.com/API_PickupAction)\(slot\) -从指定的快速栏槽中拖出一个动作并将其保持在光标上。

[PickupBagFromSlot](https://wow.gamepedia.com/API_PickupBagFromSlot)\(slot\) - 从指定的插槽中取出物品，将其放在光标中。如果已拾取某个项目，则会将该项目放入指定的插槽中，并根据需要交换项目。

[PickupContainerItem](https://wow.gamepedia.com/API_PickupContainerItem)\([bagID](https://wow.gamepedia.com/BagId), slot\) -

[PickupInventoryItem](https://wow.gamepedia.com/API_PickupInventoryItem)\([invSlot](https://wow.gamepedia.com/InventorySlotId)\) - 从玩家的磨损库存中“挑选”一件物品。

[PickupItem](https://wow.gamepedia.com/API_PickupItem)\(itemId or "itemString" or "itemName" or "itemLink"\)

NOCOMBAT [PickupMacro](https://wow.gamepedia.com/API_PickupMacro)\("macroName" or index\) -将指定的宏放在光标上。

[PickupMerchantItem](https://wow.gamepedia.com/API_PickupMerchantItem)\(index\) - Places the item onto the cursor. If the cursor already has an item, the item in the cursor will be sold.

NOCOMBAT [PickupPetAction](https://wow.gamepedia.com/API_PickupPetAction)\(slot\) - Drags an action from the specified pet action bar slot into the cursor.

[PickupPlayerMoney](https://wow.gamepedia.com/API_PickupPlayerMoney) - Picks up an amount of money from the player.

NOCOMBAT [PickupSpell](https://wow.gamepedia.com/API_PickupSpell)\(spellID\) - Places the specified spell onto the cursor.

[PickupStablePet](https://wow.gamepedia.com/API_PickupStablePet)\(index\) - ?.

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

