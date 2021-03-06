---
title: "UPPER (Azure Stream Analytics) | Microsoft Docs"
description: "Returns a character expression with lowercase character data converted to uppercase. "
applies_to: 
  - "Azure"
services: stream-analytics
author: mamccrea
manager: kfile

ms.service: stream-analytics
ms.topic: reference
ms.assetid: 36eeda67-4fe9-46ff-b5cb-5a53244f3ed3
caps.latest.revision: 6
ms.workload: data-services
ms.date: 04/22/2016
ms.author: mamccrea
---
# UPPER (Azure Stream Analytics)
  Returns a character expression with lowercase character data converted to uppercase.  
  
 ## Syntax  
  
```  
UPPER ( string_expression )  
```  
  
## Arguments  
 **string_expression**  
  
 Is the string expression to be evaluated. string_expression can be a constant or column of type nvarchar(max)  
  
## Return Types  
 nvarchar(max)  
  
## Examples  
  
```SQL  
SELECT TollId, EntryTime, UPPER(LicensePlate) AS LicensePlate_Upper  
FROM Input  
```  
  
## See Also  
 [LOWER &#40;Azure Stream Analytics&#41;](lower-azure-stream-analytics.md)  
  
  
