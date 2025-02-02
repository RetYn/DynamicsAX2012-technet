---
title: "What's new: Accounts receivable features"
TOCTitle: Accounts receivable features
ms:assetid: 809645f2-1669-4ac7-96af-88df3ae69162
ms:mtpsurl: https://technet.microsoft.com/library/Dn527164(v=AX.60)
ms:contentKeyID: 59623293
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Accounts receivable features 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Accounts receivable](accounts-receivable.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Giro footer information is printed on a separate page.</p></td>
<td><p>Six reports that can have variable footer information can now include the footer information on a separate page. These reports are the <strong>Customer account statement - external</strong>, <strong>Customer collection letter</strong>, <strong>Customer interest note</strong>, <strong>Free text invoice</strong>, <strong>Customer invoice</strong>, and <strong>Project invoice</strong> reports.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to credit card processing</p></td>
<td><p>Terminology for credit card processing has changed and now follows industry standards. In Microsoft Dynamics AX 2009, you could preauthorize a credit card to reserve the amount with the bank, and then authorize the credit card to collect the payment. Now, the term “authorize” is used for reserving the amount, and “capture” is used for collecting the payment.</p>
<p>The following enhancements are included for credit card processing:</p>
<ul>
<li><p>You can use any valid currency that your payment service supports.</p></li>
<li><p>Refunds can be processed for credit notes.</p></li>
<li><p>Authorizations, which were previously known as preauthorizations, occur automatically for the remaining amount of the order when a partial shipment is processed.</p></li>
<li><p>The card verification value (CVV) can be validated.</p></li>
<li><p>Address verification is now supported. Data support is provided for Level-2 (order header) data and Level-3 (order line) data.</p></li>
<li><p>You can process a sales order that contains a credit card, without storing the credit card number in Microsoft Dynamics AX.</p></li>
<li><p>You can send tax codes, customer tax groups, and item tax groups to an external application by using a web service.</p></li>
</ul>
<p>For more information, see <a href="credit-card-processing-white-paper.md">Credit card processing (White paper)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Multiple customer invoice formats for print management</p></td>
<td><p>You can now specify different formats for customer invoices in the <strong>Print management setup</strong> form. For example, you can use one format for most of your customers but a custom format for a specific customer. The custom report format must be created by a developer and added to the Microsoft Dynamics AX Application Object Tree (AOT) before it can be selected in the <strong>Print management setup</strong> form.</p>
<p>For more information, see <a href="set-up-print-management-for-a-customer-or-vendor.md">Set up print management for a customer or vendor</a>.</p></td>
</tr>
<tr class="even">
<td><p>Manage collections and collection agents.</p></td>
<td><p>Credit and collection managers can use a new central view to manage collections and collection agents. Collection agents can begin the collection process from customer lists that are generated by using predefined collection criteria. Collection agents can use the <strong>Collections</strong> form to organize work that is related to a specific customer to produce measurable results. Collection agents can also track activities, such as making telephone calls, sending email correspondence, and writing off transactions, and can manage groups of transactions and activities by assigning them to a case.</p>
<p>For more information, see <a href="collections-and-credit-in-accounts-receivable.md">Collections and credit in Accounts receivable</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Define enhanced interest calculations.</p></td>
<td><p>Expanded options for calculating interest give you the flexibility to handle interest charges that are unique to your organization. You can use the enhanced <strong>Interest</strong> form to define the specific calculations that are used when you collect interest and pay interest for various scenarios that your organization encounters. In earlier versions, interest could be calculated only by using a fixed percentage formula that used a simple per-day or per-month frequency. On the new <strong>Earnings</strong> and <strong>Payments</strong> tabs, you can base an interest calculation on either a percentage or an amount. On the new <strong>Ranges</strong> tab, you can derive interest percentages or amounts by defining an increasing series of these values in intervals of days, months, or amounts. For example, you can charge an interest amount of USD 5.00 every 15 days, 5 percent every three months, or 2 percent for every USD 1000.00 of the balance of an invoice.</p>
<p>For more information, see <a href="set-up-interest-calculations.md">Set up interest calculations</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create different interest terms for different date ranges.</p></td>
<td><p>You can create interest code ranges that are effective for a specified date range. You can also define changes in interest attributes, such as the days in a grace period, the amount, the ledger account, or the calculation method for a future date. This functionality guarantees that the correct set of interest attributes is used when interest is calculated on transactions. You can also view historical information for interest attributes. This information includes a timeline.</p>
<p>For more information, see <a href="set-up-interest-rates-for-an-interest-code.md">Set up interest rates for an interest code</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Correct free text invoices after they have been posted.</p></td>
<td><p>You can quickly correct posted invoices, review the history of free text invoices, and audit the correction history of free text invoices.</p>
<p>For more information, see <a href="correct-a-posted-free-text-invoice.md">Correct a posted free text invoice</a>.</p></td>
</tr>
<tr class="even">
<td><p>Select invoice lines for settlement.</p></td>
<td><p>When you use the <strong>Enter customer payments</strong> form or the <strong>Settle open transactions</strong> form, you can now apply a customer payment to selected invoice lines. You can use the new <strong>Mark invoice lines</strong> form to select individual lines for settlement and adjust the settlement amount for these lines. You can also view a history of the settled line amounts on a new <strong>Lines</strong> tab in the <strong>Customer settlement</strong> form. These features are activated by selecting a check box on the <strong>Settlement</strong> tab of the <strong>Accounts receivable parameters</strong> form.</p>
<p>For more information, see <a href="about-parameters-for-settlements-in-accounts-receivable.md">About parameters for settlements in Accounts receivable</a> and <a href="key-tasks-customer-payments-and-settlements.md">Key tasks: Customer payments and settlements</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Calculate interest based on the terms that are specified for individual transactions.</p></td>
<td><p>You can calculate the interest for transactions by using the interest code that is specified for the posting profile that is associated with the individual transactions. Interest ledger accounts, and the corresponding offset or summary accounts, are also obtained from the posting profile that is associated with the individual transactions when the interest note is posted.</p>
<p>For more information, see <a href="calculate-interest-and-create-interest-notes.md">Calculate interest and create interest notes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Quickly view customer invoice details, and create new interest notes.</p></td>
<td><p>When customers ask about their most recent invoice totals and interest charges, you can now find this information in one location instead of looking in multiple forms. Use the <strong>Open customer invoices</strong> list page to view important invoice details by customer. These details include posted and unposted interest, and total payments that have been made. You can click the <strong>New interest note</strong> button to calculate interest and create new interest notes by customer or by invoice. You can also click the <strong>Invoice</strong>, <strong>Transactions</strong>, <strong>Payments</strong>, <strong>Interest notes</strong>, and <strong>Collection letters</strong> buttons to view original transaction documents.</p>
<p>For more information, see <a href="calculate-interest-and-create-interest-notes.md">Calculate interest and create interest notes</a>.</p></td>
</tr>
<tr class="odd">
<td><p>View, print, or send individual invoices or ranges of invoices from the <strong>Free Text Invoices</strong> list page.</p></td>
<td><p>You can use the <strong>All free text invoices</strong> list page to view, print, or send individual invoices or groups of invoices, or copies of those invoices. You can use this feature to consolidate invoicing mailing batches, so that you can decrease mailing costs. You can select invoices by invoice date, invoice due date, or account number.</p>
<p>For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate recurring invoices for customers.</p></td>
<td><p>You can set up, create, and generate recurring free text invoices for customers.</p>
<p>For more information, see <a href="key-tasks-recurring-free-text-invoices.md">Key tasks: Recurring free text invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Select from multiple remit-to addresses for customer refunds.</p></td>
<td><p>You can select from multiple remit-to addresses for customers, so that you can send refunds to an address that differs from the primary customer address.</p></td>
</tr>
<tr class="even">
<td><p>New quantity and unit price fields on the free text invoice line</p></td>
<td><p>You can use the new <strong>Quantity</strong> and <strong>Unit price</strong> fields to determine the billing amount for a free text invoice line. These fields let you use a single invoice line to bill customers for more than one instance of a specific charge.</p>
<p>For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Specify how debit transactions are prioritized during Accounts receivable settlement.</p></td>
<td><p>You now can specify the order in which transactions are settled in Accounts receivable. You can use a new parameter to prioritize settlement by debit transaction type. You can create an ordered list of transaction types that determines the priority of settlement when no specific transactions are selected. If you are selecting transactions for settlement, you can click the <strong>Mark</strong> check box in the <strong>Enter customer payments</strong> and <strong>Open transactions</strong> forms to automatically select the prioritized transactions, and to easily see the transactions and make any changes before they are settled.</p>
<p>For more information, see <a href="settle-transactions-with-payments.md">Settle transactions with payments</a>.</p></td>
</tr>
<tr class="even">
<td><p>Use print management for Accounts receivable reports.</p></td>
<td><p>You can use the expanded print management features when you generate customer account statements, collection letter notes, and interest notes.</p>
<p>For more information, see <a href="set-up-print-management-for-a-transaction.md">Set up print management for a transaction</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Make adjustments to waive, reinstate, or reverse interest notes, interest on transactions, or fees.</p></td>
<td><p>You can waive interest notes, or interest on transactions or fees that are part of interest notes, when you make adjustments to an outstanding balance that is owed by a customer. Waived charges are forgiven, and the amounts are reversed to the same revenue accounts. Later, you can reinstate waived interest or fees so that the amounts are due again, if this change is required. You can also reverse waived interest notes or interest on transactions. Those amounts are then removed from account balances, so that interest can be recalculated for the transactions.</p>
<p>For more information, see <a href="waive-reinstate-or-reverse-interest-or-fees.md">Waive, reinstate, or reverse interest or fees</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhanced options for settlement priority</p></td>
<td><p>You can enable the settlement priority by debit transaction type, transaction amount, cash discount date, or due date. You can also set the sorting order, when a sorting order applies. The user can then determine which charges must be paid first when a payment is received. In addition, you can choose to use only the defined order to mark transactions for settlement and can exclude automatic settlement from being affected by the specified marking order.</p>
<p>For more information, see <a href="prioritize-automatic-settlements.md">Prioritize automatic settlements</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Improved free text invoice form for creating and posting free text invoices</p></td>
<td><p>The form for creating and posting free text invoices is easier to understand and use. All the actions have been moved to an Action Pane and are displayed on activity-based tabs. Therefore, you can access frequently used features and subsequent tasks by clicking a button.</p>
<p>For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a>.</p></td>
</tr>
<tr class="even">
<td><p>Add information from the original invoice to corrected invoices.</p></td>
<td><p>You can add the original invoice number and correction reason to a corrected free text invoice.</p>
<p>For more information, see <a href="correct-a-posted-free-text-invoice.md">Correct a posted free text invoice</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Record charges on free text invoice lines.</p></td>
<td><p>This feature lets you add freight and other charges to each line in a free text invoice, and distribute charges to dimensions and ledger lines.</p>
<p>For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a></p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Mandates and prenotifications for Single Euro Payment Area (SEPA) direct debits</p></td>
<td><p>Customer mandates for SEPA direct debit payments can be attached to customer accounts. You can specify whether a method of payment requires a mandate. If a mandate is required, the payment process verifies that a mandate is active for the customer. After you enter information about the direct debit mandate, you can send a prenotification to the customer before you start to draw payments by using a direct debit.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="sepa-direct-debit-overview.md">SEPA direct debit overview</a></p></li>
<li><p><a href="set-up-sepa-direct-debit-mandate.md">Set up SEPA direct debit mandate</a></p></li>
<li><p><a href="add-direct-debit-mandate-information-to-a-customer-account.md">Add direct debit mandate information to a customer account</a></p></li>
<li><p><a href="enter-an-invoice-or-transaction-for-a-customer-who-has-a-direct-debit-mandate.md">Enter an invoice or transaction for a customer who has a direct debit mandate</a></p></li>
<li><p><a href="create-payments-for-customers-who-have-direct-debit-mandates.md">Create payments for customers who have direct debit mandates</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>External documents can now be sent as email to a customer or vendor by using the email address that is specified by the address purposes. Any report can be sent as email to an internal employee by using the worker title.</p></td>
<td><p>In earlier releases, it was difficult for users to specify email addresses to send an external document as email. Users can now use the address purpose field to select existing email addresses from the customer or vendor, and send the external document to those addresses. A customer’s or vendor’s primary email address can also be selected. In addition, any report can be sent as email to internal employees by using the worker title field to select employees that have the same worker title. All employees that are assigned to that worker title receive the report.</p>
<p>For reports that use print management, users have the following options to send reports as email:</p>
<ul>
<li><p>Purpose</p></li>
<li><p>Primary contact</p></li>
<li><p>Worker title</p></li>
<li><p>Email address</p></li>
</ul>
<p>For Microsoft SQL Server Reporting Services reports, users have the following options to send reports as email:</p>
<ul>
<li><p>Worker title</p></li>
<li><p>Email address</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-print-management-for-a-customer-or-vendor.md">Set up print management for a customer or vendor</a></p></li>
<li><p><a href="print-or-email-a-report.md">Print or email a report</a></p></li>
<li><p><a href="print-or-email-a-report-during-off-peak-hours.md">Print or email a report during off-peak hours</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/hh597152(v=ax.60)">Print destination settings (form)</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

  


