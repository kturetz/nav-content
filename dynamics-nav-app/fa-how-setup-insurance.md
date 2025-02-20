---
title: Set Up FA Insurance
description: You set up an insurance card and general insurance policy information to manage fixed asset insurance coverage.

documentationcenter: ''
author: SorenGP

ms.prod: "dynamics-nav-2018"
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: policy, coverage
ms.date: 06/02/2017
ms.author: edupont

---
# How to: Set Up Fixed Asset Insurance
To manage fixed asset insurance coverage, you must first set up some general insurance information and an insurance card per policy.

## To set up general insurance information
To use the insurance features in [!INCLUDE[d365fin](includes/d365fin_md.md)], you must set up some general insurance information.  

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Setups**, and then choose the related link.  
2. Fill in the fields as necessary. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## To set up insurance types
You can group your insurance policies into categories, such as insurance against theft or fire insurance. The insurance types are used on the insurance card.

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Insurance Types**, and then choose the related link.  
2. Fill in the fields as necessary.

## To set up insurance cards
You may accumulate information about each insurance policy on the insurance card.  

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Insurance**, and then choose the related link.  
2. In the **Insurance** window, choose the **New** action to create a  new insurance card.  
3. Fill in the fields as necessary.

## To set up insurance journal templates
[!INCLUDE[d365fin](includes/d365fin_md.md)] automatically creates an insurance journal template the first time that you open the **Insurance Journal** window, but you can set up additional journal templates. For more information, see [Working with General Journals](ui-work-general-journals.md).  

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Insurance Journal Templates**, and then choose the related link.  
2. Fill in the fields as necessary.

## To set up insurance journal batches
You can set up batches in an insurance journal template. The values in the journal batch are used as default values if the fields are not filled in on the journal lines. For more information, see [Work with General Journals](ui-work-general-journals.md)  

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Insurance Journal Templates**, and then choose the related link.  
2. Select an insurance journal template, and then choose the **Batches** action.
3. In the **Insurance Journal Batches** window, fill in the fields as necessary.

> [!NOTE]  
>   Numbers have a special function in journal names. If a journal template name or journal batch name contains a number, the number automatically advances by one every time that the journal is posted. For example, if HH1 is entered in the **Name** field, the journal name will change to HH2 after the journal named HH1 has been posted.

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Setting Up Fixed Assets](fa-setup.md)  
[Fixed Assets](fa-manage.md)  
[Finance](finance.md)  
[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
