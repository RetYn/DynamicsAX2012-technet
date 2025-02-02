---
title: Plan the organizational hierarchy
TOCTitle: Plan the organizational hierarchy
ms:assetid: cc19ddcb-68ca-43cf-ab64-1ab556e283d5
ms:mtpsurl: https://technet.microsoft.com/library/Hh242899(v=AX.60)
ms:contentKeyID: 36059446
author: Khairunj
ms.date: 05/16/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Plan the organizational hierarchy 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you set up organizations and organization hierarchies in Microsoft Dynamics AX, make sure that you plan how your business will be modeled. The organization model has a significant effect on the implementation of Microsoft Dynamics AX and on business processes. For more information about the organization model, see [About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md).

Organizational hierarchies represent the relationships between the organizations that make up a business. Therefore, the most important consideration when you model organizations is the structure of your business. We recommend that you define organization structures based on feedback from executives and senior managers from functional areas, such as finance and accounting, human resources, operations, purchasing, and sales and marketing.

When you are planning hierarchies, it is also important to consider the relationship between the organizational hierarchy and financial dimensions. You can set up multiple organizational hierarchies to represent different views of your business. By using financial dimensions, you can create reports based on these views. Work with your Microsoft Dynamics AX Partner to create hierarchies that address both organizational and statutory reporting needs.


> [!NOTE]
> <P>Although you can use financial dimensions to represent legal entities without creating the legal entities in Microsoft Dynamics AX, financial dimensions aren’t designed to address the operational or business needs of legal entities. The interunit accounting functionality in Microsoft Dynamics AX is designed to address only the accounting entries that are created by each transaction. For more information, see <A href="create-a-financial-dimension.md">Create a financial dimension</A>.</P>



This topic includes the following information about how to plan organization hierarchies:

  - Decide whether to model internal organizations as legal entities or operating units

  - Best practices for modeling organizations and hierarchies


> [!WARNING]
> <P>You shouldn’t decide how to model organizations based only on the information in this topic. This documentation is a guide. You can work with your Microsoft Dynamics AX Partner for additional guidance. Your Microsoft Dynamics AX Partner has gained experience in various industries and across the customer base.</P>



## Decide whether to model internal organizations as legal entities or operating units

You must have at least one legal entity to represent your business in Microsoft Dynamics AX. A legal entity can enter legal contracts and is required to prepare financial statements that report on its performance.

In Microsoft Dynamics AX, legal entities can be used for transactional business or for consolidation. This means that a legal entity in Microsoft Dynamics AX does not necessarily represent a real entity in your business. For example, a company that participates in transactions can own subsidiary legal entities. In this scenario, a legal entity is required for transactions, and a virtual legal entity is required to consolidate the results and balances of the subsidiary legal entities.

Internal organizations in your business, such as regional offices, can be represented as additional legal entities, or as operating units of the main legal entity. An operating unit is not required to be a legally defined organization. Operating units are used to control economic resources and operational processes in the business. For example, departments and cost centers are operating units.

