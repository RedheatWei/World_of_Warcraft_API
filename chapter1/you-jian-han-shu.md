### 邮件函数

###### [与Mail相关的事件。](https://wow.gamepedia.com/Events/Mail)

AutoLootMailItem\(index\) - 自动收取所有邮件

[CheckInbox](https://wow.gamepedia.com/API_CheckInbox)\(\) - 检查新邮件

[ClearSendMail](https://wow.gamepedia.com/API_ClearSendMail)\(\) - 这将清除“发送邮件”选项卡中的文本，并将COD项目放入包裹中。

[ClickSendMailItemButton](https://wow.gamepedia.com/API_ClickSendMailItemButton)\(\[itemIndex, \[clearItem\]\]\) - - 从发送邮件框架中放置或拾取项目。

[CloseMail](https://wow.gamepedia.com/API_CloseMail)\(\) - 关闭邮件窗口。

[DeleteInboxItem](https://wow.gamepedia.com/API_DeleteInboxItem)\(index\) - 删除索引处的收件箱项。它立即返回，它似乎没有等待删除通过，给出快速邮件删除尝试的正常问题。

[DropCursorMoney](https://wow.gamepedia.com/API_DropCursorMoney) - 减少光标持有的金额。

[GetCoinIcon](https://wow.gamepedia.com/API_GetCoinIcon)\(amount\)

[GetInboxHeaderInfo](https://wow.gamepedia.com/API_GetInboxHeaderInfo)\(index\) - 返回有关收件箱中邮件的信息。

[GetInboxItem](https://wow.gamepedia.com/API_GetInboxItem)\(index, itemIndex\) - 返回附加到（index）处的消息的附件的描述。

[GetInboxItemLink](https://wow.gamepedia.com/API_GetInboxItemLink)\(index, itemIndex\) - 返回附加到（索引）处的消息的附件的链接。

[GetInboxNumItems](https://wow.gamepedia.com/API_GetInboxNumItems)\(\) - 返回收件箱中的邮件数。

[GetInboxText](https://wow.gamepedia.com/API_GetInboxText)\(index\) - 返回（index）处消息的消息文本。

[GetInboxInvoiceInfo](https://wow.gamepedia.com/API_GetInboxInvoiceInfo)\(index\) - 返回有关拍卖行发票的信息。

[GetLatestThreeSenders](https://wow.gamepedia.com/API_GetLatestThreeSenders) - 返回最近未读邮件的发件人。

REMOVED [GetNumStationeries](https://wow.gamepedia.com/API_GetNumStationeries)\(\) - 尚未完全实施。目前它总是返回1。

REMOVED [GetSelectedStationeryTexture](https://wow.gamepedia.com/API_GetSelectedStationeryTexture)\(\) - 尚未完全实施。目前，当邮箱打开时，它会返回“STATIONERYTEST”。

[GetSendMailCOD](https://wow.gamepedia.com/API_GetSendMailCOD)\(\) - 确定邮件发送时邮箱中COD框中输入的金币数量

[GetSendMailItem](https://wow.gamepedia.com/API_GetSendMailItem)\(index\) - 获取有关发送邮件框架上附加的项目的信息。

[GetSendMailItemLink](https://wow.gamepedia.com/API_GetSendMailItemLink)\(index\) - 获取发送邮件框架上附加项目的链接。

GetSendMailMoney\(\) - ?.

[GetSendMailPrice](https://wow.gamepedia.com/API_GetSendMailPrice)\(\) - 获取发送邮件的花费

REMOVED [GetStationeryInfo](https://wow.gamepedia.com/API_GetStationeryInfo)\(index\) - 尚未完全实施。当前索引1返回“Default Stationery”。

HasInboxItem\(?\) -

HasNewMail\(\) -如果没有新邮件则返回nil.

HasSendMailItem\(index\) - returns boolean if item is attached to send mail frame in specified slot.

[InboxItemCanDelete](https://wow.gamepedia.com/API_InboxItemCanDelete)\(index\) - Boolean check for whether a message is returnable to the sender.

RespondMailLockSendItem\(slot, keepItem\) - Confirm item wont be refunded, keepItem boolean.

ReturnInboxItem\(index\) - Returns to the sender the attached item in the mail message at the specified index.

REMOVED[SelectStationery](https://wow.gamepedia.com/API_SelectStationery)\(index\) - Not yet fully implemented. It does nothing visible.

[SendMail](https://wow.gamepedia.com/API_SendMail)\("target", "subject", "body"\) - If the mailbox is open, this sends mail.

PROTECTED SetSendMailCOD\(amount\) - Make next mail sent using SendMail\(\) COD target for amount. -- Protected as of 2.0

PROTECTED SetSendMailMoney\(amount\) - Add money to next mail sent using SendMail\(\). -- Protected as of 2.0

SetSendMailShowing\(?\) -

[TakeInboxItem](https://wow.gamepedia.com/API_TakeInboxItem)\(index, itemIndex\) - Take the attached item from the mailbox message at index.

[TakeInboxMoney](https://wow.gamepedia.com/API_TakeInboxMoney)\(index\) - Take the attached money from the mailbox message at index.

TakeInboxTextItem\(index\) - Creates a permanent copy of letter \(readable "Plain Letter"\).



