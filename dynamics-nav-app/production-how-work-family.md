---
title: How to Use Item Families in Manufacturing
description: The main task in customizing a base calendar for your company, or one of its business partners, is to enter any changes to working and nonworking day status.
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.search.keywords: ''
ms.date: 11/20/2018
ms.author: sgroespe
ms.openlocfilehash: e9cad1f2610fbc4d69f816dfcbdd760f6ccbfafc
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7274"
---
# <a name="how-to-work-with-production-families"></a>How to: Work with Production Families
A production family is a group of individual items whose relationship is based on the similarity of their manufacturing processes. By forming production families, some items can be manufactured twice or more in one production, which will optimize material consumption.

In the **Quantity** field in the **Family** window, you enter the quantity that will be produced when the whole family has been manufactured once.

## <a name="example"></a>Example
In punching processes, four pieces of the same item can be produced from one sheet and 10 pieces of another, different, item at the same time. The punching machine will punch all 14 pieces in one step.

Forming production families reduces the scrap quantity because what would normally be leftover scrap, when producing big pieces, will be used instead to produce small items.

## <a name="to-set-up-a-production-family"></a>To set up a production family
1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Families**, and then choose the related link.
2. Fill in the fields as necessary. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-produce-based-on-a-production-family"></a>To produce based on a production family
1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Orders**, and then choose the related link.
2. Create a new production order. For more information, see [How to: Create Production orders](production-how-to-create-production-orders.md).
3. In the **Source Type** field, select **Family**.  
4. In the **Source No.** field, select the relevant production family.

## <a name="see-also"></a>See Also
[How to: Create Production BOMs](production-how-to-create-production-boms.md)  
[Setting Up Manufacturing](production-configure-production-processes.md)  
[Manufacturing](production-manage-manufacturing.md)    
[Planning](production-planning.md)   
[Inventory](inventory-manage-inventory.md)  
[Purchasing](purchasing-manage-purchasing.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
