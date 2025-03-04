---
title: "Insert Surround-with Transact-SQL snippets"
description: Learn how to insert a surround-with snippet to serve as a starting point for placing statements in code blocks.
ms.custom: seo-lt-2019
ms.date: "03/14/2017"
ms.service: sql
ms.subservice: ssms
ms.reviewer: ""
ms.topic: conceptual
helpviewer_keywords: 
  - "snippets [Transact-SQL], surround with"
  - "IntelliSense [SQL Server], surround with snippets"
  - "Transact-SQL snippets, surround with"
ms.assetid: 5b5a8c6c-968e-4361-a7f5-9e2ac186d927
author: markingmyname
ms.author: maghan
monikerRange: ">=aps-pdw-2016||=azuresqldb-current||=azure-sqldw-latest||>=sql-server-2016||>=sql-server-linux-2017||=azuresqldb-mi-current"
---
# Insert Surround-with Transact-SQL snippets
[!INCLUDE[SQL Server Azure SQL Database Synapse Analytics PDW](../../includes/applies-to-version/sql-asdb-asdbmi-asa-pdw.md)]
  A surround-with snippet is a template you can use as a starting point when enclosing a set of [!INCLUDE[tsql](../../includes/tsql-md.md)] statements in a BEGIN, IF, or WHILE block.  
  
## Inserting Surround-with Snippets  
 Surround-with snippets can be launched by one of three ways: through a keyboard shortcut, through the **Edit** menu, and through the context menu.  
  
 After inserting the snippet, you must change the replacement text to form a valid [!INCLUDE[tsql](../../includes/tsql-md.md)] statement. For more information, see [Complete Transact-SQL Snippets](./complete-transact-sql-snippets.md).  
  
#### To insert a surround-with snippet  
  
1.  In the [!INCLUDE[ssDE](../../includes/ssde-md.md)] Query Editor window, select the set of statements to be included in the block.  
  
2.  Use one of these three methods to display the list of surround-with snippets:  
  
    -   Type CTRL+K, CTRL+S.  
  
    -   From the **Edit** menu, point to **IntelliSense**, and then select the **Surround With** command.  
  
    -   Right-click the selected text, and then select the **Surround With** command from the context menu.  
  
3.  Select the name of the snippet (BEGIN, IF, or WHILE) from the list either by using the mouse, or by typing the name of the snippet and pressing TAB or ENTER.  
  
## See Also  
 [Insert Transact-SQL Snippets](./insert-transact-sql-snippets.md)  
  
