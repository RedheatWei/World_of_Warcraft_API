### 队伍查找器

###### 在[Patch 3.3.0](https://wow.gamepedia.com/Patch_3.3.0)中作为“地下城查找器”和“团队浏览器”推出，这个UI在[Patch 6.0.3](https://wow.gamepedia.com/Patch_6.0.3)中彻底改造并重命名为“组队查找器”。

C\_LFGList.AcceptInvite\(resultID\) - This function is not yet documented.

[C\_LFGList.ApplyToGroup](https://wow.gamepedia.com/API_C_LFGList.ApplyToGroup)\(resultID, comment, tankOK, healerOK, damageOK\) -

C\_LFGList.CancelApplication\(resultID\) -

[C\_LFGList.ClearSearchResults](https://wow.gamepedia.com/API_C_LFGList.ClearSearchResults)\(\) 

[C\_LFGList.CreateListing](https://wow.gamepedia.com/API_C_LFGList.CreateListing)\("groupName", itemLevel, "voiceChat", "comment", autoAccept\)

C\_LFGList.DeclineApplicant\(applicantID\) - This function is not yet documented.

C\_LFGList.DeclineInvite\(resultID\) - This function is not yet documented.

[C\_LFGList.GetActiveEntryInfo](https://wow.gamepedia.com/API_C_LFGList.GetActiveEntryInfo)\(\) - Returns information about your currently listed group.

[C\_LFGList.GetActivityGroupInfo](https://wow.gamepedia.com/API_C_LFGList.GetActivityGroupInfo)\(groupID\) - Returns information about an activity group.

[C\_LFGList.GetActivityInfo](https://wow.gamepedia.com/API_C_LFGList.GetActivityInfo)\(activityID\) - Returns information about an activity for premade groups.

[C\_LFGList.GetActivityInfoExpensive](https://wow.gamepedia.com/API_C_LFGList.GetActivityInfoExpensive)\(activityID\) - Checks if you are in the zone associated with an activity.

[C\_LFGList.GetApplicantInfo](https://wow.gamepedia.com/API_C_LFGList.GetApplicantInfo)\(applicantID\) - Returns status informations and custom message of an applicant

[C\_LFGList.GetApplicantMemberInfo](https://wow.gamepedia.com/API_C_LFGList.GetApplicantMemberInfo)\(applicantID, memberIndex\) - Returns name, class, level and more about an applicant group member

[C\_LFGList.GetApplicantMemberStats](https://wow.gamepedia.com/API_C_LFGList.GetApplicantMemberStats)\(applicantID, memberIndex\) - Returns stats about an applicant group member

[C\_LFGList.GetApplicants](https://wow.gamepedia.com/API_C_LFGList.GetApplicants)\(\) - Returns a table with applicantIDs

C\_LFGList.GetApplicationInfo\(resultID\) - 

C\_LFGList.GetApplications\(\) - 

[C\_LFGList.GetAvailableActivities](https://wow.gamepedia.com/API_C_LFGList.GetAvailableActivities)\(\[categoryID\[, groupID \[, filter\]\]\]\) - Returns a list of available activityIDs.

[C\_LFGList.GetAvailableActivityGroups](https://wow.gamepedia.com/API_C_LFGList.GetAvailableActivityGroups)\(categoryID\[,filter\]\) - Returns a list of available groupIDs.

[C\_LFGList.GetAvailableCategories](https://wow.gamepedia.com/API_C_LFGList.GetAvailableCategories)\(\[filter\]\) - Returns a list of available categoryIDs.

C\_LFGList.GetAvailableRoles\(\) 

[C\_LFGList.GetCategoryInfo](https://wow.gamepedia.com/API_C_LFGList.GetCategoryInfo)\(categoryID\) - Returns information about a specific category.

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

[C\_LFGList.GetSearchResults](https://wow.gamepedia.com/API_C_LFGList.GetSearchResults)\(\) - returns numResultID, totalResultID

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

The following are functions that were used by the old "Dungeon Finder" / "Raid Browser" UIs. They may still be in use in the Group Finder UI:

RefreshLFGList\(\)

SearchLFGGetEncounterResults\(index, bossIndex\) - returns bossName, texture, isKilled

SearchLFGGetJoinedID\(\) - returns the currently selected raid ID or nil

[SearchLFGGetNumResults](https://wow.gamepedia.com/API_SearchLFGGetNumResults)\(\) - returns numResults, totalResults

[SearchLFGGetPartyResults](https://wow.gamepedia.com/API_SearchLFGGetPartyResults)\(index, partyMemberIndex\) - returns name, level, relationship, className, areaName, comment

[SearchLFGGetResults](https://wow.gamepedia.com/API_SearchLFGGetResults)\(index\) - returns name, level, areaName, className, comment, partyMembers, status, class, encountersTotal, encountersComplete, isLeader, isTank, isHealer, isDamage

HW [SearchLFGJoin](https://wow.gamepedia.com/API_SearchLFGJoin)\(typeID, raidID\) - enters a search into the Raid Browser

SearchLFGLeave\(\) - removes yourself from looking through the Raid Browser. Equivalent to selecting "none" in the Raid Browser

SearchLFGSort\(sortType\)

[SetLFGComment](https://wow.gamepedia.com/API_SetLFGComment)\(comment\) - sets the comment in the raid browser

  


