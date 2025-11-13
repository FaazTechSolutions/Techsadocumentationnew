## New Techsa
### Admin Login
- Home(month wise task chart report with year and month filter)
- Employee(here you can Create,Edit and Delete your Employees)
    - Action Import employee and export template
    - Action update Status(if gatestaus = Active || suspend || null)
    - Action End Project(just updating the valid to date as current date)
    - attachment option
    - Employee Details: all the below are view only
        - task from current project
        - all task
        - all projects
- Attendance,
    - filter with year, month and customer id
    - report based on login  and status update
    - custom excel export
- Customer(here you can Create,Edit and Delete your Customer)
    - customer details:
        - project, crud
- Project(here you can Create,Edit and Delete your Project)
    - project Details: crud
        - Action end project
        - Action transfer employee(project id,job, reason)

- Project Employee(here you can Create,Edit and Delete your Project Employee,also you can end the employee from the project)
    - Action end project
    - Action transfer employee(project id,job, reason)
- Task(here you can Create,Edit and Delete your Task,also you can assign single employee for the task)
    - print action in grid level
    - task details:
        - task details,(attachement option),
        - status history,view only
        - task assignment history,view only
- Task Template(here you can Create,Edit and Delete your task template)
    - task create action form grid
- Timesheet Access:
    assign and unassign timesheet screen role access,
- Recurring Task:crud based on schedule it will create the task

- Admin
    - LookUp(here you can Create,Edit and Delete your LookUp,lookup is used to categorize some group of values example: state list)
        - Lookup Details(here you can Create,Edit and Delete your LookUpvalues,lookupvalue is used to categorize some group of values under a lookup parent example: cities under the state)
    - Role(here you can Create,Edit and Delete your Role,also you can assign menu and user to the specific role)
    - Language(here you can Create,Edit and Delete your Language,is used to list out the languages that you want in your app)
    - Label(here you can Create,Edit and Delete your Label,for the created language you can create the transalted words here)

### Customer Portal
- Home Welcome screen
- Projects(here customer can view the list of customers projects)
    - Projects Employees(here customer can view the assigned employees for the projects)
- Task(here you can Create,Edit  your Task with attachment option)
- Task Template(here you can Create,Edit and Delete your task template ,you can create Task from task template)
- Timesheet attandence(only visible for who has permission),with filter year month
- task report month wise, with filter year and month,
- recurring task if the user as permission

### Employee Portal
- Tasks(here employee can view the list of task assigned to him and he can start the task and he can update the progress of the task)
- My Profile:the below list are view only
    - profile details
    - project details,
    - customer details,
    - job details,