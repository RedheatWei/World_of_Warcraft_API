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

[PickupMerchantItem](https://wow.gamepedia.com/API_PickupMerchantItem)\(index\) - 将项目放在光标上。如果光标已有项目，则光标中的项目将被出售。

NOCOMBAT [PickupPetAction](https://wow.gamepedia.com/API_PickupPetAction)\(slot\) - 将指定宠物操作栏插槽中的操作拖动到光标中。

[PickupPlayerMoney](https://wow.gamepedia.com/API_PickupPlayerMoney) - 从玩家那里拿出一笔钱。

NOCOMBAT [PickupSpell](https://wow.gamepedia.com/API_PickupSpell)\(spellID\) - 将指定的法术放置在光标上。

[PickupStablePet](https://wow.gamepedia.com/API_PickupStablePet)\(index\) - ?.

[PickupTradeMoney](https://wow.gamepedia.com/API_PickupTradeMoney)\(amount\)

[PlaceAction](https://wow.gamepedia.com/API_PlaceAction)\(slot\) -将光标中的操作拖放到指定的快捷方式插槽中。

[PutItemInBackpack](https://wow.gamepedia.com/API_PutItemInBackpack)\(\) - 试图将物品放入背包（袋槽0）。

[PutItemInBag](https://wow.gamepedia.com/API_PutItemInBag)\(inventoryId\) - 试图将物品放在特定的包里。

[ResetCursor](https://wow.gamepedia.com/API_ResetCursor)\(\) -

[SetCursor](https://wow.gamepedia.com/API_SetCursor)\("cursor"\) - 用作光标图像（必须为32x32像素）的纹理的路径或内置光标标记之一或nil。

ShowContainerSellCursor\(index, slot\) -

UI [ShowInspectCursor](https://wow.gamepedia.com/API_ShowInspectCursor)\(\) - Change the cursor to the magnifying glass inventory inspection cursor.

ShowInventorySellCursor\(\) - ?.

REMOVED [ShowMerchantSellCursor](https://wow.gamepedia.com/API_ShowMerchantSellCursor)\(\) - Changes the cursor to the merchant sell cursor.

[ShowRepairCursor](https://wow.gamepedia.com/API_ShowRepairCursor)\(\) -

[SplitContainerItem](https://wow.gamepedia.com/API_SplitContainerItem)\(bagID, slot, amount\) - Picks up part of a stack.

