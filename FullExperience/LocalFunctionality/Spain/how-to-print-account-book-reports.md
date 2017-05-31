---
title: "How to: Print Account Book Reports"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "account book reports"
ms.assetid: b0f15595-6434-4291-bd49-588996e80d15
caps.latest.revision: 14
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "es-es"
---
# How to: Print Account Book Reports
Account book reports display all the general ledger entries created in a specific period. The two account book reports are:  
  
-   **Official Account Book** report \- Displays information for every general ledger entry, grouped by transaction.  
  
-   **Official Account Summarized Book** report \- Displays a summary of general entries, grouped by heading or posting accounts.  
  
 When sending these reports to the authorities or auditors, you can include additional pages that will precede your report. To do this, you need to manually set the report's first page number. For example, if you have three pages of information preceding your report, you can set the first page of the report to indicate that it is page 4.  
  
### To print an official account book report  
  
1.  In the **Search** box, enter **Account \- Official Acc. Book**, and then choose the related link.  
  
2.  In the **Options** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ R\_10706\_F\_1\_1 Closing Transaction Description $\)**|Enter the description for the closing period transaction.|  
    |**\($ R\_10706\_F\_1\_5 Opening Transaction Description $\)**|Enter the description for the opening period transaction.|  
    |**\($ R\_10706\_F\_1\_7 First Page $\)**|Enter the number that you want to include on the first page of the report.|  
    |**\($ R\_10706\_F\_1\_2 Show Amounts in Add. Currency $\)**|Select to show the report amounts in additional reporting currency \(ACY\).|  
  
3.  In the **G\\L Register** FastTab, select appropriate filters.  
  
4.  Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.  
  
### To print an official account summarized book report  
  
1.  In the **Search** box, enter **Official Acc.Summarized Book**, and then choose the related link.  
  
2.  In the **Options** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ R\_10716\_F\_1\_7 From Date $\)**|Enter the start date of the report.|  
    |**\($ R\_10716\_F\_1\_6 To Date $\)**|Enter the end date of the report.|  
    |**\($ R\_10716\_F\_1\_3 Include Closing Entries $\)**|Select to include the closing entries in the report.|  
    |**\($ R\_10716\_F\_1\_1 Show Amounts in Add. Currency $\)**|Select to show the report amounts in additional reporting currency \(ACY\).|  
    |**\($ R\_10716\_F\_1\_10 First page $\)**|Enter the number that you want to include on the first page of the report.|  
    |**\($ R\_10716\_F\_1\_1100000 Account Type $\)**|Select **Posting** or **Heading**. **Posting** implies that entries can be posted to the account, and **Heading** implies that entries cannot be posted to the account.|  
  
3.  Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.  
  
## See Also  
 [Spain Local Functionality](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Spain/spain-local-functionality.md)   
 [\($ R\_10706 Account \- Official Acc. Book $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Spain/-$-r_10706-account-official-acc.-book-$-.md)   
 [\($ R\_10716 Official Acc. Summarized Book $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Spain/-$-r_10716-official-acc.-summarized-book-$-.md)