---
title: Set Up Mailing Groups for Contacts
description: You can use mailing groups to identify groups of contacts that you want to receive the same information, for example, for a marketing campaign or promo.
documentationcenter: ''
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: marketing, campaign, promo, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.openlocfilehash: d96a8ea50202bcd55fe81a33735325e8def3696d
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7396"
---
# <a name="how-to-set-up-mailing-groups-for-contacts"></a>How to: Set Up Mailing Groups for Contacts
You can use mailing groups to identify groups of contacts that you want to receive the same information. For example, you can set up a mailing group for the contacts that you want to send a notification of an office move, or another group for sending holiday gifts.

Using mailing groups on contacts is a two-step process. First, you define the mailing group code. You only have to perform this step one time for each mailing group. Once you have a mailing group code, you can start to assign the code to contact companies.

## <a name="to-define-mailing-group-codes"></a>To define mailing group codes
The mailing group code defines the type or category of the group, such as MOVE for office move, or GIFT for holiday gift. You can have several industry group codes. To define the industry groups, you use the **Mailing Groups** window.

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Mailing Groups**, and then choose the related link.
2. Choose the **New** action, and fill in a code and description. The code can be a maximum of 11 characters, and can be any combination of numbers and letters.

## <a name="AssignMailGroupContact"></a> To assign mailing groups to a contact
1. Open the contact.
2. Choose the **Mailing Groups** action. The **Contact Mailing Groups** window opens.
3. In the **Mailing Groups Code** field, select the mailing group that you want to assign.

Repeat these steps to assign as many mailing groups as you want. You can also assign mailing groups from the contact list by following the same procedure.

The number of mailing groups you have assigned to the contact is displayed in the **No. of Mailing Groups** field in the **Segmentation** section in the **Contact** window.

After you have assigned mailing groups to your contacts, you can use this information to select contacts for your segments. For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).

## <a name="see-also"></a>See Also
[Creating Contact Companies](marketing-create-contact-companies.md)  
[Creating Contact Persons](marketing-create-contact-persons.md)  
[Working with Dynamics NAV](ui-work-product.md)
