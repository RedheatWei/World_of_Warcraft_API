### 货币函数

###### 大多数这些功能都是在[Patch 3.0.2](https://wow.gamepedia.com/Patch_3.0.2)中添加的。

[GetCoinText](https://wow.gamepedia.com/API_GetCoinText)\(amount, "separator"\) - 分解钱并插入分隔符字符串。在2.4.2中添加。

[GetCoinTextureString](https://wow.gamepedia.com/API_GetCoinTextureString)\(amount\[, fontHeight\]\) -分解金钱并插入纹理字符串。

[GetCurrencyInfo](https://wow.gamepedia.com/API_GetCurrencyInfo)\(id\) - 返回索引处货币的localized\_label，amount，icon\_file\_name。（已添加4.0.1）

[GetCurrencyLink](https://wow.gamepedia.com/API_GetCurrencyLink)\(currencyID,currencyAmount\) - 返回指定货币ID的货币链接。

[GetCurrencyListSize](https://wow.gamepedia.com/API_GetCurrencyListSize)\(\) - returns the number of elements \(both headers and currencies\) in the currency list.

[GetCurrencyListInfo](https://wow.gamepedia.com/API_GetCurrencyListInfo)\(index\) - return information about an element in the currency list.

[ExpandCurrencyList](https://wow.gamepedia.com/API_ExpandCurrencyList)\(index, state\) - sets the expanded/collapsed state of a currency list header.

[SetCurrencyUnused](https://wow.gamepedia.com/API_SetCurrencyUnused)\(id, state\) - alters whether a currency is marked as unused.

UI [GetNumWatchedTokens](https://wow.gamepedia.com/API_GetNumWatchedTokens)\(\) - returns the number of currently watched.

[GetBackpackCurrencyInfo](https://wow.gamepedia.com/API_GetBackpackCurrencyInfo)\(index\) - returns information about a watched currency.

[SetCurrencyBackpack](https://wow.gamepedia.com/API_SetCurrencyBackpack)\(id, state\) - alters whether a currency is tracked.

