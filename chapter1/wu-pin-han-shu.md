### 物品函数

###### 这些功能是直接对项目链接或项目信息进行操作的功能。也可以查看[容器/包裹函数](https://wow.gamepedia.com/World_of_Warcraft_API#Container.2FBag_Functions)和[装备函数](https://wow.gamepedia.com/World_of_Warcraft_API#Inventory_Functions)

[EquipItemByName](https://wow.gamepedia.com/API_EquipItemByName)\(itemId or "itemName" or "itemLink"\[, invSlot\]\) - 装备项目，可选择装入指定的插槽。

[GetAuctionItemLink](https://wow.gamepedia.com/API_GetAuctionItemLink)\("type", index\) - 返回指定拍卖项目的[itemLink](https://wow.gamepedia.com/ItemLink)。

[GetContainerItemLink](https://wow.gamepedia.com/API_GetContainerItemLink)\([bagID](https://wow.gamepedia.com/BagId), slot\) -返回bag＃，slot＃中项目的[itemLink](https://wow.gamepedia.com/ItemLink)。

[GetDetailedItemLevelInfo](https://wow.gamepedia.com/API_GetDetailedItemLevelInfo)\(itemId or "itemName" or "itemLink"\) - 返回物品的物品等级

[GetItemCooldown](https://wow.gamepedia.com/API_GetItemCooldown)\(itemId\) - Returns startTime, duration, enable.

[GetItemCount](https://wow.gamepedia.com/API_GetItemCount)\(itemId or "itemName" or "itemLink"\[, includeBank\]\[, includeCharges\]\) - Returns number of such items in inventory\[, or charges instead if it has charges\]

[GetItemFamily](https://wow.gamepedia.com/API_GetItemFamily)\(itemId or "itemName" or "itemLink"\) - Returns the bag type that an item can go into, or for bags the type of items that it can contain. \(added in [Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

[GetItemIcon](https://wow.gamepedia.com/API_GetItemIcon)\(itemId\) - Returns the icon for the item. Works for any valid item even if it's not in the cache. \(added in[Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

[GetItemInfo](https://wow.gamepedia.com/API_GetItemInfo)\(itemId or "itemString" or "itemName" or "itemLink"\) - Returns information about an item.

[GetItemInfoInstant](https://wow.gamepedia.com/API_GetItemInfoInstant)\(itemId or "itemString" or "itemName" or "itemLink"\) - Returns basic information about an item.

[GetItemQualityColor](https://wow.gamepedia.com/API_GetItemQualityColor)\(quality\) - Returns the RGB color codes for a quality.

[GetItemSpell](https://wow.gamepedia.com/API_GetItemSpell)\(item\) - Returns name, rank.

[GetItemStats](https://wow.gamepedia.com/API_GetItemStats)\(itemLink, statTable\) - Returns a table of stats for an item.

[GetMerchantItemLink](https://wow.gamepedia.com/API_GetMerchantItemLink)\(index\) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for the given purchasable item

[GetQuestItemLink](https://wow.gamepedia.com/API_GetQuestItemLink)\("type", index\) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for a quest reward item.

[GetQuestLogItemLink](https://wow.gamepedia.com/API_GetQuestLogItemLink)\("type", index\) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for a quest reward item.

[GetTradePlayerItemLink](https://wow.gamepedia.com/API_GetTradePlayerItemLink)\(id\) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for the given item in your side of the trade window \(if open\)

[GetTradeSkillItemLink](https://wow.gamepedia.com/API_GetTradeSkillItemLink)\(index\) - Returns the [itemLink](https://wow.gamepedia.com/ItemLink) for a trade skill item.

[GetTradeSkillReagentItemLink](https://wow.gamepedia.com/API_GetTradeSkillReagentItemLink)\(index, reagentId\) - Returns the [itemLink](https://wow.gamepedia.com/ItemLink) for one of the reagents needed to craft the given item

[GetTradeTargetItemLink](https://wow.gamepedia.com/API_GetTradeTargetItemLink)\(id\) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for the given item in the other player's side of the trade window \(if open\)

IsUsableItem\(item\) - Returns usable, noMana.

[IsConsumableItem](https://wow.gamepedia.com/API_IsConsumableItem)\(item\) -

IsCurrentItem\(item\) -

[IsEquippedItem](https://wow.gamepedia.com/API_IsEquippedItem)\(item\) -

[IsEquippableItem](https://wow.gamepedia.com/API_IsEquippableItem)\(itemId or "itemName" or "itemLink"\) - Returns whether an item can be equipped.

[IsEquippedItemType](https://wow.gamepedia.com/API_IsEquippedItemType)\("type"\) - Where "type" is any valid inventory type, item class, or item subclass.

[IsItemInRange](https://wow.gamepedia.com/API_IsItemInRange)\("itemName" or "itemLink", "unit"\) - Nil for invalid target, false for out of range, true for in range.

ItemHasRange\(item\) -

[SplitContainerItem](https://wow.gamepedia.com/API_SplitContainerItem)\(bagID,slot,amount\) - Picks up part of a stack.

UI [SetItemRef](https://wow.gamepedia.com/API_SetItemRef)\(link, text, button\) - Handles item link tooltips in chat.

PROTECTED [UseItemByName](https://wow.gamepedia.com/API_UseItemByName)\("itemName", "unit"\) - Use an item on the unit specified.

