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

[GetTradeSkillReagentItemLink](https://wow.gamepedia.com/API_GetTradeSkillReagentItemLink)\(index, reagentId\) - 返回制作给定项目所需的其中一种试剂的[itemLink](https://wow.gamepedia.com/ItemLink)

[GetTradeTargetItemLink](https://wow.gamepedia.com/API_GetTradeTargetItemLink)\(id\) - 返回交易窗口另一个玩家一侧给定项目的[itemLink](https://wow.gamepedia.com/ItemLink)（如果打开）

IsUsableItem\(item\) - 返回是否可用 noMana.

[IsConsumableItem](https://wow.gamepedia.com/API_IsConsumableItem)\(item\) -

IsCurrentItem\(item\) -

[IsEquippedItem](https://wow.gamepedia.com/API_IsEquippedItem)\(item\) -

[IsEquippableItem](https://wow.gamepedia.com/API_IsEquippableItem)\(itemId or "itemName" or "itemLink"\) - 返回是否可以装备物品。

[IsEquippedItemType](https://wow.gamepedia.com/API_IsEquippedItemType)\("type"\) - 其中“type”是任何有效的库存类型，项目类或项目子类。

[IsItemInRange](https://wow.gamepedia.com/API_IsItemInRange)\("itemName" or "itemLink", "unit"\) - Nil表示无效目标，false表示超出范围，true表示范围。

ItemHasRange\(item\) -

[SplitContainerItem](https://wow.gamepedia.com/API_SplitContainerItem)\(bagID,slot,amount\) - 拾取堆叠的一部分。

UI [SetItemRef](https://wow.gamepedia.com/API_SetItemRef)\(link, text, button\) - 处理聊天中的项目链接工具提示。

PROTECTED [UseItemByName](https://wow.gamepedia.com/API_UseItemByName)\("itemName", "unit"\) - 使用指定单位上的项目。

