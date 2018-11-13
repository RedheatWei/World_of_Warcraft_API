### 物品函数

###### 这些功能是直接对项目链接或项目信息进行操作的功能。也可以查看[容器/包裹函数](https://wow.gamepedia.com/World_of_Warcraft_API#Container.2FBag_Functions)和[装备函数](https://wow.gamepedia.com/World_of_Warcraft_API#Inventory_Functions)

[EquipItemByName](https://wow.gamepedia.com/API_EquipItemByName)\(itemId or "itemName" or "itemLink"\[, invSlot\]\) - 装备项目，可选择装入指定的插槽。

[GetAuctionItemLink](https://wow.gamepedia.com/API_GetAuctionItemLink)\("type", index\) - 返回指定拍卖项目的[itemLink](https://wow.gamepedia.com/ItemLink)。

[GetContainerItemLink](https://wow.gamepedia.com/API_GetContainerItemLink)\([bagID](https://wow.gamepedia.com/BagId), slot\) -返回bag＃，slot＃中项目的[itemLink](https://wow.gamepedia.com/ItemLink)。

[GetDetailedItemLevelInfo](https://wow.gamepedia.com/API_GetDetailedItemLevelInfo)\(itemId or "itemName" or "itemLink"\) - 返回物品的物品等级

[GetItemCooldown](https://wow.gamepedia.com/API_GetItemCooldown)\(itemId\) - 返回开始时间,持续时间,是否可用.

[GetItemCount](https://wow.gamepedia.com/API_GetItemCount)\(itemId or "itemName" or "itemLink"\[, includeBank\]\[, includeCharges\]\) - 返回库存中此类商品的数量\[或者如果收费则收费\]

[GetItemFamily](https://wow.gamepedia.com/API_GetItemFamily)\(itemId or "itemName" or "itemLink"\) - 返回物品可以进入的背包类型，或者包含可以包含该物品的背包类型。 \(添加于 [Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

[GetItemIcon](https://wow.gamepedia.com/API_GetItemIcon)\(itemId\) - 返回物品的图标。适用于任何有效物品，即使它不在缓存中. \(添加于[Patch 2.4](https://wow.gamepedia.com/Patch_2.4)\)

[GetItemInfo](https://wow.gamepedia.com/API_GetItemInfo)\(itemId or "itemString" or "itemName" or "itemLink"\) - 返回物品信息

[GetItemInfoInstant](https://wow.gamepedia.com/API_GetItemInfoInstant)\(itemId or "itemString" or "itemName" or "itemLink"\) - 返回物品基本信息

[GetItemQualityColor](https://wow.gamepedia.com/API_GetItemQualityColor)\(quality\) -  返回质量的RGB颜色.

[GetItemSpell](https://wow.gamepedia.com/API_GetItemSpell)\(item\) - 返回名称,类别.

[GetItemStats](https://wow.gamepedia.com/API_GetItemStats)\(itemLink, statTable\) - 返回物品的状态表.

[GetMerchantItemLink](https://wow.gamepedia.com/API_GetMerchantItemLink)\(index\) - 返回给定可购买商品的[itemLink](https://wow.gamepedia.com/ItemLink)

[GetQuestItemLink](https://wow.gamepedia.com/API_GetQuestItemLink)\("type", index\) - 返回任务奖励项目的[itemLink](https://wow.gamepedia.com/ItemLink)。

[GetQuestLogItemLink](https://wow.gamepedia.com/API_GetQuestLogItemLink)\("type", index\) - 返回任务奖励项目的[itemLink](https://wow.gamepedia.com/ItemLink)。

[GetTradePlayerItemLink](https://wow.gamepedia.com/API_GetTradePlayerItemLink)\(id\) - 返回交易窗口一侧给定项目的[itemLink](https://wow.gamepedia.com/ItemLink)（如果已打开）

[GetTradeSkillItemLink](https://wow.gamepedia.com/API_GetTradeSkillItemLink)\(index\) - 返回交易技能项的[itemLink](https://wow.gamepedia.com/ItemLink)。

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

