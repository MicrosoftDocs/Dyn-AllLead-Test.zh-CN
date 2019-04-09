---
title: Scenario Example - Defining Dynamic Allocations Based on Items Sold
description: This topic shows an example of how to define allocations by using the dynamic allocation method. In the example, you change the dynamic allocation of the costs for the SALES cost center to support the new cost object IT EQUIPMENT. IT EQUIPMENT packages have item numbers in the range from 8904-W to 8924-W. You use the previous year’s sales figures to calculate the share. The allocation is posted to the helping cost type 9903.
documentationcenter: ''
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 07/01/2017
ms.author: sgroespe
ms.openlocfilehash: 25d9607edbdf438eaf43737824cf848aeb92852d
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7154"
---
# <a name="scenario-example-defining-dynamic-allocations-based-on-items-sold"></a><span data-ttu-id="81b5b-107">Scenario Example: Defining Dynamic Allocations Based on Items Sold</span><span class="sxs-lookup"><span data-stu-id="81b5b-107">Scenario Example: Defining Dynamic Allocations Based on Items Sold</span></span>
<span data-ttu-id="81b5b-108">This topic shows an example of how to define allocations by using the dynamic allocation method.</span><span class="sxs-lookup"><span data-stu-id="81b5b-108">This topic shows an example of how to define allocations by using the dynamic allocation method.</span></span> <span data-ttu-id="81b5b-109">In the example, you change the dynamic allocation of the costs for the SALES cost center to support the new cost object IT EQUIPMENT.</span><span class="sxs-lookup"><span data-stu-id="81b5b-109">In the example, you change the dynamic allocation of the costs for the SALES cost center to support the new cost object IT EQUIPMENT.</span></span> <span data-ttu-id="81b5b-110">IT EQUIPMENT packages have item numbers in the range from 8904-W to 8924-W.</span><span class="sxs-lookup"><span data-stu-id="81b5b-110">IT EQUIPMENT packages have item numbers in the range from 8904-W to 8924-W.</span></span> <span data-ttu-id="81b5b-111">You use the previous year’s sales figures to calculate the share.</span><span class="sxs-lookup"><span data-stu-id="81b5b-111">You use the previous year’s sales figures to calculate the share.</span></span> <span data-ttu-id="81b5b-112">The allocation is posted to the helping cost type 9903.</span><span class="sxs-lookup"><span data-stu-id="81b5b-112">The allocation is posted to the helping cost type 9903.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="81b5b-113">The example uses the demo data in the [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="81b5b-113">The example uses the demo data in the [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

## <a name="to-define-dynamic-allocations-based-on-items-sold-in-the-previous-year"></a><span data-ttu-id="81b5b-114">To define dynamic allocations based on items sold in the previous year</span><span class="sxs-lookup"><span data-stu-id="81b5b-114">To define dynamic allocations based on items sold in the previous year</span></span>  

1.  <span data-ttu-id="81b5b-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cost Allocations**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="81b5b-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cost Allocations**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="81b5b-116">In the **Cost Allocation** window, choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="81b5b-116">In the **Cost Allocation** window, choose the **New** action.</span></span>  
3.  <span data-ttu-id="81b5b-117">In the **ID** field, press Enter or enter an ID.</span><span class="sxs-lookup"><span data-stu-id="81b5b-117">In the **ID** field, press Enter or enter an ID.</span></span>  
4.  <span data-ttu-id="81b5b-118">In the **Level** field, enter **1**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-118">In the **Level** field, enter **1**.</span></span>  
5.  <span data-ttu-id="81b5b-119">In the **Valid From** and **Valid To** fields, enter appropriate dates.</span><span class="sxs-lookup"><span data-stu-id="81b5b-119">In the **Valid From** and **Valid To** fields, enter appropriate dates.</span></span>  
6.  <span data-ttu-id="81b5b-120">In the **Cost Center Code** field, enter **SALES**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-120">In the **Cost Center Code** field, enter **SALES**.</span></span>  
7.  <span data-ttu-id="81b5b-121">In the **Credit to Cost Type** field, enter the cost type **9903**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-121">In the **Credit to Cost Type** field, enter the cost type **9903**.</span></span>  
8.  <span data-ttu-id="81b5b-122">In the **Target Cost Type** field, enter the cost type **9903**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-122">In the **Target Cost Type** field, enter the cost type **9903**.</span></span>  
9. <span data-ttu-id="81b5b-123">In the **Target Cost Object** field, choose **New** to create a new cost object IT EQUIPMENT and fill in fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="81b5b-123">In the **Target Cost Object** field, choose **New** to create a new cost object IT EQUIPMENT and fill in fields as necessary.</span></span> <span data-ttu-id="81b5b-124">Select **IT EQUIPMENT**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-124">Select **IT EQUIPMENT**.</span></span> <span data-ttu-id="81b5b-125">Leave the **Target Cost Center** field blank.</span><span class="sxs-lookup"><span data-stu-id="81b5b-125">Leave the **Target Cost Center** field blank.</span></span>  
10. <span data-ttu-id="81b5b-126">In the **Allocation Target Type** field, select **All Costs** to define how all accumulated costs are allocated.</span><span class="sxs-lookup"><span data-stu-id="81b5b-126">In the **Allocation Target Type** field, select **All Costs** to define how all accumulated costs are allocated.</span></span>  
11. <span data-ttu-id="81b5b-127">In the **Base** field, select the allocation base **Items Sold (Amount)**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-127">In the **Base** field, select the allocation base **Items Sold (Amount)**.</span></span>  
12. <span data-ttu-id="81b5b-128">In the **No. Filter** field, enter **8904-W..8924-W**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-128">In the **No. Filter** field, enter **8904-W..8924-W**.</span></span>  
13. <span data-ttu-id="81b5b-129">In the **Date Filter Code** field, enter **Last Year**.</span><span class="sxs-lookup"><span data-stu-id="81b5b-129">In the **Date Filter Code** field, enter **Last Year**.</span></span>  
14. <span data-ttu-id="81b5b-130">Choose the **Calculate Allocation Key** action to calculate the share.</span><span class="sxs-lookup"><span data-stu-id="81b5b-130">Choose the **Calculate Allocation Key** action to calculate the share.</span></span>  

    > [!IMPORTANT]  
    >  [!INCLUDE[d365fin](includes/d365fin_md.md)] <span data-ttu-id="81b5b-131">uses the previous years’ sales figures to calculate a share of 1596.50 LCY with 100 percent for the IT EQUIPMENT packages.</span><span class="sxs-lookup"><span data-stu-id="81b5b-131">uses the previous years’ sales figures to calculate a share of 1596.50 LCY with 100 percent for the IT EQUIPMENT packages.</span></span> <span data-ttu-id="81b5b-132">This means that all of the items sold last year will be allocated to the cost object IT EQUIPMENT.</span><span class="sxs-lookup"><span data-stu-id="81b5b-132">This means that all of the items sold last year will be allocated to the cost object IT EQUIPMENT.</span></span>  

## <a name="see-also"></a><span data-ttu-id="81b5b-133">See Also</span><span class="sxs-lookup"><span data-stu-id="81b5b-133">See Also</span></span>  
 [<span data-ttu-id="81b5b-134">Setting Filters for Dynamic Allocation Bases</span><span class="sxs-lookup"><span data-stu-id="81b5b-134">Setting Filters for Dynamic Allocation Bases</span></span>](finance-setting-filters-for-dynamic-allocation-bases.md)   
 [<span data-ttu-id="81b5b-135">How to: Set Up Allocation Source and Targets</span><span class="sxs-lookup"><span data-stu-id="81b5b-135">How to: Set Up Allocation Source and Targets</span></span>](finance-how-to-set-up-allocation-source-and-targets.md)   
 [<span data-ttu-id="81b5b-136">Defining and Allocating Costs</span><span class="sxs-lookup"><span data-stu-id="81b5b-136">Defining and Allocating Costs</span></span>](finance-define-and-allocate-costs.md)   
 [<span data-ttu-id="81b5b-137">Terminology in Cost Accounting</span><span class="sxs-lookup"><span data-stu-id="81b5b-137">Terminology in Cost Accounting</span></span>](finance-terminology-in-cost-accounting.md)   
 [<span data-ttu-id="81b5b-138">About Cost Accounting</span><span class="sxs-lookup"><span data-stu-id="81b5b-138">About Cost Accounting</span></span>](finance-about-cost-accounting.md)
