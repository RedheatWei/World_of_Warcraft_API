### 拍卖函数

C\_WowTokenPublic.GetListedAuctionableTokenInfo\(?\) -

C\_WowTokenPublic.GetNumListedAuctionableTokens\(?\) -

C\_WowTokenPublic.IsAuctionableWowToken\(?\)

C\_WowTokenPublic.UpdateListedAuctionableTokens\(?\) -

CalculateAuctionDeposit\(runTime, stackSize, numStacks\) - 给定指定的持续时间（1 = 12h，2 = 24h，3 = 48h），返回当前销售项目的所需担保金。

CanCancelAuction\(index\) - 如果可以取消拍卖，则返回1

[CancelSell](https://wow.gamepedia.com/API_CancelSell)\(\) - 清除拍卖行列表队列，不创建任何其他拍卖。（3.3.3）

[CanSendAuctionQuery](https://wow.gamepedia.com/API_CanSendAuctionQuery)\(\) - 如果拍卖搜索按钮处于活动状态，则返回1，否则返回nil。

CancelAuction\(index\) - Cancel the specified auction \(on the "owner" list\).

[ClickAuctionSellItemButton](https://wow.gamepedia.com/API_ClickAuctionSellItemButton)\(\) - Puts the currently 'picked up' item into the 'create auction' slot.

[CloseAuctionHouse](https://wow.gamepedia.com/API_CloseAuctionHouse)\(\) - Will close the AuctionFrame if opened.

GetAuctionHouseDepositRate\(\) - Returns the deposit rate \(percentage\) for the currently open auction house \(Possibly out-dated by CalculateAuctionDeposit\).

REMOVED [GetAuctionInvTypes](https://wow.gamepedia.com/API_GetAuctionInvTypes)\(classIndex, subclassIndex\) - Returns types of subcategories items.

[GetAuctionItemBattlePetInfo](https://wow.gamepedia.com/API_GetAuctionItemBattlePetInfo)\("type", index\) - Returns model details about the specified Battle Pet auction item.

REMOVED [GetAuctionItemClasses](https://wow.gamepedia.com/API_GetAuctionItemClasses)\(\) - Returns major auction item categories.

[GetAuctionItemInfo](https://wow.gamepedia.com/API_GetAuctionItemInfo)\("type", index\) - Returns details about the specified auction item.

[GetAuctionItemLink](https://wow.gamepedia.com/API_GetAuctionItemLink)\("type", index\) - Returns an [itemLink](https://wow.gamepedia.com/ItemLink) for the specified auction item.

[GetAuctionItemSubClasses](https://wow.gamepedia.com/API_GetAuctionItemSubClasses)\(classIndex\) - Returns subcategories in the nth auction category.

[GetAuctionItemTimeLeft](https://wow.gamepedia.com/API_GetAuctionItemTimeLeft)\("type", index\) - Returns the time left status of the specified auction item.

[GetAuctionSellItemInfo](https://wow.gamepedia.com/API_GetAuctionSellItemInfo)\(\) - Returns information about the current selling item \(or nil if none selected\).

GetAuctionSort\(?\) -

GetBidderAuctionItems\(\[page\]\) - Returns details about an auction item on which the user is bidding \(possibly out-dated by GetAuctionItemInfo\("bidder", item\)\)

[GetNumAuctionItems](https://wow.gamepedia.com/API_GetNumAuctionItems)\("type"\) - Returns the size of the specified auction item list.

GetOwnerAuctionItems\(\[page\]\) - Returns details about an auction item of which the user is the owner \(possibly out-dated by GetAuctionItemInfo\("owner", item\)\)

GetSelectedAuctionItem\("type"\) - Returns the index \(1-50\) of the selected auction item or 0 if none is selected.

[IsAuctionSortReversed](https://wow.gamepedia.com/API_IsAuctionSortReversed)\("type", "sort"\) - Returns 1 if the specified auction list and sort is reversed, nil otherwise.

[PlaceAuctionBid](https://wow.gamepedia.com/API_PlaceAuctionBid)\("type", index, bid\) - Place a bid on the selected auction item.

[QueryAuctionItems](https://wow.gamepedia.com/API_QueryAuctionItems)\("name", minLevel, maxLevel, invTypeIndex, classIndex, subclassIndex, page, isUsable, qualityIndex\) - Performs a search of the auction house with the specified characteristics.

SetAuctionsTabShowing\(showing\) - Sets whether auction-related events should be delivered to the client. \(3.3.3\)

[SetSelectedAuctionItem](https://wow.gamepedia.com/API_SetSelectedAuctionItem)\("type", index\) - Selects a specific item in the auction house.

SortAuctionApplySort\(?\) -

SortAuctionClearSort\(?\) -

[SortAuctionItems](https://wow.gamepedia.com/API_SortAuctionItems)\("type", "sort"\) - Request that the specified auction list be sorted by a specific column.

SortAuctionSetSort\(?\) -

[StartAuction](https://wow.gamepedia.com/API_StartAuction)\(minBid, buyoutPrice, runTime, stackSize, numStacks\) - Starts the auction you have created in the Create Auction panel.

  


