---
title: Controller profitability analysis report (ControllerProfitabilityAnalysis)
TOCTitle: Controller profitability analysis report (ControllerProfitabilityAnalysis)
ms:assetid: 1d6db11a-4cbe-4473-98f6-6a2f7155e803
ms:mtpsurl: https://technet.microsoft.com/library/Hh556860(v=AX.60)
ms:contentKeyID: 39509590
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.ControllerProfitabilityAnalysis
---

# Controller profitability analysis report (ControllerProfitabilityAnalysis) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays key performance indicator (KPI) information for a controller.


> [!NOTE]
> <P>This report is designed for use on Role Centers.</P>



## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>ControllerProfitabilityAnalysis</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ControllerProfitabilityAnalysis</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerControllerProfitAnalysisSmall</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Controller Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BASEENUM\_FiscalQuarter table

  - BICOMPANYVIEW table

  - LEDGERPERIODDATEDIMENSIONVIEW table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


