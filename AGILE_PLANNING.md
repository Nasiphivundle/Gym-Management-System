 Introduction

Agile methodology is used to plan the development of the Smart Student Task Manager system. The user stories are created based on the use case diagram and use case specifications from Assignment 5.
The goal is to break down the system into small tasks, organize them, and plan the first sprint.

User Stories (Based on Use Cases)

Story ID	User Story	Acceptance Criteria	Priority
US-001	As a student, I want to register an account so that I can use the system	Account must be created successfully	High
US-002	As a student, I want to login so that I can access my tasks	Only valid login allowed - High
US-003	As a student, I want to create a task so that I can manage my work	Task must be saved	- High
US-004	As a student, I want to edit a task so that I can update it	Changes must be saved	-Medium
US-005	As a student, I want to delete a task so that I can remove it	Task must be deleted	-Medium
US-006	As a student, I want to set a deadline so that I don’t forget work	Deadline must be stored	-High
US-007	As a student, I want to mark tasks complete so that I track progress	Task must show completed	-Medium
US-008	As a student, I want to view tasks so that I can see all my work	Tasks must display correctly	-High
US-009	As a system, I want to send reminders so that users don’t miss deadlines	Reminder must be sent before deadline


Product Backlog

Story ID	User Story	Priority (MoSCoW)	Effort (1–5)	Dependencies
US-002	Login	Must-have	                  3	                 None
US-001	Register account	Must-have	       3	             None
US-003	Create task	Must-have	                3	          Login
US-008	View tasks	Must-have	                 2	        Login
US-006	Set deadline	Must-have	             3	          Create task
US-009	Send reminders	Should-have	              4	          Deadline
US-004	Edit task	Should-have	                  2	         Create task
US-005	Delete task	Could-have	                   2	          Create task
US-007	Mark complete	Could-have                 2	          View tasks
Justification

The "Must-have" features are necessary for the system to work (login, create task, view tasks).
The "Should-have" features improve the system.
The "Could-have" features are less important for the first version.

Sprint Planning
Sprint Duration

2 Weeks

Sprint Goal

To build the main features of the system where a student can register, login, create tasks, and view tasks.

Selected User Stories for Sprint

US-001 (Register Account)
US-002 (Login)
US-003 (Create Task)
US-008 (View Tasks)
Sprint Backlog
Task ID	Task Description	Assigned To	      Estimated Hours	    Status
T-001	Create registration page	Developer	6	                To Do
T-002	Develop login system	Developer	    8	               To Do
T-003	Create task form	Developer	        6	                To Do
T-004	Save task in database	Developer	    8	               To Do
T-005	Display task list	Developer	          6	               To Do
T-006	Test login and task features	Developer	 4             To Do


Reflection

I learned how to turn use cases into user stories. At the beginning, I found it difficult because I had to make sure each user story was simple, clear, and easy to understand. I realized that a good user story must clearly explain what the user wants and why.

Another challenge I faced was prioritizing the product backlog. I had to decide which features were more important than others. This was not easy because many features seemed important, but I learned that core features like login and task creation must come first because they are needed for the system to work properly.

I also found it challenging to break down user stories into smaller tasks. I had to think like a developer and understand all the steps required to build each feature. This helped me see how much planning is needed before actual development starts.

Since I am working alone, I had to think from different perspectives, such as a student, admin, and developer. This helped me better understand the system and the needs of different users.

Overall, this assignment helped me understand Agile development, user stories, and sprint planning. It showed me the importance of planning and organizing work before building a system.