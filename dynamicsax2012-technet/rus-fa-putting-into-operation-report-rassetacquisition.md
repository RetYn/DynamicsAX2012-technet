---
title: (RUS) FA putting into operation report (RAssetAcquisition)
TOCTitle: (RUS) FA putting into operation report (RAssetAcquisition)
ms:assetid: 8e982f96-e06b-4af2-9a89-ad5f12679d61
ms:mtpsurl: https://technet.microsoft.com/library/JJ955219(v=AX.60)
ms:contentKeyID: 51831851
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetAcquisition
---

# (RUS) FA putting into operation report (RAssetAcquisition) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The FA putting into operation report displays the costs of fixed assets, the acquisition costs, and the costs that are incurred to put the fixed assets into operation. This report is generated periodically by accountants to view the original costs of the fixed assets, and the costs to put them into operation.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>FA accounting type</strong></p></td>
<td><p>Select the value model of the fixed assets to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reporting date</strong></p></td>
<td><p>Select a date to generate the report for. The fixed assets that are acquired and put into operation up to the selected date are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The inventory number of the fixed asset.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

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
<td><p>RAssetAcquisition</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetAcquisition</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetAcquisition</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>FA putting into operation</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetAcquisitionTMP table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the RAssetAcquisitionDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Fixed assets (modified form)](https://technet.microsoft.com/library/jj923580\(v=ax.60\))

  


