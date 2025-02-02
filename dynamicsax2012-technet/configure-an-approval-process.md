---
title: Configure an approval process
TOCTitle: Configure an approval process
ms:assetid: c7771469-ab50-4e75-b239-802a7ea51f07
ms:mtpsurl: https://technet.microsoft.com/library/Dd362072(v=AX.60)
ms:contentKeyID: 35132859
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure an approval process 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure an approval process, in the workflow editor, right-click the approval element, and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties of the approval process.

## Name the approval process

Follow these steps to enter a name for the approval process.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the approval process.

## Specify when the system automatically acts on the document

You can configure the system to automatically act on the document if specific conditions are met. For example, the system can approve expense reports that have total amounts that are less than USD 100.

Follow these steps to specify when the system acts on the document.

1.  In the left pane, click **Automatic actions**.

2.  Select the **Enable automatic actions** check box.

3.  Click **Add condition**.

4.  Enter a condition.

5.  Enter additional conditions, if necessary.

6.  To verify that the conditions that you entered are configured correctly, complete the following steps:
    
    1.  Click **Test** to open the **Test workflow condition** form.
    
    2.  Select a record in the **Validate condition** area of the form.
    
    3.  Click **Test**. The system evaluates the record to determine whether it meets the conditions that you defined.
    
    4.  Click **OK** or **Cancel** to return to the **Properties** form.

7.  In the **Auto complete action** list, select the action that the system should take on the document.

## Specify when notifications are sent

You can send notifications to people when a document has been approved, rejected, delegated, or escalated, or when a change has been requested.

Follow these steps to specify when notifications are sent, and who the notifications are sent to.

1.  In the left pane, click **Notifications**.

2.  Select the check box next to the events to send notifications for:
    
      - **Delegate** – When a document has been assigned to another user for approval.
    
      - **Escalate** – When the assigned user has not acted on a document in the allotted time.
    
      - **Approve** – When a document has been approved.
    
      - **Reject** – When a document has been rejected.
    
      - **Request change** – When the assigned user has requested a change to a document that was submitted.

3.  Select the row for an event that you selected in step 2.

4.  Click the **Notification text** tab.

5.  In the text box, enter the text for the notification.

6.  To personalize the text, you can insert placeholders, which are replaced with the appropriate data when they are displayed to users. To insert a placeholder, follow these steps:
    
    1.  Click in the text box at the location where the placeholder should appear.
    
    2.  Click **Insert placeholder**.
    
    3.  In the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

7.  To add translations of the notification, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, insert placeholders.
    
    5.  Click **Close**.

8.  Click the **Recipient** tab.

9.  Specify who the notifications are sent to. Select one of the options in the following table, and then follow the additional steps for the option before you go to step 10.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Notification recipients</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Participant</strong></p></td>
    <td><p>Users who are assigned to a specific group or role</p></td>
    <td><ol>
    <li><p>After you select <strong>Participant</strong>, click the <strong>Role based</strong> tab.</p></li>
    <li><p>In the <strong>Type of participant</strong> list, select the type of group or role to send notifications to.</p></li>
    <li><p>In the <strong>Participant</strong> list, select the group or role to send notifications to.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Workflow user</strong></p></td>
    <td><p>Users who participate in the current workflow</p></td>
    <td><ol>
    <li><p>After you select <strong>Workflow user</strong>, click the <strong>Workflow user</strong> tab.</p></li>
    <li><p>In the <strong>Workflow user</strong> list, select a user who participates in the workflow.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>User</strong></p></td>
    <td><p>Specific Microsoft Dynamics AX users</p></td>
    <td><ol>
    <li><p>After you select <strong>User</strong>, click the <strong>User</strong> tab.</p></li>
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to send notifications to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


10. Repeat steps 3 through 9 for each event that you selected in step 2.

## Specify a final approver

You may want to designate a final approver for scenarios where the approver is the person who submitted the document for approval. Follow these steps to specify a final approver.

1.  In the left pane, click **Advanced settings**.

2.  Select the **Use final approver** check box.

3.  In the list, select the user to be the final approver.

## Set a time limit

Follow these steps if the approval process must be completed in a specific time.


> [!NOTE]
> <P>The options that you select in these steps override the options that you selected in the <STRONG>Assignment</STRONG> and <STRONG>Escalation</STRONG> areas of each approval step.</P>



1.  In the left pane, click **Advanced settings**.

2.  Select the **Set a time limit for the workflow element** check box.

3.  In the **Duration** field, specify when the approval process must be completed. Select one of the following options:
    
      - **Hours** – Enter the number of hours in which the approval process must be completed. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days in which the approval process must be completed. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks in which the approval process must be completed.
    
      - **Months** – Select the day and week by which the approval process must be completed. For example, you may want the approval process to be completed by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the approval process must be completed. For example, you may want the approval process to be completed by Friday of the third week of December.

4.  If the time limit is exceeded, the system acts on the document. In the **Action** list, select the action that the system should take.

## Specify which actions are available to the user

When a document is assigned to a user for approval, the user must act on the document. Follows these steps to specify which actions the user can take on the document that was submitted.

1.  In the left pane, click **Advanced settings**.

2.  Select the **Approve** check box if the user can approve the document.

3.  Select the **Reject** check box the user can reject the document.

4.  Select the **Request change** check box the user can request changes to the document.

5.  Select the **Delegate** check box if the user can assign the document to another user for approval.

## Specify whether users can act on the document from the work list in Enterprise Portal

By default, users can act on documents from the **Work list** Web part in Enterprise Portal for Microsoft Dynamics AX. However, there may be cases where you do not want users to be able to act on documents from this Web part. For example, you may want to require that users open the documents, and approve or reject the documents from the documents themselves.

Follow these steps to specify whether users can act on the document from the **Work list** Web part in Enterprise Portal.

1.  In the left pane, click **Advanced settings**.

2.  To allow users to act on the document from the **Work list** Web part in Enterprise Portal, select the **Enable actions from the work list in Enterprise Portal** check box.

3.  To prevent users from acting on the document from the **Work list** Web part in Enterprise Portal, clear the **Enable actions from the work list in Enterprise Portal** check box.

## Configure the approval steps

An approval process consists of approval steps. Complete the following procedure to add steps the approval process and configure the steps.

1.  In the workflow editor, double-click the approval process. The workflow editor displays the steps of the approval process.

2.  To add an approval step, drag the step from the **Workflow elements** area to the canvas.

3.  To configure an approval step, see [Configure an approval step](configure-an-approval-step.md).

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


