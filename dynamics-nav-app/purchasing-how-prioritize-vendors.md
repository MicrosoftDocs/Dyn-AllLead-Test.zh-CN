---
title: Assign a Priority Level to a Vendor
description: You can assign numbers to your vendors or suppliers to prioritize them and facilitate payment suggestions in Dynamics NAV.
documentationcenter: ''
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supplier, payment priority
ms.date: 03/29/2017
ms.author: sgroespe
ms.openlocfilehash: 82b315423372e56a36ce124aba4120dafc279662
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7234"
---
# <a name="how-to-prioritize-vendors"></a><span data-ttu-id="39d96-103">How to: Prioritize Vendors</span><span class="sxs-lookup"><span data-stu-id="39d96-103">How to: Prioritize Vendors</span></span>
[!INCLUDE[d365fin](includes/d365fin_md.md)] <span data-ttu-id="39d96-104">can suggest various payments to vendors, for example, payments that will be due soon or payments where a discount is available.</span><span class="sxs-lookup"><span data-stu-id="39d96-104">can suggest various payments to vendors, for example, payments that will be due soon or payments where a discount is available.</span></span> <span data-ttu-id="39d96-105">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="39d96-105">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>

<span data-ttu-id="39d96-106">First, you must prioritize your vendors by assigning numbers to them.</span><span class="sxs-lookup"><span data-stu-id="39d96-106">First, you must prioritize your vendors by assigning numbers to them.</span></span>

## <a name="to-prioritize-vendors"></a><span data-ttu-id="39d96-107">To prioritize vendors</span><span class="sxs-lookup"><span data-stu-id="39d96-107">To prioritize vendors</span></span>
1. <span data-ttu-id="39d96-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendors**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="39d96-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="39d96-109">Select the relevant vendor, and then choose **Edit**.</span><span class="sxs-lookup"><span data-stu-id="39d96-109">Select the relevant vendor, and then choose **Edit**.</span></span>
3. <span data-ttu-id="39d96-110">In the **Priority** field, enter a number.</span><span class="sxs-lookup"><span data-stu-id="39d96-110">In the **Priority** field, enter a number.</span></span>

[!INCLUDE[d365fin](includes/d365fin_md.md)] <span data-ttu-id="39d96-111">considers the lowest number, except 0, to have the highest priority.</span><span class="sxs-lookup"><span data-stu-id="39d96-111">considers the lowest number, except 0, to have the highest priority.</span></span> <span data-ttu-id="39d96-112">So, for example, if you use 1, 2, and 3, then 1 will have the highest priority.</span><span class="sxs-lookup"><span data-stu-id="39d96-112">So, for example, if you use 1, 2, and 3, then 1 will have the highest priority.</span></span>

<span data-ttu-id="39d96-113">If you do not want to prioritize a vendor, leave the **Priority** field blank.</span><span class="sxs-lookup"><span data-stu-id="39d96-113">If you do not want to prioritize a vendor, leave the **Priority** field blank.</span></span> <span data-ttu-id="39d96-114">Then, if you use the payment suggestion feature, the vendor will be listed after all the vendors that have a priority number.</span><span class="sxs-lookup"><span data-stu-id="39d96-114">Then, if you use the payment suggestion feature, the vendor will be listed after all the vendors that have a priority number.</span></span> <span data-ttu-id="39d96-115">You can enter as many priority levels as necessary.</span><span class="sxs-lookup"><span data-stu-id="39d96-115">You can enter as many priority levels as necessary.</span></span>

## <a name="see-also"></a><span data-ttu-id="39d96-116">See Also</span><span class="sxs-lookup"><span data-stu-id="39d96-116">See Also</span></span>
[<span data-ttu-id="39d96-117">Setting Up Purchasing</span><span class="sxs-lookup"><span data-stu-id="39d96-117">Setting Up Purchasing</span></span>](purchasing-setup-purchasing.md)  
[<span data-ttu-id="39d96-118">Managing Payables</span><span class="sxs-lookup"><span data-stu-id="39d96-118">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="39d96-119">Working with</span><span class="sxs-lookup"><span data-stu-id="39d96-119">Working with</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
