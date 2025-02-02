---
title: Set up validation groups
TOCTitle: Set up validation groups
ms:assetid: 5872fd9d-ccf9-4f42-9595-b7af66701f79
ms:mtpsurl: https://technet.microsoft.com/library/Aa549068(v=AX.60)
ms:contentKeyID: 36811405
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project/category
- validation group
- validation setup
- category/worker
- worker/project
audience: Application User
ms.search.region: Global
---

# Set up validation groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

**This is preliminary documentation and is subject to change.**

Use validation in **Project management and accounting** for journal entry access control. You can provide or deny access to specific categories or projects to worker groups or individual workers when they enter transactions in journals.

1.  Click **Project management and accounting** \> **Setup** \> **Validation**.

2.  Depending on the type of group that you want to set up, click one of the following:
    
      - **Project/category validation groups**
    
      - **Worker/project validation groups**
    
      - **Worker/category validation groups**

3.  Click **New** or press CTRL+N to create a new validation group.

4.  In the **Remaining workers** area, in the **Legal entity** field, select the legal entity from which you want to assign workers to the validation group.
    
    If you are the borrowing legal entity, you can add workers that are loaned from different legal entities to your validation groups when you are setting up validation options that are used with intercompany timesheets.
    
    > [!NOTE]  
    > The <strong>Legal entity</strong> field is available on the <strong>Worker/category validation groups</strong> form and <strong>Worker/project validation groups</strong> form.
    
    > [!NOTE]  
    > <p>This control is available only if Microsoft Dynamics AX 2012 Feature Pack is installed.</p>

5.  On the **Projects**, **Worker**, or **Categories** FastTabs, add the appropriate projects, workers, or categories.

## See also

[About validation in projects](about-validation-in-projects.md)

  


