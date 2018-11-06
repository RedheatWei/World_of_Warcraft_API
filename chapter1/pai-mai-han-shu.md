### 拍卖函数

C\_WowTokenPublic.GetListedAuctionableTokenInfo\(?\) -

C\_WowTokenPublic.GetNumListedAuctionableTokens\(?\) -

C\_WowTokenPublic.IsAuctionableWowToken\(?\)

C\_WowTokenPublic.UpdateListedAuctionableTokens\(?\) -

CalculateAuctionDeposit\(runTime, stackSize, numStacks\) - 给定指定的持续时间（1 = 12h，2 = 24h，3 = 48h），返回当前销售项目的所需担保金。

CanCancelAuction\(index\) - 如果可以取消拍卖，则返回1

[CancelSell](https://wow.gamepedia.com/API_CancelSell)\(\) - 清除拍卖行列表队列，不创建任何其他拍卖。（3.3.3）

[CanSendAuctionQuery](https://wow.gamepedia.com/API_CanSendAuctionQuery)\(\) - 如果拍卖搜索按钮处于活动状态，则返回1，否则返回nil。

CancelAuction\(index\) - 取消指定的拍卖（在“所有者”列表中）。

[ClickAuctionSellItemButton](https://wow.gamepedia.com/API_ClickAuctionSellItemButton)\(\) - 将当前“拾取”的项目放入“创建拍卖”广告位。

[CloseAuctionHouse](https://wow.gamepedia.com/API_CloseAuctionHouse)\(\) - 如果打开，将关闭拍卖框。

GetAuctionHouseDepositRate\(\) - 返回当前打开拍卖行的税率（百分比）（可能过时由[CalculateAuctionDeposit](https://wow.gamepedia.com/index.php?title=API_CalculateAuctionDeposit&action=edit&redlink=1)）。

REMOVED [GetAuctionInvTypes](https://wow.gamepedia.com/API_GetAuctionInvTypes)\(classIndex, subclassIndex\) - 返回子类别项的类型。

[GetAuctionItemBattlePetInfo](https://wow.gamepedia.com/API_GetAuctionItemBattlePetInfo)\("type", index\) - 返回有关指定Battle Pet拍卖项目的模型详细信息。

REMOVED [GetAuctionItemClasses](https://wow.gamepedia.com/API_GetAuctionItemClasses)\(\) - 返回主要拍卖品类别。

[GetAuctionItemInfo](https://wow.gamepedia.com/API_GetAuctionItemInfo)\("type", index\) - 返回有关指定拍卖项目的详细信息。

[GetAuctionItemLink](https://wow.gamepedia.com/API_GetAuctionItemLink)\("type", index\) - 返回指定拍卖项目的[项目链接](https://wow.gamepedia.com/ItemLink)。

[GetAuctionItemSubClasses](https://wow.gamepedia.com/API_GetAuctionItemSubClasses)\(classIndex\) - 返回第n个拍卖类别中的子类别。

[GetAuctionItemTimeLeft](https://wow.gamepedia.com/API_GetAuctionItemTimeLeft)\("type", index\) - 返回指定拍卖项目的剩余时间状态。

[GetAuctionSellItemInfo](https://wow.gamepedia.com/API_GetAuctionSellItemInfo)\(\) - 返回有关当前销售项目的信息（如果未选择，则返回nil）。

GetAuctionSort\(?\) -

GetBidderAuctionItems\(\[page\]\) - 返回有关用户出价的拍卖项目的详细信息（可能过时由[GetAuctionItemInfo](https://wow.gamepedia.com/API_GetAuctionItemInfo)\(“bidder”，item\)时）

[GetNumAuctionItems](https://wow.gamepedia.com/API_GetNumAuctionItems)\("type"\) - 返回指定的拍卖项目列表的大小。

GetOwnerAuctionItems\(\[page\]\) - 返回有关用户所有者的拍卖项目的详细信息（可能由[GetAuctionItemInfo](https://wow.gamepedia.com/API_GetAuctionItemInfo)\(“owner”，item\)过时）

GetSelectedAuctionItem\("type"\) - 返回所选拍卖项目的索引（1-50），如果未选择，则返回0。

[IsAuctionSortReversed](https://wow.gamepedia.com/API_IsAuctionSortReversed)\("type", "sort"\) - 如果指定的拍卖列表和排序被反转，则返回1，否则返回nil。

[PlaceAuctionBid](https://wow.gamepedia.com/API_PlaceAuctionBid)\("type", index, bid\) - 对所选拍卖物品进行出价。

[QueryAuctionItems](https://wow.gamepedia.com/API_QueryAuctionItems)\("name", minLevel, maxLevel, invTypeIndex, classIndex, subclassIndex, page, isUsable, qualityIndex\) - 执行具有指定特征的拍卖行搜索。

SetAuctionsTabShowing\(showing\) - 设置是否应将与拍卖相关的事件传递给客户端。（3.3.3）

[SetSelectedAuctionItem](https://wow.gamepedia.com/API_SetSelectedAuctionItem)\("type", index\) -选择拍卖行中的特定项目。

SortAuctionApplySort\(?\) -

SortAuctionClearSort\(?\) -

[SortAuctionItems](https://wow.gamepedia.com/API_SortAuctionItems)\("type", "sort"\) - 请求指定的拍卖列表按特定列排序。

SortAuctionSetSort\(?\) -

[StartAuction](https://wow.gamepedia.com/API_StartAuction)\(minBid, buyoutPrice, runTime, stackSize, numStacks\) - 开始您在“创建拍卖”面板中创建的拍卖。

