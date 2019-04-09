---
title: Configure Production Processes
description: To convert material into produced end items, production resources, such as bills of material, routings, machine operators, and machinery must be set up in the system.
documentationcenter: ''
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 09/04/2017
ms.author: sgroespe
ms.openlocfilehash: 3ff04009603768bc0ace7b454f6ebb056cf3a69b
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7003"
---
# <a name="setting-up-manufacturing"></a>Setting Up Manufacturing
To convert material into produced end items, production resources, such as bills of material, routings, machine operators, and machinery must be set up in the system.

Operators and machines are represented in the system as machine centers that may be organized in work centers and work center groups. When these resources are established, they can be loaded with operations according to the item's defined material (BOM) and process (routing) structure, and according to the capacity of the machine or work center. You can also set the production capacity of each resource. Capacity is defined by the work time available in the machine and work centers, and is governed by calendars for each level. A work center calendar specifies the working days or hours, shifts, holidays, and absence that determine the work center’s gross available capacity (typically measured in minutes). All of this is determined by defined efficiency and capacity values.  

When you have set up manufacturing, you can plan and execute production orders. For more information, see [Planning](production-planning.md) and [Manufacturing](production-manage-manufacturing.md).  

 The following table describes a sequence of tasks, with links to the topics that describe them.   

|**To**|**See**|  
|------------|-------------|  
|Configure the manufacturing features, such as defining shop floor work hours and selecting planning principles.|The **Manufacturing Setup** page.|  
|Define a standard working week in the manufacturing department in terms of starting and ending times of each work day and related work shift.|[How to: Create Shop Calendars](production-how-to-create-work-center-calendars.md)|  
|Organize fixed values and requirements of production resources as work centers or machine centers to govern their output of production performed.|[How to: Set Up Work Centers and Machine Centers](production-how-to-set-up-work-and-machine-centers.md)|
|Organize production operations in the required order and assign them to work or machine centers with the required work times.|[How to: Create Routings](production-how-to-create-routings.md)|
|Organize production components or subassemblies under a produced parent item and certify the BOM for execution at work centers.|[How to: Create Production BOMs](production-how-to-create-production-boms.md)|
|Make sure that the right component quantity is available when produced items are stocked in one unit of measure but produced in another.|[How to: Work With Manufacturing Batch Units of Measure](production-how-to-use-the-manufacturing-batch-unit-of-measure.md)|  
|Define families of production items with similar manufacturing processes to save consumption. For example, four pieces of the same item can be produced from one sheet and 10 pieces of another, different, item at the same time.|[How to: Work With Production Families](production-how-work-family.md)|
|Use standard tasks to simplify the creation of routings by quickly attaching extra information to recurring operations.|[How to: Set Up Standard Routing Lines](production-how-set-up-standard-routing-lines.md)|  
|Prepare work centers and routings to represent subcontracted production operations.|[How to: Subcontract Manufacturing](production-how-to-subcontract-manufacturing.md)|  

## <a name="see-also"></a>See Also
[Manufacturing](production-manage-manufacturing.md)    
[Planning](production-planning.md)   
[Inventory](inventory-manage-inventory.md)  
[Purchasing](purchasing-manage-purchasing.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
