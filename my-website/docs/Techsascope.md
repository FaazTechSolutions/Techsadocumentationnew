## login
- Employee
    - Employee can login with his mobile number/email/ Id number(iqama number),
- Customer
    - Customer can login with his email/ CR number,
- Admin
    - Admin will login with his user Id

## Employee:
- employee screen needs create,edit and delete,
- if created automatically create an entry in users table,
- show the employees into separate menu based on status,
- file attachment,
- maintain the actions status change in employement history table
    #### actions
        - assign Project to employee(should be available only for employees who are not assigned to any project)
        - Activate (to update the status employee from suspended or terminated)
        - Suspend (to update the status employee from active to suspended)
        - Terminate(to update the status employee from suspended to terminate),
        - Rehire(to make the terminated employee in to active)
        - Import and Export Template for bulk Upload,
## Customer:
- customer screen needs create,edit and delete,
- if created automatically create an entry in users table,
- file attachment,
- need  sales person as dropdown for customer create,

## Project:
- Project screen needs create,edit and delete,

## Project Employees:
- Project Employees screen needs create,edit and delete,
- Need Bulk Creation
    #### actions
        - End Project
        - Transfer Employee
## Task:
- Task screen needs create,edit and delete,
- File Attachment,
- chat option inside the task details page,
- status history,
- assignment history,
- Task month wise report(For Admin and Customer only)
    #### actions
        - Print task details page,
        - download task details as pdf,
        - update task Status(For Employee only)
## Task Template:
- Task Template screen needs create,edit and delete,
    #### actions:
        - create task from template,
## Recurring Task:
- Recurring Task screen needs create,edit and delete,

## Attendance:
- based on employee login and task update action percentage,
- Role based Access for this screen,

## Enhancement:
- Show Online Users
- Notification
- Automate Attendance report(daily, weekly, monthly),
- Enquiry Form,

## Users:
- Users screen needs create,edit and delete,
    #### actions
        - Role Assignment
## Role:
- Role screen needs create,edit and delete,
    #### actions
        - Menu and User Assignment

## Lookup:
- Lookup screen needs create,edit and delete
    #### lookup Values
        - Lookup Values screen needs create,edit and delete,
## Translation:
- Language screen needs create,edit and delete
- Label screen needs create,edit and delete


## Common Features for All screens:
- multiple search,
- grid search auto filter,
- by default open all the grid search input box fixed open,
- Export All,Export Visible and Export Selected,
- sorting,
- pagination server side,
- change password option,


## Screen Access
- Employee
    - Profile, view only
        - my profile
        - projects (he is assigned in),
        - Customer (he is working for),
        - Job Details
    - Tasks,view only
        - only he can update the task(percentage and comments)
- Customer
    - Project, view only
    - Project Employees, view only
    - Task, view,create and update,Print Task Details 
    - Task template, view, create and update,
    - Attandence,only his employees
    - Recurring Task, create and edit
    - Task Report, only for his tasks
- Admin
    - All Screens

