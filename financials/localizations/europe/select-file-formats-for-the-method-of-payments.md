---
title: File formats for methods of payment | Microsoft Docs
description: This topic describes the two methods for getting file formats that you can use for methods of payment.
author: ShylaThompson
manager: AnnBe
ms.date: 2016-12-12 21:28:31
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
keywords: CustPaymMode, VendPaymMode
audience: Application User
ms.reviewer: 81
ms.suite: Released- Dynamics 365 for Operations version 1611
ms.custom: 262514
ms.assetid: 2bc39b0e-56f4-4c30-8502-8513054af074
ms.region: Belgium, France, Germany, Norway, Spain, Sweden, Switzerland
ms.author: v-lenest
translationtype: Human Translation
ms.sourcegitcommit: 744ac447b01dee241043ba27e3b1ffdcb0022a1b
ms.openlocfilehash: 25e22c6d40a1303d157c5d0907f85f84c325ba32


---

# <a name="file-formats-for-methods-of-payment"></a>File formats for methods of payment

This topic describes the two methods for getting file formats that you can use for methods of payment.

There are two methods that you can use to get file formats for use with methods of payment, electronic reporting (ER) file formats or X++ file formats. When you set up a method of payment for a customer or vendor, you indicate which file formats and standards should be used for payments and how payments will be processed. You can select from the following types of formats:

-   Export
-   Import
-   Return
-   Remittance

### <a name="method-1-electronic-reporting-file-formats"></a>Method 1: Electronic reporting file formats

For file formats that are based on ER configurations, you must import the configurations from Lifecycle Services (LCS). For more information, see [Download Electronic reporting configurations from Lifecycle Services](https://docs.microsoft.com/en-us/dynamics365/operations/dev-itpro/analytics-bi-reporting/download-electronic-reporting-er-configuration-from-lifecycle-services). After you import reporting configurations for those file formats, the imported formats will be available to select on the **Methods of payment** page. The process for importing and selecting file formats for Europe is similar to the procedure for Japan. For more details, see [Enable the JBA payment file format](https://ax.help.dynamics.com/en/wiki/enable-the-jba-payment-file-format/).

### <a name="method-2-x-file-formats"></a>Method 2: X++ file formats

To select file formats that are based on X++ code, complete the following steps.

1.  Go to the **Methods of payment** page.
2.  On the **File formats** FastTab, click **Setup**.
3.  Select the tab that corresponds with the file format type.
4.  Select a file format from the **Available** list and move it to the **Selected** list with the arrow control.
5.  Close the **File formats for methods of payment** page.
6.  On the **File formats** FastTab, select the file format to use for the method of payment from the appropriate file format field. The General electronic reporting options should be set to **No** for X++ file formats.





<!--HONumber=Feb17_HO3-->


