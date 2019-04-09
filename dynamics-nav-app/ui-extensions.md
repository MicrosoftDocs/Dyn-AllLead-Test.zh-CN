---
title: Installing Extensions to Customize Dynamics NAV
description: Learn about adding functionality and customizing Dynamics NAV by installing extensions.
documentationcenter: ''
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: app, add-in, manifest, customize
ms.date: 11/28/2017
ms.author: edupont
ms.openlocfilehash: 5751ba7c4bc7a011a4d2af5b3e77f8e5b37e698a
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7131"
---
# <a name="customizing-dynamics-nav-using-extensions"></a>Customizing Dynamics NAV Using Extensions
You can customize [!INCLUDE[d365fin](includes/d365fin_md.md)] by installing extensions that add functionality, change behavior, or give you access to online services. For example, Microsoft offers an extension that provides integration with PayPal Payments Standard, and several that make it easy to import data from other finance apps.   

You manage the extensions in the **Extension Management** window. You can access this window from Home. Alternatively, choose the **Search for Page or Report** icon ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") in the top right corner, enter **Extension**, and then choose the related link.  

> [!NOTE]  
>   If you think you should have access to an extension but you cannot find its functionality, check the **Extension Management** window - if the extension is not listed there, you can install it as described in the following section.  

## <a name="installing-an-extension"></a>Installing an Extension
In the **Extension Management** window, you can see the extensions that are currently available, and are either installed or ready to be installed.

> [!NOTE]  
>   Extensions might need to be published before they are available in the list. Typically, this is something a Microsoft Partner helps with. For more information, see [How to: Publish and Install an Extension v2.0](https://go.microsoft.com/fwlink/?linkid=864046).

If you choose an extension, you can read about what the extension does, and you can access Help for the extension to learn more. When you choose to install an extension, you must agree to the terms of use.  

When you install an extension, you might have to set it up, such as specifying an account for use with the **PayPal Payments Standard** extension.
Other extensions simply add fields to an existing page, or they add a new page, for example.  

If you uninstall an extension, and you then change your mind, you can install it again. When you uninstall an extension that you have been using, the data is preserved so that if you install the extension again, your data is still available.  

All extensions are tested before they are made available to you, but we recommend that you access the links that are provided with each extension to learn more about the extension before you choose to install it.  

Microsoft provides the following extensions:  

* [C5 2012 Data Migration](LocalFunctionality/Denmark/ui-extensions-c5-data-migration.md) (DK)
* [Ceridian Payroll](ui-extensions-ceridian-payroll.md)  
* [Image Analyzer](ui-extensions-image-analyzer.md)  
* [Microsoft Pay](https://go.microsoft.com/fwlink/?linkid=857276)
* [PayPal Payments Standard](ui-extensions-paypal-payments-standard.md)  
* [QuickBooks Data Migration](ui-extensions-quickbooks-data-migration.md)  
* [Quickbooks Payroll File Import](ui-extensions-quickbooks-payroll.md)  
* [Sales and Inventory Forecast](ui-extensions-sales-forecast.md)  

## <a name="see-also"></a>See Also
[How to: Enable Customer Payment Through PayPal](sales-how-enable-payment-service-extensions.md)  
[Migrating Business Data from Other Finance Systems](upload-data.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] Extensions by Other Providers](ui-extensions-other.md)  
[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