Some functionality in Microsoft Dynamics AX works differently depending on whether the organization is a legal entity or an operating unit. Carefully consider your requirements for the features and functions in the following table.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Function</p></th>
<th><p>If the organization is modeled as a legal entity</p></th>
<th><p>If the organization is modeled as an operating unit</p></th>
<th><p>For more information, see</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Master data entry</p></td>
<td><p>Some master data, such as customers, payment terms, tax authorities, and site-specific stock ordering, must be set up for each legal entity. Some master data, such as users, products, and most human resources data, is shared among all legal entities.</p></td>
<td><p>Master data is shared among operating units.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Module parameters</p></td>
<td><p>Parameters for modules, such as <strong>Accounts receivable parameters</strong>, <strong>Accounts payable parameters</strong>, and <strong>Cash and bank management parameters</strong>, must be set per legal entity. Because the module setup for legal entities is separate, each subsidiary can comply with local statutory requirements and business practices. For example, a professional services legal entity and a manufacturing legal entity can have different module parameters even though they report to the same parent company.</p></td>
<td><p>Module parameters are shared among operating units.</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Data security</p></td>
<td><p>Most data is automatically secured by company ID. A company ID is a unique identifier for the data that is associated with a legal entity. A company can be associated with only one legal entity, and a legal entity can be associated with only one company. Users can access data only for the companies that they have access to. You do not need to customize Microsoft Dynamics AX to secure data by company ID.</p></td>
<td><p>Data can be secured per operating unit by creating customized data security policies. Data security policies are used to limit access to data. For example, assume that a user is allowed to create purchase orders only in a particular operating unit. Data security policies can be created to prevent the user from accessing purchase order data from any other operating unit.</p>
<p>The volume of transactions and the number of security policies can affect performance. When you design security policies, keep performance in mind.</p></td>
<td><p><a href="security-architecture-of-the-microsoft-dynamics-ax-application.md">Security architecture of the Microsoft Dynamics AX application</a></p></td>
</tr>
<tr class="even">
<td><p>Ledgers</p></td>
<td><p>Each legal entity requires a ledger that provides a chart of accounts, accounting currency, reporting currency, and fiscal calendar. A balance sheet can be created only for a legal entity.</p>
<p>Main accounts, dimensions, account structures, charts of accounts, and account rules can be used by more than one legal entity.</p></td>
<td><p>An operating unit can’t have its own ledger information. If your internal organizations do not require unique ledgers, you can model them as operating units. Ledger information will be set up for the parent legal entity in the hierarchy.</p>
<p>Income statements can be created for operating units within a legal entity or for the parent legal entity.</p></td>
<td><p><a href="set-up-a-ledger.md">Set up a ledger</a></p></td>
</tr>
<tr class="odd">
<td><p>Fiscal calendars</p></td>
<td><p>Each legal entity has its own fiscal calendar. If your internal organizations use different fiscal years and fiscal calendars, you must model the organizations as legal entities.</p></td>
<td><p>Operating units must share a fiscal calendar. If your internal organizations can use the same fiscal years and fiscal calendars, you can model the organizations as operating units.</p></td>
<td><p><a href="key-tasks-fiscal-calendars-fiscal-years-and-periods.md">Key tasks: Fiscal calendars, fiscal years, and periods</a></p></td>
</tr>
<tr class="even">
<td><p>Consolidation</p></td>
<td><p>You must consolidate the financial results for regional offices into a single, consolidated company in order to prepare financial statements.</p></td>
<td><p>Consolidation is not required, because data is already shared among operating units.</p></td>
<td><p><a href="consolidate-transactions.md">Consolidate transactions</a></p></td>
</tr>
<tr class="odd">
<td><p>Centralized payments</p></td>
<td><p>Centralized payments must be set up so that invoices for all child legal entities can be paid to or from a single parent legal entity.</p></td>
<td><p>Centralized payments are not required because all invoices are recorded in a single legal entity.</p></td>
<td><p><a href="set-up-centralized-vendor-payments.md">Set up centralized vendor payments</a></p>
<p><a href="set-up-centralized-customer-payments.md">Set up centralized customer payments</a></p></td>
</tr>
<tr class="even">
<td><p>Intercompany transactions</p></td>
<td><p>Intercompany sales orders, purchase orders, payments, or receipts can be applied to one another. You are not required to use journal vouchers. You can view intercompany transactions at the sub-ledger level (Accounts receivable, Accounts payable).</p>
<p>The following examples illustrate how intercompany transactions are handled.</p>
<p><strong>Example 1: Headquarters provides services to regional offices and must charge the costs of those services to the regional offices.</strong></p>
<p>If you model the regional office as a legal entity, you have the following options.</p>
<p><strong>Option 1:</strong> Headquarters creates a journal entry to cross-charge the regional office for the expense. The transactions cannot be aged.</p>
<p><strong>Option 2:</strong> Headquarters sends a purchase order for the services to the regional office. A sales order is automatically created in the legal entity for the regional office, with intercompany sub-ledger transactions.</p>
<p><strong>Example 2: Headquarters procures and pays for service that is delivered to a regional office.</strong></p>
<p>If you model the regional office as a legal entity, you have the following options.</p>
<p><strong>Option 1:</strong> The invoice and payment follow the regulatory requirements of headquarters. Headquarters can create a journal entry to cross-charge the regional office for the expense. The transactions cannot be aged.</p>
<p><strong>Option 2:</strong> The invoice and payment follow the regulatory requirements of headquarters. Headquarters can create an intercompany sub-ledger transaction.</p></td>
<td><p>Intercompany transactions among operating units are supported only through journal vouchers. An operating unit cannot issue or receive a purchase order, sales order, or invoice from another operating unit in the same legal entity. You cannot view intercompany transactions at the sub-ledger level (Accounts receivable, Accounts payable).</p>
<p>The following examples illustrate how intercompany transactions are handled.</p>
<p><strong>Example 1: Headquarters provides services to regional offices and must charge the costs of those services to the regional offices.</strong></p>
<p>If you model the regional office as an operating unit, headquarters enters an expense transaction and codes it to the regional office.</p>
<p><strong>Example 2: Headquarters procures and pays for service that is delivered to a regional office.</strong></p>
<p>If you model the regional office as an operating unit, the invoice and payment follow the regulatory requirements of headquarters. The invoice can be coded to the regional office. On the income statement, use a balancing financial dimension to report costs for the regional office.</p></td>
<td><p><a href="about-intercompany-parameters.md">About intercompany parameters</a></p></td>
</tr>
<tr class="odd">
<td><p>Local tax requirements</p></td>
<td><p>A legal entity is subject to the tax laws of the tax authority in the country/region where the legal entity is registered. For example, a legal entity that is registered in Denmark is subject to Danish tax laws and regulations.</p>
<p>In Microsoft Dynamics AX, a legal entity can belong to only one country/region. The country/region that you select for the primary address of the legal entity controls the country/region-specific features that are available to that legal entity. For example, if the primary address of the legal entity is in Denmark, features that are related to Danish tax laws and regulations become available.</p>
<p>Therefore, if your organizations are in different countries/regions and require different local tax options, you must set up the organizations as separate legal entities.</p></td>
<td><p>Operating units use the country context of the parent legal entity. Operating units in the same legal entity cannot have different country/region-specific requirements.</p>
<p>If your organizations are in the same country/region and use the same tax options, you can set them up as operating units.</p></td>
<td><p><a href="additional-country-region-specific-information.md">Additional country/region-specific information</a></p></td>
</tr>
<tr class="even">
<td><p>Statutory reporting for a country/region</p></td>
<td><p>For countries/regions that are supported by Microsoft Dynamics AX, most statutory reports can be created.</p>
<p>For information about which reports are available for each country/region, see the <a href="https://mbs.microsoft.com/customersource/global/ax/support/support-news/gfmlocalizationportalmc">Microsoft Dynamics Localization Portal</a> for Microsoft Dynamics AX. (A CustomerSource logon is required.)</p>
<div class="alert">

