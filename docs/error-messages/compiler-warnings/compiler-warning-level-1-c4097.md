---
title: "Compiler Warning (level 1) C4097 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C4097"]
dev_langs: ["C++"]
helpviewer_keywords: ["C4097"]
ms.assetid: 2525be51-fac2-43b2-b57c-3bbf1a2268f7
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# Compiler Warning (level 1) C4097
expected pragma parameter to be 'restore' or 'off'  
  
 A pragma was passed an invalid value.  
  
 The following sample generates C4097:  
  
```  
// C4097.cpp  
// compile with: /W1  
#pragma runtime_checks("",test)   // C4097  
// try the following line instead  
// #pragma runtime_checks("",off)  
  
int main() {  
}  
```