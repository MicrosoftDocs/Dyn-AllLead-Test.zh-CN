---
title: Using the QuickBooks Migration Extension
description: Describes how to use the extension to import customers, vendors, items, and accounts from QuickBooks Desktop to Dynamics NAV.
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.openlocfilehash: be63e3837fdbd8a26bcd4524e381b850c85bd59d
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7456"
---
# <a name="the-quickbooks-data-migration-extension-for-dynamics-nav"></a>The QuickBooks Data Migration Extension for Dynamics NAV
This extension makes it easy to migrate customers, vendors, items, and accounts from QuickBooks Desktop to [!INCLUDE[d365fin](includes/d365fin_md.md)]. If your business uses QuickBooks today, you can export the relevant information and then open an assisted setup guide to upload the data to [!INCLUDE[d365fin](includes/d365fin_md.md)].  
For more information, see [Importing Business Data from Other Finance Systems](upload-data.md).

## <a name="exporting-data-from-quickbooks-desktop"></a>Exporting Data from QuickBooks Desktop
You must have exported some or all of your existing customers, vendors, inventory items, and accounts to an Intuit Interchange Format (IIF) file. The QuickBooks Data Migration extension includes a default mapping of QuickBooks data so that you can use your existing data to test your new [!INCLUDE[d365fin](includes/d365fin_md.md)] company. The default mapping will be sufficient in the vast majority of cases, but you can change the mapping in the assisted setup guide.  
In QuickBooks, the File menu includes a utility to export lists. For the purposes of [!INCLUDE[d365fin](includes/d365fin_md.md)], you can export the following lists:

* Customer List  
* Vendor List  
* Item List  
* Account List  

The exported data is saved as an IIF file that you can then upload to [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="finding-the-quickbooks-data-migration-extension"></a>Finding the QuickBooks Data Migration Extension
The QuickBooks Data Migration extension is installed and ready to go as an integrated part of the Data Migration assisted setup guide. If you are ready to get started now, and have exported your data from QuickBooks, choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Assisted Setup**, and then choose the related link. Choose **Migrate business data**, and then follow the steps in the guide.  

## <a name="see-also"></a>See Also
[Importing Business Data from Other Finance Systems](upload-data.md)  
[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions ](ui-extensions.md)  
