**Project Description**

This project implements an Employee Onboarding Automation System using ServiceNow. The application automates the onboarding process for new employees by capturing employee details, requesting managerial approval, and automatically generating tasks for IT and administrative teams.

The system reduces manual effort by ensuring that onboarding activities such as laptop configuration, email setup, and workspace preparation are automatically assigned and tracked within the platform.

The automation logic is implemented using ServiceNow Flow Designer.

**Workflow Explanation**

The onboarding workflow follows a structured process to ensure that employee onboarding tasks are completed efficiently.

1. A new employee onboarding request is submitted through the application form.

2. When the request record is created, the workflow is automatically triggered.

3. The system updates the request status to In Progress.

4. An approval request is sent to the employee’s manager.

5. The manager reviews the request and either approves or rejects it.

6. If the manager approves the request:

            A task is created for the IT team to configure the laptop, email account, and system access.

            A task is created for the Administration team to prepare the workspace and employee ID card.

7. If the request is rejected, the workflow stops and no tasks are created.

8. This automated process ensures a smooth and efficient onboarding experience.

**Architecture Diagram**

The system workflow architecture is shown below:

Employee Onboarding Request Created
            ↓
Update Request Status (In Progress)
            ↓
Manager Approval
            ↓
If Approved
      ↓            ↓
Create IT Task   Create Admin Task

**Features**

- Custom ServiceNow application for employee onboarding.

- Custom table for storing onboarding requests.

- Form interface for submitting employee details.

- Automated workflow triggered on record creation.

- Manager approval process.

- Conditional task creation based on approval decision.

- Automated task assignment for IT and administrative teams.

- Status tracking for onboarding requests.

**Technologies Used**

- ServiceNow

- ServiceNow Flow Designer

- Custom tables and modules

- Workflow automation

- Approval management
