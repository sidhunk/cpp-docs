---
title: "Compiler Warning (level 1) C4153 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C4153"]
dev_langs: ["C++"]
helpviewer_keywords: ["C4153"]
ms.assetid: 37a15754-9dba-470b-adda-c4b888064b3e
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# Compiler Warning (level 1) C4153
function/data pointer conversion in expression  
  
 A function pointer is converted to or from a data pointer. This conversion is allowed under Microsoft extensions (/Ze) but not under ANSI C.