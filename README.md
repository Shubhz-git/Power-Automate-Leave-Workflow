# Automated Leave Management System 🚀

An end-to-end automation solution built with **Microsoft Power Automate**, **SharePoint Online**, and **Microsoft Teams**. This project streamlines the employee leave request process from submission to final approval and calendar logging.



## 🛠️ Technology Stack
* **Data Storage:** SharePoint Online (Lists)
* **Logic Engine:** Power Automate (Cloud Flows)
* **Communication:** Microsoft Teams (Adaptive Cards) & Outlook (Office 365)

## 📖 How it Works
1.  **Submission:** Employee fills out a simple form in a SharePoint List.
2.  **Validation:** The flow triggers, calculates the number of days, and checks against the employee's remaining balance.
3.  **Approval:** An **Adaptive Card** is sent to the Manager via Teams. The manager can Approve or Reject directly within the chat.
4.  **Notification:** The employee receives an automated email with the manager's comments.
5.  **Logistics:** If approved, the leave is automatically added to a shared Outlook "Team Calendar."

## 📁 Repository Structure
* `/solution`: Contains the `.zip` export of the Power Automate flow.
* `/templates`: Contains the SharePoint List schema.
* `/assets`: Architecture diagrams and screenshots.

## 🚀 Getting Started
1.  Create a SharePoint list based on the schema in `/templates/sharepoint-schema.md`.
2.  Import the `.zip` file from `/solution` into your Power Automate environment.
3.  Update the connection references to point to your specific SharePoint Site and Teams environment.

---
Created by Shubham Patil - Feel free to connect on LinkedIn!