> [!NOTE]
> <P>In Microsoft Dynamics AX, a posting layer in the general ledger allows you to make adjusting entries to a parent company that uses a different accounting standard than the child company. For example, for a company that uses generally accepted accounting practices in the United Kingdom (UK GAAP), you can make adjusting entries in the posting layer. These entries can be consolidated into a parent company that uses generally accepted accounting principles (GAAP) in the United States. The adjusting entries do not affect UK GAAP reporting. For more information, see <A href="https://technet.microsoft.com/library/aa575927(v=ax.60)">Posting layer</A>.</P>


</div></td>
<td><p>Statutory reports must be created by using another application. You must ensure that data is captured in Microsoft Dynamics AX to support the requirements of each operating unit, where they differ from the requirements of headquarters.</p>
<p>Management Reporter, a financial reporting tool for Microsoft Dynamics ERP, can be used to create reports that address most statutory requirements. For more information about Management Reporter, see <a href="https://mbs.microsoft.com/customersource/default_managementreporter.htm">the Management Reporter page</a> on CustomerSource (logon required).</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Currency</p></td>
<td><p>If your organizations must use different functional currencies, you must model the organizations as legal entities.</p>
<p>Functional currencies are set up per legal entity. However, you can enter transactions in multiple currencies.</p></td>
<td><p>If your organizations can use a single functional currency, you can model the organizations as operating units.</p>
<p>Operating units must share a functional currency. However, you can enter transactions and create reports in multiple currencies.</p></td>
<td><p><a href="shared-currencies-and-exchange-rates-white-paper.md">Shared Currencies and Exchange Rates (White paper)</a></p></td>
</tr>
<tr class="even">
<td><p>Year-end closing</p></td>
<td><p>If laws and accounting practices differ among the countries/regions where your organizations are located, you may require different year-end procedures per organization. This means that you must model the organizations as legal entities. Each legal entity has its own year-end procedures.</p></td>
<td><p>If laws and accounting practices are the same among the countries/regions where your organizations are located, you may use a single set of year-end procedures. This means that you can model the organizations as operating units. All operating units must use the same year-end closing procedure.</p></td>
<td><p><a href="fiscal-year-closing-checklist.md">Fiscal year closing checklist</a></p></td>
</tr>
<tr class="odd">
<td><p>Number sequences</p></td>
<td><p>Number sequences for some references can be set up per legal entity. Some number sequences can be shared.</p></td>
<td><p>Number sequences for some references can be set up per operating unit. Some number sequences can be shared.</p></td>
<td><p><a href="number-sequence-overview.md">Number sequence overview</a></p></td>
</tr>
<tr class="even">
<td><p>Products</p></td>
<td><p>Product definitions are shared, and they must be released to individual legal entities before they can be included in transactions. Each legal entity has its own set of released products that can be included in transaction documents. If your internal organizations must use different sets of products, you must model the organizations as legal entities.</p>
<div class="alert">

