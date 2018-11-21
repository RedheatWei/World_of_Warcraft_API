### 真实ID\(战网\)函数

###### [补丁3.3.5](https://wow.gamepedia.com/Patch_3.3.5)中添加了这些功能。

BNAcceptFriendInvite\(ID\)

BNCheckBattleTagInviteToGuildMember\(fullname\)

BNCheckBattleTagInviteToUnit\(unit\)

[BNConnected](https://wow.gamepedia.com/API_BNConnected)\(\) - 返回你的战网连接状态 \(True\|False\)

BNDeclineFriendInvite\(ID\)

BNFeaturesEnabled\(\)

BNFeaturesEnabledAndConnected\(\)

BNGetBlockedInfo\(index\)

[BNGetFOFInfo](https://wow.gamepedia.com/API_BNGetFOFInfo)\(presenceID, mutual, non-mutual, index\) - 返回presenceID, givenName, surname, isFriend

[BNGetFriendGameAccountInfo](https://wow.gamepedia.com/API_BNGetFriendGameAccountInfo)\(bnetIDGameAccount\) -

[BNGetFriendIndex](https://wow.gamepedia.com/API_BNGetFriendIndex)\(presenceID\)

[BNGetFriendInfo](https://wow.gamepedia.com/API_BNGetFriendInfo)\(friendIndex\) - 返回 presenceID, givenName, surname, character name, character ID, game client, connected, status, broadcast and note of the friend

[BNGetFriendInfoByID](https://wow.gamepedia.com/API_BNGetFriendInfoByID)\(presenceID\) - 返回 presenceID, givenName, surname, character name, character ID, game client, connected, status, broadcast and note of the friend

BNGetFriendInviteInfo\(menuValue\) - 返回 presenceID, givenName, surname

[BNGetGameAccountInfo](https://wow.gamepedia.com/API_BNGetGameAccountInfo)\(bnetIDGameAccount\) -

[BNGetInfo](https://wow.gamepedia.com/API_BNGetInfo)\(\) - 返回 presenceID, toonID, currentBroadcast, bnetAFK, bnetDND

BNGetNumBlocked\(\)

BNGetNumFOF\(ID,mutual,non\)

[BNGetNumFriendGameAccounts](https://wow.gamepedia.com/API_BNGetNumFriendGameAccounts)\(friendIndex\)

BNGetNumFriendInvites\(\)

[BNGetNumFriends](https://wow.gamepedia.com/API_BNGetNumFriends)\(\) - 返回 numBNetTotal, numBNetOnline

BNGetSelectedBlock\(\)

BNGetSelectedFriend\(\)

BNInviteFriend\(bnetIDGameAccount\)

BNIsBlocked\(ID\)

BNIsFriend\(presenceID\)

BNIsSelf\(presenceID\) - 如果指定的presenceID是您自己的，则返回true，否则返回false。

BNRemoveFriend\(ID\)

BNReportPlayer\(presenceID, type, comments\)

BNRequestFOFInfo\(bnetIDAccount\)

BNSendFriendInvite\(text, noteText\)

BNSendFriendInviteByID\(ID, noteText\)

[BNSendGameData](https://wow.gamepedia.com/API_BNSendGameData)\(id, addonPrefix, text\) - BNet 等同于 SendAddonMessage -- Added in [Patch 5.4.7](https://wow.gamepedia.com/Patch_5.4.7)

BNSendSoR\(target,comment\)

BNSendVerifiedBattleTagInvite\(\) - 单位应该已经设置为BNCheckBattleTagInviteToUnit或BNCheckBattleTagInviteToGuildMember

[BNSendWhisper](https://wow.gamepedia.com/API_BNSendWhisper)\(id, text\)

[BNSetAFK](https://wow.gamepedia.com/API_BNSetAFK)\(bool\) - Set or unset afk status

BNSetBlocked\(ID, bool\)

[BNSetCustomMessage](https://wow.gamepedia.com/API_BNSetCustomMessage)\(text\)

[BNSetDND](https://wow.gamepedia.com/API_BNSetDND)\(bool\) - Set or unset dnd status

BNSetFriendNote\(ID, noteText\)

BNSetSelectedBlock\(index\)

BNSetSelectedFriend\(index\)

BNSummonFriendByIndex\(id\)

BNTokenFindName\(target\)

GetAutoCompletePresenceID\(name\)

IsBNLogin\(\)

