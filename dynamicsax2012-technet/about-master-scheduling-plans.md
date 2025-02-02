---
title: About master scheduling plans
TOCTitle: About master scheduling plans
ms:assetid: 8c30f003-4176-4f56-be45-a9b44621301a
ms:mtpsurl: https://technet.microsoft.com/library/Aa498331(v=AX.60)
ms:contentKeyID: 37072061
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- master plan
- master planning
- master scheduling
- dynamic plan
- planning strategies
- planning strategy
- static plan
audience: Application User
ms.search.region: Global
---

# About master scheduling plans 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up and use various master plans to support your company's daily working operations, simulate different planning strategies that you want to monitor, and implement a company policy, such as a policy about internal performance or customer satisfaction. You can configure master plans in the **Master plans** form.

There are two types of plans:

  - **Static plan** – The master scheduling calculation uses the current data to generate a net requirements plan. This plan remains unchanged until the next time that you run master scheduling. It is an operating plan that various company personnel, such as a purchaser or production planner, can use to base their decisions on and perform their daily tasks and activities.

  - **Dynamic plan** – This plan starts with the same net requirements plan that was generated by master scheduling. However, you can update the dynamic plan every time that the master data changes. This could be when you create a new sales order, for example. This enables you to monitor the changing order network and item availability without disturbing the static plan that others are using for their work processes.

A company may choose to work with just a static plan, or it may use both static and dynamic plans. In addition, you can configure any master plan to reflect a particular strategy or address an issue. Examples are as follows:

  - Set higher inventory levels to guarantee against stockouts.

  - Set longer safety margins to protect against unreliable vendors.

You can also set up the starting dynamic plan so that it is updated with the new requirements plan every time that you run master scheduling. You can specify these settings in the **Master planning parameters** form.

## See also

[Run master scheduling](run-master-scheduling.md)

  


