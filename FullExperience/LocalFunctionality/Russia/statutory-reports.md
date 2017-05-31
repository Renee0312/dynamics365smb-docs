---
title: "Statutory Reports"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "official reports in Russia, statutory reporting"
  - "statutory reports, setting up"
ms.assetid: 87459ed2-6acd-4cc9-9632-8b8c6343b3bd
caps.latest.revision: 2
ms.author: "edupont"
translation.priority.ht: 
  - "ru-ru"
---
# Statutory Reports
[!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] lets you set up statutory reports so that you can import and export data for electronic tax reporting and other required documents.  
  
 After you have set up a report and specified the required information, you can export the report to Excel, and then print the report.  
  
## Getting Started with Statutory Reports  
 Use the windows based on the following key tables to set up and create statutory reports.  
  
|Tables|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
|------------|---------------------------------------|  
|[\($ T\_26569 Statutory Report Setup $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_26569-statutory-report-setup-$-.md)|Specifies information that is used to set up statutory reports including templates, formats, number series, and export destinations.|  
|[\($ T\_26573 Format Version $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_26573-format-version-$-.md)|Specifies setup information about the different report formats. This includes when to use which report, the XML schema to use, and the required data format.|  
|[\($ T\_26550 Statutory Report $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_26550-statutory-report-$-.md)|Specifies a list of statutory reports with detailed information, such as type, format version, and if the statutory report is currently active. From this window, you can define statutory report tables, requisites groups, the XML element lines, and you can export data.|  
|[\($ T\_26552 Statutory Report Table $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_26552-statutory-report-table-$-.md)|Specifies information that is required to set up reporting tables including scalability limits, templates, and standard text.<br /><br /> From this window, you can define table rows, columns, individual requisites, and data source mapping.|  
|[\($ T\_26553 Stat. Report Table Row $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_26553-stat.-report-table-row-$-.md)|Allows you to define row formats and functions for your statutory report tables.|  
|[\($ T\_26554 Stat. Report Table Column $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_26554-stat.-report-table-column-$-.md)|Allows you to define column formats for your statutory report tables.|  
|[\($ T\_26557 Stat. Report Requisites Group $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_26557-stat.-report-requisites-group-$-.md)|Specifies the conditions used to format and process statutory reports including export type, Microsoft Excel mapping, and cell quantity.|  
  
## Data for Statutory Reports  
 The statutory reports are based on account schedules and tax registers. For each statutory report that you set up in the **\($ N\_26550 Statutory Reports $\)** window, you define how the data maps to fields on tables in [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] by creating table mappings. In the **\($ N\_26552 Statutory Report Tables $\)** window, in the **\($ T\_26552 Int. Source Type $\)** field, you specify the area that the data comes from as described in the following table.  
  
|[!INCLUDE[bp_tableoption](../../ApplicationDesign/includes/bp_tableoption_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
|----------------------------------|---------------------------------------|  
|**Acc. Schedule**|The data is based on an account schedule.|  
|**Tax Register**|The data is based on a tax register. For more information, see [Tax Registers](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/tax-registers.md).|  
|**Tax Difference**|The data is based on a tax difference. For more information, see [Tax Differences](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/tax-differences.md).|  
|**Payroll Analysis Report**|The data is based on payroll analysis.|  
  
## See Also  
 [\($ T\_14919 Excel Template $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/-$-t_14919-excel-template-$-.md)   
 [Tax Accounting](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/tax-accounting.md)   
 [Tax Differences](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Russia/tax-differences.md)   
 [Selecting the Report Data Source](assetId:///79db2621-6067-4421-8fe6-3ef2baba1ecc)