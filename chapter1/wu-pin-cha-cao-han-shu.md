### 物品插槽函数

###### 以下内容与[Patch 2.0](https://wow.gamepedia.com/Patch_2.0)中的插槽项目和宝石一起介绍。ID是指正在考虑进行插入的项目中插槽的从1开始的索引。

[AcceptSockets](https://wow.gamepedia.com/API_AcceptSockets)\(\) - 将宝石插入插槽，必要时替换现有的宝石。

ClickSocketButton\(id\) - 如果光标当前持有宝石，将其插入插槽。

[CloseSocketInfo](https://wow.gamepedia.com/API_CloseSocketInfo)\(\) - 停止考虑物品插入插槽并不应用更改。

[GetSocketItemInfo](https://wow.gamepedia.com/API_GetSocketItemInfo)\(\) - 返回有关当前正在插入的项目的信息。

[GetSocketItemRefundable](https://wow.gamepedia.com/API_GetSocketItemRefundable)\(\) - 返回当前正在插入的项目是否可取出。

[GetSocketItemBoundTradeable](https://wow.gamepedia.com/API_GetSocketItemBoundTradeable)\(\) - 返回当前正在插入的项目是否可以暂时交易（BoP boss抢劫）。

[GetNumSockets](https://wow.gamepedia.com/API_GetNumSockets)\(\) - 返回当前正在插入的物品中的插槽数。

[GetSocketTypes](https://wow.gamepedia.com/API_GetSocketTypes)\(id\) - 返回插槽颜色.

GetExistingSocketInfo\(id\) - 返回有关插槽中现有宝石的信息。

GetExistingSocketLink\(id\) - 返回插槽中现有宝石的项链接。

GetNewSocketInfo\(id\) - 返回有关套接字中新（暂定）宝石的信息。

GetNewSocketLink\(id\) - 返回套接字中新（暂定）宝石的项链接。

SocketInventoryItem\(slot\) - 考虑插槽中的项目以进行插槽。

SocketContainerItem\(bag, slot\) - 考虑容器插槽中的项目以进行插槽。

