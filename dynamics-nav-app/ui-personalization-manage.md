---
title: Managing Personalization as an Administrator
description: Learn how to customize the user interface to suit your way of working.
documentationcenter: ''
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.openlocfilehash: c178267c72476fe59a64aaf894c3c8d4c824a7ce
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7005"
---
# <a name="managing-personalization-as-an-administrator"></a>Managing Personalization as an Administrator
Users can personalize their workspace to suit their own preferences. As an administrator, you can control and manage personalization by:

-   Enabling or disabling the personalization feature for the entire the application ([!INCLUDE[nav_web_md](includes/nav_web_md.md)] only). You cannot disable personalization on a global basis for the [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)].
-   Enabling or disabling the personalization feature for users of a specific profile.
-   Clearing any page personalizations that users have made.

## <a name="EnablePersonalization"></a>Enabling or Disabling Personalization in the [!INCLUDE[nav_web_md](includes/nav_web_md.md)] 
By default, personalization is not enabled in the [!INCLUDE[nav_web_md](includes/nav_web_md.md)]. To enable personalization, you modify the configuration file (navsettings.json) of the [!INCLUDE[nav_web_server_instance_md](includes/nav_web_server_instance_md.md)] instance for the Web client to include this line:

```
"PersonalizationEnabled": "True"
```

If you want to disable personalization in the Web client, remove this line.

For more information about how to modify the navsettings.json file, see [Modify the navsettings.json file directly](https://docs.microsoft.com/en-us/dynamics-nav/configuring-microsoft-dynamics-nav-web-client-by-modifying-the-web.config-file#WebClientSettingsFile).

## <a name="disabling-personalization-for-a-profile"></a>Disabling Personalization for a Profile
You can prevent all users that belong to a specific profile from being able to personalize their pages.
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Profiles**, and then choose the related link.
2.  Select the profile in the list that you want to modify.
3.  Select the **Disable personalization** check box, and then choose the **OK** button.

## <a name="clearing-user-personalizations"></a>Clearing User Personalizations
Clearing page personalization changes the page back to its original layout before any personalization was made. There are two ways to clear the personalizations that users have made to pages: using the **Delete User Personalization** page and using the **User Personalization Card** page.

### <a name="to-clear-user-personalizations-by-using-the-delete-user-personalization-page"></a>To clear user personalizations by using the Delete User Personalization page
The **Delete User Personalization** page enables you to clear personalization on a per-page, per-user basis.

1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Delete User Personalization**, and then choose the related link.

    The page lists all the pages that have been personalized and the user it belongs to.

    >[!NOTE]
    > A check mark in the **Legacy Personalization** column indicates that the personalization has been done strictly by using [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] and/or it has been done in [!INCLUDE[nav_web_md](includes/nav_web_md.md)] prior to [!INCLUDE[navnow_md](includes/navnow_md.md)]. Users who try to personalize these pages by using the [!INCLUDE[nav_web_md](includes/nav_web_md.md)] are locked from doing so unless they choose to unlock the page. For more information, see [Why a page is locked from personalizing](ui-personalization-locked.md).For more information about personalization between the [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] and [!INCLUDE[nav_web_md](includes/nav_web_md.md)], see [Working with personalization between the Dynamics NAV Windows and Web client](ui-personalization-overview.md#PersonalizationWinWeb).

2. Select the entry that you want to delete, and then choose the **Delete** action.

    The user will see the changes the next time they sign-in.

### <a name="to-clear-user-personalizations-by-using-the-user-personalization-card-page"></a>To clear user personalizations by using the User Personalization Card page

The **User Personalization Card** page enables you to clear the personalization on all pages for specific user. This requires write permission to Table 2000000072 **Profile**.

1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **User Personalization**, and then choose the related link.

    The **User Personalization** page lists all users who potentially have personalized pages. If you cannot find a user in the list, this means that they do not have any personalized pages.

2. Select the user from the list, and then choose the **Edit** action.

3.  On the **Actions** tab, choose **Clear Personalized Pages**.

    The user will see the changes the next time they sign-in.

## <a name="see-also"></a>See Also
[Personalization Overview](ui-personalization-overview.md)  
[Personalizing Your Workspace](ui-personalization-user.md)  
[Working with [!INCLUDE[navnow_md](includes/navnow_md.md)]](ui-work-product.md)  
[How to: Change the Role Center](change-role.md)  
