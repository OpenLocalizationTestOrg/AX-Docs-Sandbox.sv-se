---
title: Import or manually create postal codes
description: This article explains how to import and manually create Dutch postal codes in the correct format. This topic includes information about feature that was added for Microsoft Dynamics 365 for Operations.
author: ShylaThompson
manager: AnnBe
ms.date: 2016-01-21 17 - 15 - 40
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 
ms.search.form: LogisticsAddressSetup
audience: Application User
ms.search.scope: Operations
ms.custom: 29901
ms.assetid: 0c9cbc5f-88ae-4ed2-8331-13ecea029f79
ms.search.region: Belgium, Netherlands, Sweden
ms.author: epopov
ms.dyn365.ops.intro: 01-11-2016
ms.dyn365.ops.version: Version 1611
translationtype: Human Translation
ms.sourcegitcommit: b97d17ceabfd25c52c5f0c1e96a123bae6941c5a
ms.openlocfilehash: d25f8967831ffbedab5aa7c161722c195caec729
ms.lasthandoff: 02/22/2017


---

# <a name="import-or-manually-create-postal-codes"></a>Import or manually create postal codes

This article explains how to import and manually create Dutch postal codes in the correct format. This topic includes information about feature that was added for Microsoft Dynamics 365 for Operations. 

The import process lets you update the ZIP/postal codes for a specific country/region. You can also create postal codes manually.

## <a name="import-zippostal-codes"></a>Import ZIP/postal codes
You can use the **Import ZIP/postal codes** page to import new postal codes into Microsoft Dynamics 365 for Operations. When you import the codes, the existing ZIP or postal codes are replaced with the new format, and any new codes are added.

For some countries, you must use the Data management framework to import codes, while for other countries only a upload file is required. Belgium, Netherlands, and Sweden require a file to upload.

**Note:**

-   For Belgium, the official webpage from the Belgian Post provides an official list of the postcodes and the corresponding city names. The import supports html file format.
-   For Netherlands, a third-party organization provides the file that contains postal codes. After the import is completed, all postal codes will appear in the format (NNNN AA).
-   For Sweden, Postnummerservice.se provides two types of files: Swedish postal codes and Swedish addresses. The import supports text file format for both types.

## <a name="create-zippostal-codes-manually"></a>Create ZIP/postal codes manually
Instead of importing codes, you can use the **Address setup** page to manually add new ZIP/postal codes.


