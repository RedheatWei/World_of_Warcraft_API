### 队伍查找器

###### 在[Patch 3.3.0](https://wow.gamepedia.com/Patch_3.3.0)中作为“地下城查找器”和“团队浏览器”推出，这个UI在[Patch 6.0.3](https://wow.gamepedia.com/Patch_6.0.3)中彻底改造并重命名为“组队查找器”。

C\_LFGList.AcceptInvite\(resultID\) -

[C\_LFGList.ApplyToGroup](https://wow.gamepedia.com/API_C_LFGList.ApplyToGroup)\(resultID, comment, tankOK, healerOK, damageOK\) -

C\_LFGList.CancelApplication\(resultID\) -

[C\_LFGList.ClearSearchResults](https://wow.gamepedia.com/API_C_LFGList.ClearSearchResults)\(\)

[C\_LFGList.CreateListing](https://wow.gamepedia.com/API_C_LFGList.CreateListing)\("groupName", itemLevel, "voiceChat", "comment", autoAccept\)

C\_LFGList.DeclineApplicant\(applicantID\) -

C\_LFGList.DeclineInvite\(resultID\) -

[C\_LFGList.GetActiveEntryInfo](https://wow.gamepedia.com/API_C_LFGList.GetActiveEntryInfo)\(\) - 返回当前列出队伍的信息.

[C\_LFGList.GetActivityGroupInfo](https://wow.gamepedia.com/API_C_LFGList.GetActivityGroupInfo)\(groupID\) - 返回有关活动组的信息。

[C\_LFGList.GetActivityInfo](https://wow.gamepedia.com/API_C_LFGList.GetActivityInfo)\(activityID\) - 返回有关预制组活动的信息。

[C\_LFGList.GetActivityInfoExpensive](https://wow.gamepedia.com/API_C_LFGList.GetActivityInfoExpensive)\(activityID\) - 检查您是否在与活动相关联的区域中。

[C\_LFGList.GetApplicantInfo](https://wow.gamepedia.com/API_C_LFGList.GetApplicantInfo)\(applicantID\) - 返回申请人的状态信息和自定义消息

[C\_LFGList.GetApplicantMemberInfo](https://wow.gamepedia.com/API_C_LFGList.GetApplicantMemberInfo)\(applicantID, memberIndex\) -返回有关申请人组成员的昵称，职业，级别等信息

[C\_LFGList.GetApplicantMemberStats](https://wow.gamepedia.com/API_C_LFGList.GetApplicantMemberStats)\(applicantID, memberIndex\) - 返回有关申请人组成员的统计信息

[C\_LFGList.GetApplicants](https://wow.gamepedia.com/API_C_LFGList.GetApplicants)\(\) - 返回申请人ID的表

C\_LFGList.GetApplicationInfo\(resultID\) -

C\_LFGList.GetApplications\(\) -

[C\_LFGList.GetAvailableActivities](https://wow.gamepedia.com/API_C_LFGList.GetAvailableActivities)\(\[categoryID\[, groupID \[, filter\]\]\]\) - 返回可用的活动ID列表。

[C\_LFGList.GetAvailableActivityGroups](https://wow.gamepedia.com/API_C_LFGList.GetAvailableActivityGroups)\(categoryID\[,filter\]\) - 返回可用groupID的列表。

[C\_LFGList.GetAvailableCategories](https://wow.gamepedia.com/API_C_LFGList.GetAvailableCategories)\(\[filter\]\) - 返回可用类别ID的列表。

C\_LFGList.GetAvailableRoles\(\)

[C\_LFGList.GetCategoryInfo](https://wow.gamepedia.com/API_C_LFGList.GetCategoryInfo)\(categoryID\) - 返回有关特定类别的信息。

C\_LFGList.GetNumApplicants\(\) -

C\_LFGList.GetNumApplications\(\) -

C\_LFGList.GetNumInvitedApplicantMembers\(\) -

C\_LFGList.GetNumPendingApplicantMembers\(\) -

C\_LFGList.GetRoleCheckInfo\(\) -

C\_LFGList.GetSearchResultEncounterInfo\(resultID\) -

C\_LFGList.GetSearchResultFriends\(resultID\) -

C\_LFGList.GetSearchResultInfo\(resultID\) -

C\_LFGList.GetSearchResultMemberCounts\(resultID\) -

C\_LFGList.GetSearchResultMemberInfo\(resultID, memberIndex\) -

[C\_LFGList.GetSearchResults](https://wow.gamepedia.com/API_C_LFGList.GetSearchResults)\(\) - 返回 numResultID, totalResultID

C\_LFGList.HasActivityList\(\) -

C\_LFGList.InviteApplicant\(applicantID\) -

C\_LFGList.IsCurrentlyApplying\(\) -

C\_LFGList.RefreshApplicants\(\) -

C\_LFGList.RemoveApplicant\(applicantID\) -

[C\_LFGList.RemoveListing](https://wow.gamepedia.com/API_C_LFGList.RemoveListing)\(\) -

C\_LFGList.ReportApplicant\(applicantID\) -

C\_LFGList.ReportSearchResult\(resultID, complaintType\) -

[C\_LFGList.RequestAvailableActivities](https://wow.gamepedia.com/API_C_LFGList.RequestAvailableActivities)\(\) -

[C\_LFGList.Search](https://wow.gamepedia.com/API_C_LFGList.Search)\(categoryID, "query" \[, filter \[, preferredFilters\] \]\) -

C\_LFGList.SetApplicantMemberRole\(applicantID, memberIndex, "ROLE"\) -

C\_LFGList.UpdateListing\(lfgID, "groupName", itemLevel, "voiceChat", "comment", autoAccept\) -

以下是旧的“Dungeon Finder”/“Raid Browser”UI使用的功能。它们可能仍在Group Finder UI中使用：

RefreshLFGList\(\)

SearchLFGGetEncounterResults\(index, bossIndex\) - 返回boss名称, 类型, 是否击杀

SearchLFGGetJoinedID\(\) - 返回当前选中的raid ID或nil

[SearchLFGGetNumResults](https://wow.gamepedia.com/API_SearchLFGGetNumResults)\(\) - 返回 numResults, totalResults

[SearchLFGGetPartyResults](https://wow.gamepedia.com/API_SearchLFGGetPartyResults)\(index, partyMemberIndex\) - 返回 name, level, relationship, className, areaName, comment

[SearchLFGGetResults](https://wow.gamepedia.com/API_SearchLFGGetResults)\(index\) - 返回 name, level, areaName, className, comment, partyMembers, status, class, encountersTotal, encountersComplete, isLeader, isTank, isHealer, isDamage

HW [SearchLFGJoin](https://wow.gamepedia.com/API_SearchLFGJoin)\(typeID, raidID\) - 进入Raid浏览器搜索

SearchLFGLeave\(\) -从浏览Raid浏览器中删除自己。相当于在Raid浏览器中选择“无”

SearchLFGSort\(sortType\)

[SetLFGComment](https://wow.gamepedia.com/API_SetLFGComment)\(comment\) - 在raid浏览器中设置评论

