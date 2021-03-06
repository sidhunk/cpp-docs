---
title: "IRowsetInfoImpl::GetProperties | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["ATL.IRowsetInfoImpl.GetProperties", "IRowsetInfoImpl.GetProperties", "ATL::IRowsetInfoImpl::GetProperties", "IRowsetInfoImpl::GetProperties", "GetProperties"]
dev_langs: ["C++"]
helpviewer_keywords: ["GetProperties method"]
ms.assetid: 62c12063-28e0-4a06-ad4d-21c5c1e9ccea
caps.latest.revision: 8
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
---
# IRowsetInfoImpl::GetProperties
Returns the current settings for properties in the **DBPROPSET_ROWSET** group.  
  
## Syntax  
  
```  
  
      STDMETHOD ( GetProperties )(  
   const ULONG cPropertyIDSets,  
   const DBPROPIDSET rgPropertyIDSets[],  
   ULONG* pcPropertySets,  
   DBPROPSET** prgPropertySets   
);  
```  
  
#### Parameters  
 See [IRowsetInfo::GetProperties](https://msdn.microsoft.com/en-us/library/ms719611.aspx) in the *OLE DB Programmer's Reference*.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetInfoImpl Class](../../data/oledb/irowsetinfoimpl-class.md)   
 [IRowsetInfoImpl::GetReferencedRowset](../../data/oledb/irowsetinfoimpl-getreferencedrowset.md)   
 [IRowsetInfoImpl::GetSpecification](../../data/oledb/irowsetinfoimpl-getspecification.md)