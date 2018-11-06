### 绑定函数

[GetBinding](https://wow.gamepedia.com/API_GetBinding)\(index\) - 获取该索引的操作和键绑定。

[GetBindingAction](https://wow.gamepedia.com/API_GetBindingAction)\("key"\[, checkOverride\]\) - 获取绑定到该键的操作。

[GetBindingKey](https://wow.gamepedia.com/API_GetBindingKey)\("command"\) - 获取绑定到操作的键。

UI [GetBindingText](https://wow.gamepedia.com/API_GetBindingText)\("key", "prefix", returnAbbr\) - 获取键的字符串值。

[GetCurrentBindingSet](https://wow.gamepedia.com/API_GetCurrentBindingSet)\(\) - 查询当前的键绑定集是特定于字符还是帐户

[GetNumBindings](https://wow.gamepedia.com/API_GetNumBindings)\(\) - Get total number key bindings and headers.

[LoadBindings](https://wow.gamepedia.com/API_LoadBindings)\(which\) - Loads default, account or character specific key binding set into memory from disk.

[RunBinding](https://wow.gamepedia.com/API_RunBinding)\("command"\[, "up"\]\) - Executes the key binding named "command"

[SaveBindings](https://wow.gamepedia.com/API_SaveBindings)\(which\) - Saves account or character specific key bindings from memory to disk.

NOCOMBAT [SetBinding](https://wow.gamepedia.com/API_SetBinding)\("key"\[, "command"\[, mode\]\]\) - Sets or unsets key bindings. \(2.0 - Can not be used in combat.\)

NOCOMBAT [SetBindingSpell](https://wow.gamepedia.com/API_SetBindingSpell)\("key", "Spell Name"\) - Set a key binding directly to a spell, uses the same spell name syntax as /cast.

NOCOMBAT [SetBindingClick](https://wow.gamepedia.com/API_SetBindingClick)\("key", "ButtonName" \[,"mouseButton"\]\) - Set a key binding directly to a Button object. The click sends a mouse down when the key is pressed, and a mouse up when it is released.

NOCOMBAT [SetBindingItem](https://wow.gamepedia.com/API_SetBindingItem)\("key", "itemname"\) -

NOCOMBAT [SetBindingMacro](https://wow.gamepedia.com/API_SetBindingMacro)\("key", "macroname" or macroId\) -

[SetConsoleKey](https://wow.gamepedia.com/API_SetConsoleKey)\("key"\) - Sets the console key \(normally ~ \).

NOCOMBAT [SetOverrideBinding](https://wow.gamepedia.com/API_SetOverrideBinding)\(owner, isPriority, "key"\[, "command"\]\) - Set \(or clear\) an override key binding.

NOCOMBAT [SetOverrideBindingSpell](https://wow.gamepedia.com/API_SetOverrideBindingSpell)\(owner, isPriority, "key", "spellname"\) -

NOCOMBAT [SetOverrideBindingClick](https://wow.gamepedia.com/API_SetOverrideBindingClick)\(owner, isPriority, "key", "buttonName" \[, "mouseClick"\]\) - Sets an override binding that acts like a mouse click on a button.

NOCOMBAT [SetOverrideBindingItem](https://wow.gamepedia.com/API_SetOverrideBindingItem)\(owner, isPriority, "key", "itemname"\) -

NOCOMBAT [SetOverrideBindingMacro](https://wow.gamepedia.com/API_SetOverrideBindingMacro)\(owner, isPriority, "key", "macroname" or macroId\) -

NOCOMBAT [ClearOverrideBindings](https://wow.gamepedia.com/API_ClearOverrideBindings)\(owner\) - Reset all overrides belonging to an owner.

SetMouselookOverrideBinding\("key" \[,"command"\]\) -

[IsModifierKeyDown](https://wow.gamepedia.com/API_IsModifierKeyDown)\(\) - equivalent to \(IsShiftKeyDown\(\) or IsControlKeyDown\(\) or IsAltKeyDown\(\)\).

[IsModifiedClick](https://wow.gamepedia.com/API_IsModifiedClick)\("action"\) - Returns 1 if the keys for the specified action are down, nil otherwise.

[IsMouseButtonDown](https://wow.gamepedia.com/API_IsMouseButtonDown)\(\[button or "button"\]\) -

