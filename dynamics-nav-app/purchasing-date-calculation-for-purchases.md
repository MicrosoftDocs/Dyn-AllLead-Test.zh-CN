---
title: Date Calculation for Purchases
description: The program automatically calculates the date on which you must order an item to have it in inventory on a certain date. This is the date on which you can expect items ordered on a particular date to be available for picking.
documentationcenter: ''
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 08/10/2017
ms.author: sgroespe
ms.openlocfilehash: 60c349e91078a2d2da6c994f62abea985fed2f76
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7211"
---
# <a name="date-calculation-for-purchases"></a>Date Calculation for Purchases
[!INCLUDE[d365fin](includes/d365fin_md.md)] automatically calculates the date on which you must order an item to have it in inventory on a certain date. This is the date on which you can expect items ordered on a particular date to be available for picking.  

If you specify a requested receipt date on a purchase order header, then the calculated order date is the date on which the order must be placed to receive the items on the date that you requested. Then, the date on which the items are available for picking is calculated and entered in the **Expected Receipt Date** field.  

If you do not specify a requested receipt date, then the order date on the line is used as the starting point for calculating the date on which you can expect to receive the items and the date on which the items are available for picking.  

## <a name="calculating-with-a-requested-receipt-date"></a>Calculating with a Requested Receipt Date  
If there is a requested receipt date on the purchase order line, then that date is used as the starting point for the following calculations.  

- requested receipt date - lead time calculation = order date  
- requested receipt date + inbound whse. handling time + safety lead time = expected receipt date  

If you entered a requested receipt date on the purchase order header, then that date is copied to the corresponding field on all the lines. You can change this date on any of the lines, or you can remove the date on the line.  

## <a name="calculating-without-a-requested-delivery-date"></a>Calculating without a Requested Delivery Date  
If you enter a purchase order line without a requested delivery date, then the **Order Date** field on the line is filled with the date in the **Order Date** field on the purchase order header. This is either the date that you entered or the work date. The following dates are then calculated for the purchase order line, with the order date as the starting point.  

- order date + lead time calculation = planned receipt date  
- planned receipt date + inbound whse. handling time + safety lead time = expected receipt date  

If you change the order date on the line, such as when items are not available at your vendor until a later date, then the relevant dates on the line are automatically recalculated.  

If you change the order date on the header, then that date is copied to the **Order Date** field on all the lines, and all the related date fields are then recalculated.  

## <a name="see-also"></a>See Also  
 [Date Calculation for Sales](sales-date-calculation-for-sales.md)   
 [How to: Calculate Order Promising Dates](sales-how-to-calculate-order-promising-dates.md)  
 [Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
