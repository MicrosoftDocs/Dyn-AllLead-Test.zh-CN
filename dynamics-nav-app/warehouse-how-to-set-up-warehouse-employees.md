---
title: How to Set Up Warehouse Employees
description: Each user who performs warehouse activities must be set up as a warehouse employee assigned to one default location and potentially more non-default locations.
documentationcenter: ''
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 08/23/2017
ms.author: sgroespe
ms.openlocfilehash: fcb41f04d36eede1aced3127cb34b0cf542488e6
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7209"
---
# <a name="how-to-set-up-warehouse-employees"></a>How to: Set Up Warehouse Employees
Each user who performs warehouse activities must be set up as a warehouse employee assigned to one default location and potentially more non-default locations. This user setup filters all warehouse activities across the database to the employee's location so that the employee can only perform the warehouse activities at the default location. A user can be assigned to additional non-default locations for which the employee can view activity lines but not perform the activities.

## <a name="to-set-up-warehouse-employees"></a>To set up warehouse employees  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Warehouse Employees**, and then choose the related link.  
2. Choose the **New** action.  
3. Select the **User ID** field, and then select the user to be added as a warehouse employee. Choose the **OK** button.  
6.  In the **Location Code** field, enter the code of the location where the user will be working.  
7.  Select the **Default** check box to define the location as the only location where the employee can perform warehouse activities.  
8.  Repeat these steps to assign other employees to locations or assign non-default locations to existing warehouse employees.  

## <a name="see-also"></a>See Also  
[Warehouse Management](warehouse-manage-warehouse.md)  
[Inventory](inventory-manage-inventory.md)  
[Setting Up Warehouse Management](warehouse-setup-warehouse.md)     
[Assembly Management](assembly-assemble-items.md)    
[Design Details: Warehouse Management](design-details-warehouse-management.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
