### 公会银行函数

###### 这些功能在[补丁2.3.0](https://wow.gamepedia.com/Patch_2.3.0)中引入。

[AutoStoreGuildBankItem](https://wow.gamepedia.com/API_AutoStoreGuildBankItem)\(tab, slot\) - 从银行取款，并自动将其存储在玩家的库存中。

BuyGuildBankTab\(\) - 购买公会银行标签，无需确认。

CanEditGuildBankTabInfo\(\) -

CanGuildBankRepair\(\) -

CanWithdrawGuildBankMoney\(\) - 布尔值，如果允许玩家提取资金，则为true。无需银行接近。

CloseGuildBankFrame\(\) - 关闭公会银行框架

DepositGuildBankMoney\(money\) - 用铜存入“钱”金额。

GetCurrentGuildBankTab\(\) - 选定选项卡的整数，&gt; = 1

GetGuildBankBonusDepositMoney\(\) -

[GetGuildBankItemInfo](https://wow.gamepedia.com/API_GetGuildBankItemInfo)\(tab, slot\) - 返回纹理，数量和整数1或nil，具体取决于锁定状态

[GetGuildBankItemLink](https://wow.gamepedia.com/API_GetGuildBankItemLink)\(tab, slot\) - 返回物品链接

[GetGuildBankMoney](https://wow.gamepedia.com/API_GetGuildBankMoney)\(\) - 整数，铜可用资金。

[GetGuildBankMoneyTransaction](https://wow.gamepedia.com/API_GetGuildBankMoneyTransaction)\(index\) - 不需要银行接近，但QueryGuildBankLog功能需要接近。

GetGuildBankTabCost\(\) - 整数或零 - 铜成本或没有可供购买的标签

[GetGuildBankTabInfo](https://wow.gamepedia.com/API_GetGuildBankTabInfo)\(tab\) - 返回查询的公会银行标签的名称和图标。

[GetGuildBankTabPermissions](https://wow.gamepedia.com/API_GetGuildBankTabPermissions)\(tab\) - 获取显示/用户的访问信息。有限的数据，不需要接近银行。

GetGuildBankText\(\) -

[GetGuildBankTransaction](https://wow.gamepedia.com/API_GetGuildBankTransaction)\(tab, index\) - 要求公会银行邻近

GetGuildBankWithdrawGoldLimit\(\) - 返回公会控制中当前所选等级的撤回限制

GetGuildBankWithdrawMoney\(\) -

GetGuildTabardFileNames\(\)

GetNumGuildBankMoneyTransactions\(\) - 返回货币日志条目的数量

GetNumGuildBankTabs\(\) - 已购买标签的整数计数，&gt; = 0.无需银行临近。

GetNumGuildBankTransactions\(tab\) - 返回选项卡“tab”的日志事务数

PickupGuildBankItem\(tab, slot\) - 从公会银行拿起一件物品

PickupGuildBankMoney\(money\) - 从公会银行拿出“钱”铜

QueryGuildBankLog\(tab\) - 更新来自服务器的银行日志数据，在所有事务功能之前调用。“Money tab”是MAX\_GUILDBANK\_TABS + 1

QueryGuildBankTab\(tab\) - 更新服务器中的银行选项卡数据，在所有项目功能之前调用。

QueryGuildBankText\(\) -

SetCurrentGuildBankTab\(tab\) - 在UI中选择不同的银行选项卡

SetGuildBankTabInfo\(tab, name, iconIndex\) - 修改选项卡的名称和图标

SetGuildBankTabItemWithdraw\(\) -

[SetGuildBankTabPermissions](https://wow.gamepedia.com/API_SetGuildBankTabPermissions)\(tab, index, enabled\) - 修改GuildBankTab的权限。仅限公会领袖。

SetGuildBankText\(\) -

[SetGuildBankWithdrawGoldLimit](https://wow.gamepedia.com/API_SetGuildBankWithdrawGoldLimit)\(amount\) - 设置公会银行的黄金提取限额。仅限公会领袖。

SplitGuildBankItem\(tab, slot, amount\) - 拾取堆叠的一部分

WithdrawGuildBankMoney\(money\) - 从公会银行取出“钱”铜

