### 公会银行函数

###### 这些功能在[补丁2.3.0](https://wow.gamepedia.com/Patch_2.3.0)中引入。

[AutoStoreGuildBankItem](https://wow.gamepedia.com/API_AutoStoreGuildBankItem)\(tab, slot\) - 从银行取款，并自动将其存储在玩家的库存中。

BuyGuildBankTab\(\) - 购买公会银行标签，无需确认。

CanEditGuildBankTabInfo\(\) -

CanGuildBankRepair\(\) -

CanWithdrawGuildBankMoney\(\) - 布尔值，如果允许玩家提取资金，则为true。无需银行接近。

CloseGuildBankFrame\(\) - 关闭公会银行框架

DepositGuildBankMoney\(money\) - Deposits "money" amount in copper.

GetCurrentGuildBankTab\(\) - Integer of selected tab, &gt;= 1

GetGuildBankBonusDepositMoney\(\) -

[GetGuildBankItemInfo](https://wow.gamepedia.com/API_GetGuildBankItemInfo)\(tab, slot\) - Returns texture, amount and integer 1 or nil depending on locked state

[GetGuildBankItemLink](https://wow.gamepedia.com/API_GetGuildBankItemLink)\(tab, slot\) - Returns itemLink

[GetGuildBankMoney](https://wow.gamepedia.com/API_GetGuildBankMoney)\(\) - Integer, funds available in copper.

[GetGuildBankMoneyTransaction](https://wow.gamepedia.com/API_GetGuildBankMoneyTransaction)\(index\) - No bank proximity required, however QueryGuildBankLog function requires proximity.

GetGuildBankTabCost\(\) - Integer OR nil - cost in copper OR no tabs available to buy

[GetGuildBankTabInfo](https://wow.gamepedia.com/API_GetGuildBankTabInfo)\(tab\) - Returns the name and icon of the guild bank tab queried.

[GetGuildBankTabPermissions](https://wow.gamepedia.com/API_GetGuildBankTabPermissions)\(tab\) - Gets display / player's access info. Limited data available without bank proximity.

GetGuildBankText\(\) -

[GetGuildBankTransaction](https://wow.gamepedia.com/API_GetGuildBankTransaction)\(tab, index\) - Requires Guild Bank Proximity

GetGuildBankWithdrawGoldLimit\(\) - Returns withdraw limit for currently selected rank in guild control

GetGuildBankWithdrawMoney\(\) -

GetGuildTabardFileNames\(\)

GetNumGuildBankMoneyTransactions\(\) - Returns number of money log entries

GetNumGuildBankTabs\(\) - Integer count of bought tabs, &gt;= 0. No bank proximity required.

GetNumGuildBankTransactions\(tab\) - Returns number of log transactions for tab "tab"

PickupGuildBankItem\(tab, slot\) - Picks up an item from the guild bank

PickupGuildBankMoney\(money\) - Picks up "money" copper from the guild bank

QueryGuildBankLog\(tab\) - Updates bank log data from the server, called before all transaction functions. "Money tab" is MAX\_GUILDBANK\_TABS+1

QueryGuildBankTab\(tab\) - Updates bank tab data from the server, called before all item functions.

QueryGuildBankText\(\) -

SetCurrentGuildBankTab\(tab\) - Select different bank tab in the UI

SetGuildBankTabInfo\(tab, name, iconIndex\) - Modifies name and icon for tab

SetGuildBankTabItemWithdraw\(\) -

[SetGuildBankTabPermissions](https://wow.gamepedia.com/API_SetGuildBankTabPermissions)\(tab, index, enabled\) - Modifies the permissions for the GuildBankTab. Guild Leader Only.

SetGuildBankText\(\) -

[SetGuildBankWithdrawGoldLimit](https://wow.gamepedia.com/API_SetGuildBankWithdrawGoldLimit)\(amount\) - Sets the gold withdraw limit from the guild bank. Guild Leader Only.

SplitGuildBankItem\(tab, slot, amount\) - Picks up part of a stack

WithdrawGuildBankMoney\(money\) - Withdraws "money" copper from the guild bank

