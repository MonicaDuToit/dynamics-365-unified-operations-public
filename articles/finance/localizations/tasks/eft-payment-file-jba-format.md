--- 
# required metadata 
 
title: Generate EFT payment file with JBA format
description: This topic explains how to generate an EFT file with the JBA format. 
author: ShylaThompson
ms.date: 08/29/2018
ms.topic: business-process 
ms.prod:  
ms.technology:  
 
# optional metadata 
 
ms.search.form: LedgerJournalTable, LedgerJournalTransVendPaym   
audience: Application User 
# ms.devlang:  
ms.reviewer: kfend
# ms.tgt_pltfrm:  
# ms.custom:  
ms.search.region: Japan
# ms.search.industry: 
ms.author: roschlom
ms.search.validFrom: 2016-06-30 
ms.dyn365.ops.version: Version 7.0.0 
---
# Generate EFT payment file with JBA format

[!include [banner](../../includes/banner.md)]

In Japan, the Japanese Bankers Association (JBA) file format is commonly used for Electronic Fund Transfer (EFT) among banks. 



Use this task to learn how to generate an EFT file with the JBA format.



This task uses the JPMF demo company data.

1. Go to Accounts payable > Payments > Payment journal.
2. Click New.
3. In the Name field, type 'VendPay'.
4. Click Lines.
5. In the Account field, specify the values 'JPMF-000001'.
6. In the Debit field, enter a number.
7. Note the value in the Offset account field to reference later
8. Click Save.
9. Click Generate payments.
10. In the Method of payment field, select a method of payment that is enabled for the JBA file format..
11. In the File name field, Specify a file name for the generated file..
12. Use the value noted previously in the Bank account field
    * Select a Offset bank account in the vendor journal lines.  
13. Click OK.
    * Toggle the slider if you want to print the payment control report.  
14. Click OK.
    * A .zip file will be generated and you will be prompted to download the file.  
    * The Payment status will now switch to be 'Sent'.  



[!INCLUDE[footer-include](../../../includes/footer-banner.md)]
