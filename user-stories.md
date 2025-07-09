
# 📘 User Stories – Employee Productivity Web App

This document describes the user stories for building a Vue.js web application that allows employees to track their daily logs, request leave, and view assigned tasks. These stories are structured for Agile development and GitHub integration.

---

## 🧑‍💼 As an Employee

### ✅ Dashboard Access
- **Story**: As an employee, I want to log into my dashboard so I can view my assigned tasks, leave form, and log my work for the day.
- **Acceptance Criteria**:
  - A personalized greeting (e.g., "Hello, Shivangi!")
  - View all primary widgets: *Assigned Tasks*, *Leave Form*, *Today’s Log*

---

## 📝 Latest Assigned Tasks

### ✅ View Assigned Tasks
- **Story**: As an employee, I want to see the latest tasks assigned to me so that I know what I’m supposed to work on.
- **Acceptance Criteria**:
  - Card with heading **"Latest Assigned Task"**
  - Shows list of task names (e.g., Admin Website, Maa Bala Sundari Ji Website, Gj Website)
  - Includes a “Check More” button
  - Styled with a light blue background

---

## 🛌 Apply for Leave

### ✅ Submit Leave Request
- **Story**: As an employee, I want to submit a leave request with dates and a reason so that the admin can review it.
- **Acceptance Criteria**:
  - Form fields:
    - Select leave type / days (dropdown)
    - From date (calendar picker)
    - Till date (calendar picker)
    - Leave description (text input)
  - “Update” button
  - Styled with a light green background

---

## 🧾 Add Today’s Work Log

### ✅ Daily Log Entry
- **Story**: As an employee, I want to log what I worked on today, including task details and hours, so that I can keep a record.
- **Acceptance Criteria**:
  - Form with:
    - Date picker
    - Select project (dropdown)
    - Select sub-project (dropdown)
    - Select task (dropdown)
    - Hours spent (input)
    - Task details (textarea)
  - “Update” button
  - Styled with light purple background

---

## 📋 Navigation Sidebar

### ✅ Navigation Menu
- **Story**: As an employee, I want to navigate to different sections like Attendance, Calendar, Logs, etc., using a sidebar.
- **Acceptance Criteria**:
  - Sidebar menu includes:
    - Dashboard (active)
    - Attendance
    - Colleagues
    - Assigned Tasks
    - Leave
    - HAIS Calendar
    - Add Day Logs
    - My Profile
  - Each item has a corresponding icon
  - Sidebar logo on top left with text `high(alt)`

---

## 🎨 UI & Layout

### ✅ Consistent Design
- **Story**: As a user, I want the interface to be clean and consistent so that it’s easy to use and understand.
- **Acceptance Criteria**:
  - Proper padding and margin between components
  - Font sizes match across components
  - Proper spacing between sidebar items
  - Sidebar items are vertically aligned
  - Logo is prominent and positioned at the top

---

## 📌 Technical Notes

- App built using **Vue.js 3**
- Future integration with **.NET Core API**
- Each section should be reusable as a Vue component
- Layout using Flexbox/Grid for responsiveness

---

✅ *End of User Stories Document*
