# Employee-task-manager

Employee Task Manager – IMS566 Individual Project
The Employee Task Manager is a prototype web application developed for the IMS566 Advanced Web Design, Development and Content Management individual assignment. It simulates an internal admin portal used to monitor and manage employee tasks.

After logging in, an administrator can view pending employee tasks, completed tasks, and a visual summary of task distribution via a dashboard.

---

Features Included
Authentication & Login
Simple login page with hardcoded credentials: admin / 1234.
Error message displayed for invalid login.
Successful login redirects to the Dashboard.

Dashboard Page
Landing page after login.
Summary cards showing total tasks, completed tasks, and pending tasks.
Quick task list showing sample pending and completed tasks.
Doughnut chart (Chart.js) visualising the distribution of Completed vs Pending tasks.

Home (About) Page
Description of the portal and its purpose.
Explanation of key features.
Step-by-step instructions on how to use the system.
Short note about the assignment context and technologies used.

Pending Tasks Page
Table listing 5 pending employee tasks.
Columns: Task, Due date, Priority, Status.
Clean, responsive table layout.

Completed Tasks Page
Table listing 5 completed employee tasks.
Columns: Task, Completed On, Priority, Status.

Layout & Content Management
Consistent navigation bar with brand identity (NAIMUS Corporation).
Footer on all main pages with course info and developer name.
Responsive layout using Tailwind CSS (works on desktop and smaller screens).

---

Instructions to Test the Login
Open the live site (GitHub Pages link for this project).
On the Login page, enter:
Username: admin
Password: 1234
Click Login.
You will be redirected to the Dashboard, which shows:
Summary cards
Quick task list
A doughnut chart of Completed vs Pending tasks.

If you enter the wrong username or password, an error message will appear and access will be denied.

---

Frameworks / Libraries Used
HTML5 – structure and content.
Tailwind CSS (via CDN) – styling, layout, and responsive design.
Chart.js (via CDN) – doughnut chart on the Dashboard.
Vanilla JavaScript – login logic, Chart.js configuration, and Home-page clock.

---

File Structure (Main Pages)
login.html – Authentication page (entry point to the system).
dashboard.html – Dashboard (landing page after login with summary and chart).
home.html – About / instructions page for the portal.
pending.html – Data view page showing pending employee tasks.
completed.html – Data view page showing completed employee tasks.
