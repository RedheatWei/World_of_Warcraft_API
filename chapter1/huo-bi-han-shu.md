### 货币函数

###### 大多数这些功能都是在[Patch 3.0.2](https://wow.gamepedia.com/Patch_3.0.2)中添加的。

[GetCoinText](https://wow.gamepedia.com/API_GetCoinText)\(amount, "separator"\) - 分解钱并插入分隔符字符串。在2.4.2中添加。

[GetCoinTextureString](https://wow.gamepedia.com/API_GetCoinTextureString)\(amount\[, fontHeight\]\) -分解金钱并插入纹理字符串。

[GetCurrencyInfo](https://wow.gamepedia.com/API_GetCurrencyInfo)\(id\) - 返回索引处货币的localized\_label，amount，icon\_file\_name。（已添加4.0.1）

[GetCurrencyLink](https://wow.gamepedia.com/API_GetCurrencyLink)\(currencyID,currencyAmount\) - 返回指定货币ID的货币链接。

[GetCurrencyListSize](https://wow.gamepedia.com/API_GetCurrencyListSize)\(\) - 返回货币列表中的元素数（标题和货币）。

[GetCurrencyListInfo](https://wow.gamepedia.com/API_GetCurrencyListInfo)\(index\) - 返回有关货币列表中元素的信息。

[ExpandCurrencyList](https://wow.gamepedia.com/API_ExpandCurrencyList)\(index, state\) - 设置货币列表标题的展开/折叠状态。

[SetCurrencyUnused](https://wow.gamepedia.com/API_SetCurrencyUnused)\(id, state\) - 改变货币是否标记为未使用。

UI [GetNumWatchedTokens](https://wow.gamepedia.com/API_GetNumWatchedTokens)\(\) - 返回当前观看的人数。

[GetBackpackCurrencyInfo](https://wow.gamepedia.com/API_GetBackpackCurrencyInfo)\(index\) - 返回有关观看货币的信息。

[SetCurrencyBackpack](https://wow.gamepedia.com/API_SetCurrencyBackpack)\(id, state\) - 改变是否跟踪货币。

