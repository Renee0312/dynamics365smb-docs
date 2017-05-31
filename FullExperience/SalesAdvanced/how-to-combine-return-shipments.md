---
title: "How to: Combine Return Shipments"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "shipments, combining"
  - "returns, combining shipments"
  - "return shipments, combining"
  - "purchase returns, combining shipments"
  - "return orders, combining shipments"
  - "shipments, returns"
  - "purchase credit memos, combining return shipments"
ms.assetid: 13903618-4815-49eb-add4-d88d325b5161
caps.latest.revision: 7
ms.author: "sgroespe"
manager: "terryaus"
translation.priority.ht: 
  - "da-dk"
  - "de-at"
  - "de-ch"
  - "de-de"
  - "en-au"
  - "en-ca"
  - "en-gb"
  - "en-in"
  - "en-nz"
  - "es-es"
  - "es-mx"
  - "fi-fi"
  - "fr-be"
  - "fr-ca"
  - "fr-ch"
  - "fr-fr"
  - "is-is"
  - "it-ch"
  - "it-it"
  - "nb-no"
  - "nl-be"
  - "nl-nl"
  - "ru-ru"
  - "sv-se"
---
# How to: Combine Return Shipments
If you want to return items covered by different purchase return orders to the same vendor, then you can use the **Combine Return Shipments** function.  
  
 When you ship the items, you post the related purchase return orders as shipped and this creates posted purchase return shipments.  
  
 When you are ready to invoice these items, instead of invoicing each purchase return order separately, you can create a purchase credit memo and automatically copy the posted purchase return shipment lines to this document. Then you can post the purchase credit memo and conveniently invoice all the open purchase return orders at the same time.  
  
 When return shipments are combined on a credit memo and posted, then a posted purchase credit memo is created for the invoiced lines. The **Quantity Invoiced** field on the originating purchase return order is updated based on the invoiced quantity. However, this original purchase return order is not deleted, even if it has been fully received and invoiced, and you must therefore delete the purchase return order.  
  
 This procedure assumes that there are several purchase return orders for the vendor, and that they have been posted as shipped.  
  
### To combine return shipments  
  
1.  In the **Search** box, enter **Purchase Credit Memos**, and then choose the related link.  
  
2.  On the **Home** tab, in the **New** group, choose **New**.  
  
3.  Create a purchase credit memo. For more information, see [How to: Create Purchase Credit Memos](../Finance/how-to-create-purchase-credit-memos.md).  
  
4.  On the **Lines** FastTab, choose **Functions**, and then choose **Get Return Shipment Lines**.  
  
5.  Select multiple return shipment lines that you want to include in the invoice.  
  
     If an incorrect return shipment line was selected or you want to start over, you can just delete the lines on the purchase credit memo and then use the **Get Return Shipment Lines** function again.  
  
6.  On the **Actions** tab, in the **Posting** group, choose **Post**, and then choose the **OK** button.  
  
### To remove open purchase return orders after combined return shipment posting  
  
1.  In the **Search** box, enter **Delete Invoiced Purchase Return Orders**, and then choose the related link.  
  
2.  Enter filters to define which orders to delete, and then choose the **OK** button.  
  
3.  Alternatively, delete the individual orders manually. On the **Home** tab, in the **Manage** group, choose **Delete**.  
  
## See Also  
 [How to: Combine Receipts](../Finance/how-to-combine-receipts.md)   
 [How to: Combine Return Receipts](../Sales/how-to-combine-return-receipts.md)   
 [How to: Combine Shipments on a Single Invoice](../Sales/how-to-combine-shipments-on-a-single-invoice.md)   
 [How to: Get Return Shipment Lines for Item Charges](../Finance/how-to-get-return-shipment-lines-for-item-charges.md)   
 [How to: Process Purchase Returns](../Purchasing/how-to-process-purchase-returns.md)   
 [How to: Undo Quantity Posting on Posted Return Shipments](../Purchasing/how-to-undo-quantity-posting-on-posted-return-shipments.md)