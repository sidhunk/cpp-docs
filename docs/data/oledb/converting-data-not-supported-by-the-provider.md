---
title: "Converting Data Not Supported by the Provider | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: ["C++"]
helpviewer_keywords: ["OLE DB provider templates, unsupported data types"]
ms.assetid: f495e50f-530a-4fab-ab54-e0c359785845
caps.latest.revision: 7
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
---
# Converting Data Not Supported by the Provider
When the consumer requests a data type that is not supported by the provider, the OLE DB provider template code for `IRowsetImpl::GetData` calls Msdadc.dll to convert the data type.  
  
 If you implement an interface like `IRowsetChange` that requires data conversion, you can call Msdaenum.dll to do the conversion. Use `GetData`, defined in Atldb.h, as an example.  
  
## See Also  
 [Working with OLE DB Provider Templates](../../data/oledb/working-with-ole-db-provider-templates.md)