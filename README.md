ServiceNow Employee Onboarding Automation
Project Description

This project implements an Employee Onboarding Automation System using ServiceNow.
The application automates the process of onboarding new employees by capturing employee details, requesting manager approval, and automatically creating tasks for IT and administrative teams.

The system reduces manual effort and ensures that onboarding activities such as laptop setup, email configuration, and workspace preparation are completed efficiently.

The application includes custom tables, forms, modules, and automated workflows built using ServiceNow Flow Designer.

Key Features

Custom ServiceNow application for employee onboarding

Custom table to store employee onboarding requests

Form interface for submitting onboarding details

Automated workflow triggered when a request is created

Manager approval process

Automatic task creation for IT and Admin teams

Status tracking of onboarding requests

Workflow Explanation

The onboarding workflow follows these steps:

HR submits a new employee onboarding request through the application form.

The workflow is triggered when a new record is created.

The system automatically updates the request status to In Progress.

An approval request is sent to the employee's manager.

If the manager approves the request:

A task is created for the IT team to set up the laptop and email.

A task is created for the Admin team to prepare the workspace and ID card.

If the request is rejected, the onboarding process stops.

This workflow ensures that all required onboarding activities are automatically assigned to the responsible teams.

Workflow Architecture

The system workflow is structured as follows:

Employee Onboarding Request Created
            ↓
Update Request Status (In Progress)
            ↓
Manager Approval
            ↓
If Approved
      ↓            ↓
Create IT Task   Create Admin Task
System Components
Custom Table

New Employee Request

Fields include:

Employee Name

Employee ID

Department

Manager

Joining Date

Laptop Required

Email Required

Status

Modules Created

Employee Onboarding System

New Employee Requests

Create Request

Flow Automation

Automation is implemented using Flow Designer and includes:

Trigger: Record Created

Update Request Status

Ask for Manager Approval

Conditional logic for approval

Automated task creation
