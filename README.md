Parking App

WBS
•Add User
1.1	User Login Username and password authentication 
1.2	Create User Account 
1.3	Account Security Password reset and access control
2.	 User Setup 
2.1	Management Create and update user profiles 
2.2	Create and manage user accounts 
2.3	Roles and Permissions Assign user/operator access 
3.	 Garage Monitoring and Pay
3.1	View Parking Availability 
3.2	Track parking space status 
3.3	Parking payments 
3.4	Track parking and payment history
4.	Reporting
4.1	Generate parking usage reports
4.2	Generate payment reports
4.3	View garage and user activity

Story Points

Story points are used to tell how complex the work is with a higher number meaning higher difficulty.
User Login – 3 story points
User Registration – 3 story points
Account Security – 2 story points
User Management – 3 story points
Operator Management – 5 story points
Roles and Permissions – 5 story points
Parking Availability – 5 story points
Garage Monitoring – 8 story points
Payment Processing – 8 story points
Parking Transactions – 5 story points
Usage Reports – 5 story points
Payment Reports – 5 story points
Operator Reports – 3 story points

Scheduling Dependencies

The Parking Management App will use different types of scheduling dependencies to organize the project.
Finish-to-Start (FS): One task must be finished before the next task can start. For example, system design must finish before application development starts.
Start-to-Start (SS): Two tasks can start around the same time. For example, garage monitoring development and reporting development can start around the same time.
Finish-to-Finish (FF): Two tasks are connected because they should finish around the same time. For example, feature development and related testing can overlap, but testing should finish after the feature is completed.
Testing: Testing will happen throughout development and again after the major features are completed. This will help find problems before the project is finished.
Main Dependencies
Project Planning → Requirements (FS)
Requirements → System Design (FS)
System Design → Authentication Development (FS)
System Design → User/Operator Setup (FS)
System Design → Garage Monitoring (FS)
Garage Monitoring → Payment Processing (FS)
Garage Monitoring → Reporting (SS)
Application Development → Testing (FF)

Draft Schedule

The draft schedule shows the estimated amount of time for each major task and the dependency between tasks.
1.	Project Planning
Duration: 2 days
Dependency: None
2.	Requirements
Duration: 3 days
Dependency: Finish-to-Start (FS) after Project Planning
3.	System Design
Duration: 4 days
Dependency: Finish-to-Start (FS) after Requirements
4.	Authentication Development
Duration: 4 days
Dependency: Finish-to-Start (FS) after System Design
5.	User/Operator Setup
Duration: 5 days
Dependency: Finish-to-Start (FS) after System Design
6.	Garage Monitoring
Duration: 6 days
Dependency: Finish-to-Start (FS) after System Design
7.	Payment Processing
Duration: 5 days
Dependency: Finish-to-Start (FS) after Garage Monitoring
8.	Reporting Development
Duration: 4 days
Dependency: Start-to-Start (SS) with Garage Monitoring
9.	Integration Testing
Duration: 4 days
Dependency: Finish-to-Start (FS) after the major development tasks
10.	Final Testing
Duration: 3 days
Dependency: Finish-to-Finish (FF) with development/testing
11.	Project Completion
Duration: 1 day
Dependency: Finish-to-Start (FS) after Final Testing

Mile Stones




Update*

Jira Backlog and Sprint 1

The Parking App backlog was created in Jira using 45 tasks:

Login: 5 items
User and Operator UI: 15 items
Back end Processes: 15 items
Reporting: 10 items
Sprint 1

Sprint 1 includes 10 tasks focused on the basic parking app foundation. These tasks include login, account setup, user and operator dashboards, parking availability, and access control.


•	Requirements Completed
•	System Design Completed
•	Authentication Completed
•	User/Operator Setup Completed
•	Garage Monitoring and Payment Completed
•	Reporting Completed
•	Testing Completed

