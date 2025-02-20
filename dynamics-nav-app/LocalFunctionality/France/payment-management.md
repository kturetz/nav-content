---
    title: Payment Management
    description: You can manage bills of exchange, electronic payments, and vendor payments using the payment management function.

    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2018"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: edupont

---
# Payment Management
[!INCLUDE[navnow](../../includes/navnow_md.md)] allows you to manage bills of exchange, electronic payments, and vendor payments using the payment management function.  

You can manage customer and vendor payments using payment slips. Before you create a payment slip, you must set up the following prerequisites:  

- Payment class – The type of payment that you want to perform, for example, bill of exchange, electronic payment, or check. For more information, see [How to: Set Up Payment Classes](how-to-set-up-payment-classes.md).  

- Payment status – The progress level of a payment document. You must define a set of statuses for each payment class. For more information, see [How to: Set Up Payment Statuses](how-to-set-up-payment-statuses.md).  

- Payment steps – A payment that is executed at a specified time. After a payment step is completed, you can move the payment document from one status to another. If a step involves posting debit or credit entries, you must define additional actions in the **Payment Step Ledger** table. For more information, see [How to: Set Up Payment Steps](how-to-set-up-payment-steps.md).  

- Payment address for vendors and customers – The address that is used for a vendor or a customer at the time of settlement. The payment address can be different from the vendor’s or customer's default address. For more information, see [How to: Set Up Payment Addresses](how-to-set-up-payment-addresses.md).  

You can also transfer your payment management setup information to an external disk so that you can use the same parameters for another company with similar requirements. You can export the payment data in the following formats:  

- ETEBAC – To create a bill of exchange remittance.  
- Withdraw – To create a customer payment withdrawal (direct debit).  
- Transfer – To create a vendor payment transfer (credit transfer).  

## Managing Payment Slips and Files  
You can create payment slips to manage customer payments and vendor payments. After creating the payment slip, you must post it.  

These payment slips can then be converted into payment files, which can be sent to the bank electronically.  

For more information, see [How to: Create Payment Slips](how-to-create-payment-slips.md).  

## Archiving Payment Slips  
You can separate a fully processed payment slip from the active payment slips by archiving it. You can manually archive an individual payment slip or you can automatically archive a batch of payment slips. For more information, see [How to: Archive Payment Slips](how-to-archive-payment-slips.md).  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[How to: Set Up Payment Classes](how-to-set-up-payment-classes.md)   
 [How to: Set Up Payment Statuses](how-to-set-up-payment-statuses.md)   
 [How to: Set Up Payment Steps](how-to-set-up-payment-steps.md)   
 [How to: Set Up Payment Addresses](how-to-set-up-payment-addresses.md)   
 [How to: Create Payment Slips](how-to-create-payment-slips.md)   
 [How to: Post Payment Slips](how-to-post-payment-slips.md)   
 [How to: Archive Payment Slips](how-to-archive-payment-slips.md)   
 [How to: Export or Import Payment Management Setup Parameters](how-to-export-or-import-payment-management-setup-parameters.md)   
 [France Local Functionality](france-local-functionality.md)
