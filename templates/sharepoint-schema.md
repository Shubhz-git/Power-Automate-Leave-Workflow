# SharePoint List Configuration

To use this workflow, create a SharePoint list named **LeaveRequests** with the following column structure:

| Display Name | Internal Name | Type | Options / Requirements |
| :--- | :--- | :--- | :--- |
| **Title** | `Title` | Single line of text | Used for "Leave Reason" |
| **Leave Type** | `LeaveType` | Choice | Annual, Sick, Personal, Maternity |
| **Start Date** | `StartDate` | Date and Time | Date Only |
| **End Date** | `EndDate` | Date and Time | Date Only |
| **Status** | `Status` | Choice | Pending, Approved, Rejected |
| **Manager Comments** | `ManagerComments` | Multiple lines of text | Optional |
| **Requester Email** | `RequesterEmail` | Single line of text | Set to [Me] or Person Column |

> **Note:** Ensure that the "Status" column defaults to "Pending" upon new item creation.
