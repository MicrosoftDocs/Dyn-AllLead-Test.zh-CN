---
title: Set Up Marketing and Contact Management Information
description: You can set up marketing and contact management in Dynamics NAV to optimize relationships with prospects or customers, and improve campaigns and promotions.
documentationcenter: ''
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect, client, customer, campaign, promo
ms.date: 06/06/2017
ms.author: jswymer
ms.openlocfilehash: 7839597fbf7a676d34ef88166a27bd3751b766a8
ms.sourcegitcommit: 02827d275e1341d5c9ddb7b314b43b48a9ac96e2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2019
ms.locfileid: "7173"
---
# <a name="setting-up-relationship-management"></a>Setting Up Relationship Management
Before you get started working with your contacts and marketing interests, there are a few decisions and steps that you should take to set up how the marketing area manages certain aspects of your contacts. For example, you can decide whether to synchronize the contact card with the customer card, vendor card, and bank account card, how number series are defined, or what the standard salutation should be when writing to your contacts.

Managing your contacts and having a strategy in place to identify, attract, and retain customers will help optimize your business and increase customer satisfaction. Using a good contact management system will also help you create and maintain relationships with your customers. Communication is the key to these relationships. Being able to tailor communication with potential and existing customers, vendors, and business partners according to their needs, is necessary for companies to succeed. Establishing a strategy and defining how your company uses contact information is a primary step. This information will be viewed by many different groups in your company, so having a good system in place will help everyone be more productive.

You set up the marketing and contact management from the **Marketing Setup** window. To open the **Marketing Setup** window, choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Marketing Setup**, and then choose the related link.

## <a name="automatically-copying-specific-information-from-the-contact-companies-to-the-contact-persons"></a>Automatically Copying Specific Information from the Contact Companies to the Contact Persons
Some information about contact companies is identical to the information about the contact persons working within these companies, for example, the address details. In the **Inheritance** section of the **Marketing Setup** window, you can set the application to automatically copy specific fields from the contact company card to the contact person card each time you create a contact person for a contact company. For example, you can select to copy the salesperson code, address details (address, address 2, city, post code, and county), communication details (fax number, telex answer back, and phone number), and more.

When you modify one of these fields on the contact company card, the program will automatically modify the field on the contact person card (unless you have manually modified the field on the contact person card).

For more information, see [How to: Create Contact Persons](marketing-how-create-contact-persons.md).

## <a name="using-predefined-defaults-on-new-contacts"></a>Using Predefined Defaults on New Contacts
You can decide that the application automatically assigns a specific language code, territory code, salesperson code, and country/region code as defaults to each new contact you create. You can also enter a default sales cycle code that the program automatically assigns to each new opportunity you create.

The inheritance of fields overwrites the default values you have set up. For example, if you have set up English as the default language, but the contact company's language is German, the program will automatically assign German as the language code for the contact persons recorded for that company.

<!--You can also setup a default salutation that the program automatically assigns to your contacts. You can use these salutations in your interaction template attachments (for example, Microsoft Word documents). When setting up a default salutation, you can enter a salutation text and a salutation format. For example, if the salutation text is Dear, and the salutation format is Salutation Text + Title + Name, the program will automatically enter Dear Mr. John Smith as a salutation for a contact called John Smith.-->

## <a name="automatically-recording-interactions"></a>Automatically Recording Interactions
[!INCLUDE[d365fin](includes/d365fin_md.md)] can automatically record sales and purchase documents as interactions (for example, orders, invoices, receipts, and so on), as well as emails, phone calls, and cover sheets.

For more information, see [Automatically Record Interactions with Contacts](marketing-auto-record-interactions.md).

## <a name="synchronizing-contacts-with-customers-and-more"></a>Synchronizing Contacts with Customers and More
In order to synchronize the contact card with the customer card, the vendor card and the bank account card, you must select a business relation code for customers, vendors, and bank accounts. For example, you can only link a contact with an existing customer if you have selected a business relation code for customers in the **Marketing Setup** window.

For more information, see [Synchronizing Contacts with Customers, Vendors and Bank Accounts](marketing-synchronize-contacts-customers-vendors-bank-accounts.md).

## <a name="assigning-a-number-series-to-contacts-and-opportunities"></a>Assigning a Number Series to Contacts and Opportunities
You can set up a number series for contacts and opportunities. If you have set up a number series for contacts, when you create a contact, and press Enter in the No. field on the contact card, the program automatically enters the next available contact number.

For more information about number series, see [How to: Create Number Series](ui-create-number-series.md).

## <a name="searching-for-duplicate-contacts-when-contacts-are-created"></a>Searching for Duplicate Contacts when Contacts are Created
You can choose to have the program automatically search for duplicates each time you create a contact company, or you can choose to search manually after you have created contacts. You can also choose to have the program update the search strings automatically each time you modify contact information or create a contact. You can decide the search hit percentage, that is, the percentage of identical strings two contacts must have for the program to consider them as duplicates.

## <a name="see-also"></a>See Also
[Managing Contacts](marketing-contacts.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
