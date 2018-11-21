### 安全和保护函数

[issecure](https://wow.gamepedia.com/API_issecure)\(\) - 确定当前环境是否安全。

[forceinsecure](https://wow.gamepedia.com/API_forceinsecure)\(\) - 污染当前的执行路径。

[issecurevariable](https://wow.gamepedia.com/API_issecurevariable)\(\[table,\] "name"\) - 确定指定的变量是否安全。

[securecall](https://wow.gamepedia.com/API_securecall)\(function or "functionName", ...\) - 从安全环境调用函数，而不会冒安全状态的风险。

[hooksecurefunc](https://wow.gamepedia.com/API_hooksecurefunc)\(\[table,\] "functionName", hookfunc\) - 为命名函数创建一个安全的“post hook”。hookfunc在原始函数之后调用，并接收相同的参数。hookfunc的返回值将被丢弃。这是挂钩执行受保护功能的函数的唯一安全方法。

[InCombatLockdown](https://wow.gamepedia.com/API_InCombatLockdown)\(\) - 如果战斗中的AddOn限制处于活动状态，则返回true。

scrub\(...\) - 返回参数列表，其中非数字/布尔值/字符串值更改为nil。





