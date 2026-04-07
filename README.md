
# Employee Task Tracker Application

The Employee Task Tracker Application is built using Microsoft Power Apps to track employee daily tasks and working hours.  
It also includes a manager view and an automated email alert system using Power Automate.

---

## Application Overview

This application helps employees log their daily work activities and update task status throughout the day.
Managers can monitor employee productivity and receive automated alerts when employees do not meet minimum working hours.

The solution is designed for internal organizational use to improve transparency and productivity.

---

## User Roles

### Employee
- Add daily tasks
- Update task status
- View task summary
- View task history

### Manager
- View all employees
- Monitor total working hours
- View employee task details
- Receive automated email alerts

---

## Key Features

- Automatic employee identification on app launch
- Add and manage daily tasks
- Task status tracking:
  - In Progress
  - Break
  - Completed
- Automatic calculation of total working hours
- Task history view for employees
- Manager-only dashboard
- Automated email alerts using Power Automate

---

## Application Views

### Employee Dashboard
- Displays employee name automatically
- Allows adding new tasks
- Shows current task status


---

### Task Status Management
- Employees can update task status during the day
- Status changes are saved automatically


---

### Task History
- Displays completed tasks for the current and previous days

---

### Manager View
- Restricted access for managers
- Displays employee ID, name, department, and total working hours


---

### Employee Task Details
- Managers can view detailed task history for a selected employee


---

### Automated Email Alert
- An email alert is sent to the manager if total working hours are less than 7 hours and 45 minutes

---

## Power Automate Flow Details

- Flow Type: Scheduled Cloud Flow
- Schedule: Daily at 6:30 PM
- Condition: Total working hours < 7 hours 45 minutes
- Action: Send email alert to manager

Note:
The flow is scheduled to run daily, but it is triggered manually during demo for demonstration purposes.

---

## Demo Video

A short demo video is included to demonstrate:
- Task creation and status updates
- Task history view
- Manager dashboard
- Automated email alert

---

## Files Included in Repository

- EmployeeTaskTracker.msapp – Power Apps application file
- User manual/ – Application and flow screenshots
- Demo video link
- Power Automate flow package (ZIP)
- Application workflow

---

## Technologies Used

- Microsoft Power Apps
- Microsoft Power Automate
- SharePoint (as backend data source)

---

## Conclusion

The Employee Task Tracker Application provides a complete solution for tracking employee work hours, managing daily tasks, and ensuring accountability through automated monitoring and alerts.

---

## Author

Soundaryaa  
Junior Programmer  
Power Apps & Power Automate
