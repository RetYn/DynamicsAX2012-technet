---
title: Perform a catalog area analysis
TOCTitle: Perform a catalog area analysis
ms:assetid: 64af9179-b487-4f09-8ebe-23c1a859c8c6
ms:mtpsurl: https://technet.microsoft.com/library/Dn497781(v=AX.60)
ms:contentKeyID: 62200082
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRCatalogPage
- Forms.MCRPageTypeTable
- Forms.MCRCatalogSection
- Forms.MCRCatalogProductPage
- Forms.MCRPagePositionTable
- MsDynAx060.Forms.MCRPagePositionTable
- MsDynAx060.Forms.MCRCatalogProductPage
- MsDynAx060.Forms.MCRPageTypeTable
- MsDynAx060.Forms.MCRCatalogSection
- MsDynAx060.Forms.MCRCatalogPage
- catalog area analysis
- page area
- page layout
- square inch analysis
audience: Application User
ms.search.region: Global
---

# Perform a catalog area analysis 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to perform an analysis of the catalog area in a printed catalog. This analysis helps you determine whether page space is being used efficiently to generate sales. To perform this analysis, you specify where each product appears on the page, the amount of space that is given to the product, and the total cost of producing the page. The sales for each item can then be compared to the cost of displaying the item on the page.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Related setup tasks</p></td>
<td><p><a href="create-call-center-catalogs.md">Create call center catalogs</a></p></td>
</tr>
</tbody>
</table>


## 1\. Define page types, page positions, and catalog sections

Before you specify where products are put on the page, you must define the following types of data:

  - Page types—The types of pages that a catalog can contain, such as front cover, back cover, and general page.

  - Page positions—The areas on the page where you can put a product.

  - Catalog sections—The sections of the catalog. You can have sections for items on sale, regular-priced items, ordering instructions, and so on.

To define page types, page positions, and catalog sections, follow these steps.

1.  Click **Call center** \> **Setup** \> **Pages** \> **Page positions**.

2.  Click **New**, and then enter a unique name and a brief description for the first page position. Repeat this step to add all the page positions that you require.

3.  Close the **Page positions** form.

4.  Click **Call center** \> **Setup** \> **Pages** \> **Page types**.

5.  Click **New**, and then enter a unique name and a brief description for the first page type. Repeat this step to add all the page types that you require.

6.  Close the **Page types** form.

7.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

8.  Double-click the name of the catalog to work with. On the **Action Pane**, in the **Call center** group, click **Catalog pages**.

9.  On the **Action Pane**, click **Catalog section**.

10. Click **New**, and then enter a name and description for a catalog section. Repeat this step to add all the sections that you require.

## 2\. Specify catalog page layout and page costs

Next, for each page in the catalog, specify the page type, the section in which the page appears, how many products appear on each page, and the cost of publishing each page. For each product that you want to analyze, specify the page on which the product appears, where the product appears on the page, and what percent of the page is allocated to the product.

To specify the layout and cost for a catalog page, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

2.  Double-click the name of the catalog to work with. On the **Action Pane**, in the **Call center** group, click **Catalog pages**.

3.  Click **New**, and then enter the page number, page type, page cost, number of products on the page, and section information for a page. Repeat this step to add lines for each page to analyze.

4.  Close the **Catalog pages** form.

5.  In the **Category hierarchy** area on the left side of the **Catalogs** form, select a node. On the Products FastTab, select a product in the list, and then click Product page layout.

6.  Click **New**, and then enter the following information:
    
      - Page number – The number of the page on which the product appears.
    
      - Percent of page – The percentage of page space that is allocated to the product.
    
      - Page position – The location of the product on the page.

7.  Repeat steps 5 and 6 to define the layout data for each product to analyze.

## 3\. Perform catalog area analysis

After a catalog has generated sales, you can perform a catalog area analysis that compares the cost of displaying a product in a page area to the sales and profit that are generated by that page area.

To perform a catalog area analysis, follow these steps.

1.  Click **Retail** \> **Reports** \> **Catalog area analysis**.

2.  In the **Catalog area analysis** form, on the **General** tab, click **Select**.

3.  On the **Range** tab, click **Add**. In the **Table** field, select the hierarchy level to analyze. You can analyze data for the whole catalog, for individual pages, or for individual items.

4.  In the **Criteria** field, enter the name of the entity to analyze. For example, if you want to analyze a catalog, enter the catalog name.

5.  Repeat steps 3 through 4 to add more lines to the query, if more lines are required.

6.  Click **OK**, and then click **OK** in the **Catalog area analysis** form.
    
    The catalog area analysis report is displayed. Each line shows data for a single product. The cost and profit associated with each product are shown in the following fields:
    
      - **Space cost** – The cost of the space that is allocated to the product. This value is calculated as the cost per page multiplied by the percentage of the page that the product uses.
    
      - **Contribution to profit** – The amount that the space contributes to profits. This value is calculated as the sales for the product minus the space cost.

7.  Optional: To set up the catalog area analysis to run as a batch job, in the **Catalog area analysis** form, on the **Batch** tab, enter the batch specifications.

## Related tasks

[Create call center catalogs](create-call-center-catalogs.md)

[Set up catalog source codes](set-up-catalog-source-codes.md)

[Analyze source code data](analyze-source-code-data.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Catalog manager</p></td>
</tr>
</tbody>
</table>

  