> [!NOTE]
> <P>Even though product definitions are shared, in each legal entity where a product has been released, you can specify different sales, purchase, and stocking parameters for the item at each inventory site. For more information, see <A href="https://technet.microsoft.com/library/aa615563(v=ax.60)">Released product details (form)</A>.</P>


</div></td>
<td><p>All operating units share the same set of products. If your internal organizations can share the same set of products, you can model the organizations as operating units.</p></td>
<td><p><a href="key-tasks-define-products.md">Key tasks: Define products</a></p></td>
</tr>
<tr class="odd">
<td><p>Inquiry and reporting</p></td>
<td><p>You must manually change companies to enter transactions and perform inquiries in multiple legal entities.</p>
<p>Because of data security boundaries, consolidated inquiry and reporting can be resource intensive and time-consuming.</p></td>
<td><p>You do not need to change companies to access data from multiple operating units.</p>
<p>Consolidated inquiry and reporting and individual regional inquiry is easier and faster.</p></td>
<td><p><a href="open-another-company.md">Open another company</a></p></td>
</tr>
</tbody>
</table>


## Best practices for modeling organizations and hierarchies

Consider the following best practices when you implement an organization hierarchy:

  - Create a department to model the intersection between a legal entity and a business unit. You can then roll up data from a department to a legal entity for statutory reporting, and from a department to a business unit for internal reporting.
    
    Departments can serve as profit centers. If you use departments, you do not have to use legal entities and business units as dimensions in the account structure. You can use just departments as a dimension. However, you must use both cost centers and departments as dimensions in the account structure if cost centers are used only as cost accumulators, and departments are used for revenue recognition.

  - Model multiple hierarchies for operating units if you have complex requirements for reporting profit and loss.

  - In a single legal entity, do not model multiple hierarchies for the same hierarchy purpose.

  - Do not create a hierarchy for every purpose. Usually, you can use one hierarchy for multiple purposes. For example, one hierarchy of operating units can be assigned to all policy-related purposes.

  - Create balanced hierarchies. In a hierarchy, all nodes that are the same distance from the root node are defined as a level. In a balanced hierarchy, only one type of operating unit can occur at each level, and the distance from the root node to each level is consistent. If there are intermediate levels between a department and a legal entity or a business unit, placeholder organizations may be required to create a balanced hierarchy.

  - Do not model a separate hierarchy of operating units if the structure for legal entities is also your operating structure. A mixed hierarchy of legal entities and operating units may serve both purposes.

  - Before you model major restructuring scenarios, use the hierarchy's effective dates to perform an impact analysis and a validation test.

  - Use draft mode to change a hierarchy before you publish a new version in a production environment.

  - Limit the number of people who have permissions to add or remove organizations from a hierarchy in a production environment. A smaller number reduces the chance that costly mistakes can occur and corrections must be made.

## See also

[Example organizational hierarchies](example-organizational-hierarchies.md)

  


