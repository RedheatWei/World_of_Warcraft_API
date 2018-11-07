### 容器/包裹函数

###### 这些功能管理容器（袋子，背包）。另请参见[仓库功能](https://wow.gamepedia.com/World_of_Warcraft_API#Inventory_Functions)和[银行功能](https://wow.gamepedia.com/World_of_Warcraft_API#Bank_Functions)。

[ContainerIDToInventoryID](https://wow.gamepedia.com/API_ContainerIDToInventoryID)\([bagID](https://wow.gamepedia.com/BagId)\)

[GetBagName](https://wow.gamepedia.com/API_GetBagName)\([bagID](https://wow.gamepedia.com/BagId)\) - 获取玩家其中一个包的名称

[GetContainerItemCooldown](https://wow.gamepedia.com/API_GetContainerItemCooldown)\([bagID](https://wow.gamepedia.com/BagId), slot\)

[GetContainerItemDurability](https://wow.gamepedia.com/API_GetContainerItemDurability)\(bag, slot\) - 获得角色包中物品的当前和最大耐久性。

REMOVED [GetContainerItemGems](https://wow.gamepedia.com/API_GetContainerItemGems)\(bag, slot\) - 返回插入指定容器槽中项目的宝石的项ID。

[GetContainerItemID](https://wow.gamepedia.com/API_GetContainerItemID)\(bag, slot\) - 返回特定容器槽中项的项ID。

[GetContainerItemInfo](https://wow.gamepedia.com/API_GetContainerItemInfo)\([bagID](https://wow.gamepedia.com/BagId), slot\) - 获取其中一个玩家行李中的物品信息。

[GetContainerItemLink](https://wow.gamepedia.com/API_GetContainerItemLink)\([bagID](https://wow.gamepedia.com/BagId), slot\) - 获取包裹/插槽中项目的[物品ID](https://wow.gamepedia.com/ItemLink)

[GetContainerNumSlots](https://wow.gamepedia.com/API_GetContainerNumSlots)\([bagID](https://wow.gamepedia.com/BagId)\) - 返回索引指定的包中的插槽总数。

[GetContainerItemQuestInfo](https://wow.gamepedia.com/API_GetContainerItemQuestInfo)\(bag, slot\) - 返回有关任务和任务开始项目的信息。（在3.3.3中添加）

[GetContainerNumFreeSlots](https://wow.gamepedia.com/API_GetContainerNumFreeSlots)\([bagID](https://wow.gamepedia.com/BagId)\) - 返回索引指定的包中的空闲槽数和槽位数。（在[补丁2.4](https://wow.gamepedia.com/Patch_2.4)中添加）

UI[OpenAllBags](https://wow.gamepedia.com/API_OpenAllBags)\(\) - 打开所有包裹

UI [CloseAllBags](https://wow.gamepedia.com/API_CloseAllBags)\(\) - 关闭所有包裹

[PickupBagFromSlot](https://wow.gamepedia.com/API_PickupBagFromSlot)\(slot\) - 从指定的插槽中取出行李，将其放在光标中。

[PickupContainerItem](https://wow.gamepedia.com/API_PickupContainerItem)\([bagID](https://wow.gamepedia.com/BagId),slot\)

[PutItemInBackpack](https://wow.gamepedia.com/API_PutItemInBackpack)\(\) - 试图将物品放入背包（袋槽0）。

[PutItemInBag](https://wow.gamepedia.com/API_PutItemInBag)\(inventoryId\) - 试图将物品放在特定的包里。

[SplitContainerItem](https://wow.gamepedia.com/API_SplitContainerItem)\([bagID](https://wow.gamepedia.com/BagId),slot,amount\)

UI [ToggleBackpack](https://wow.gamepedia.com/API_ToggleBackpack)\(\) - T打开/关闭你的背包。

UI [ToggleBag](https://wow.gamepedia.com/API_ToggleBag)\([bagID](https://wow.gamepedia.com/BagId)\) - 打开或关闭指定的包。

PROTECTED \(situational\) [UseContainerItem](https://wow.gamepedia.com/API_UseContainerItem)\([bagId](https://wow.gamepedia.com/BagId), slot\[, target\]\) - 对行李中的物品执行“右键单击”操作或有针对性地使用。- 在1.12中添加了第3个参数

