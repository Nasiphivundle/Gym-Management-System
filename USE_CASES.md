
```mermaid
usecaseDiagram
actor Student
actor Lecturer
actor Admin
actor System
actor IT_Support
actor Developer

Student --> (Register Account)
Student --> (Login)
Student --> (Create Task)
Student --> (Edit Task)
Student --> (Delete Task)
Student --> (Set Deadline)
Student --> (Mark Task Complete)
Student --> (View Tasks)

Lecturer --> (Create Assignment)
Lecturer --> (View Student Progress)

Admin --> (Manage Users)

System --> (Send Reminders)

IT_Support --> (Maintain System)

Developer --> (Update System)


---

## Explanation (VERY IMPORTANT FOR MARKS)

```markdown
## Use Case Explanation

### Key Actors
- Student: Main user who manages tasks
- Lecturer: Provides assignments
- Admin: Manages system users
- System: Sends automated reminders
- IT Support: Maintains system
- Developer: Updates system features

### Relationships
- The "Set Deadline" use case includes "Send Reminder"
- Students interact with most use cases
- Admin has control over user management

### Stakeholder Alignment
- Students’ concern for missing deadlines is solved by reminders
- Lecturers’ concern for tracking progress is addressed by viewing tasks
- IT staff concerns about maintenance are addressed through system monitoring