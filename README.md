Employee Task Manager – NAIMUS Corporation
Employee Task Manager is a comprehensive internal admin portal prototype developed for the IMS566 (Advanced Web Design, Development, and Content Management) individual project. The application is designed to simulate a real-world environment where administrators can monitor employee performance, manage task distributions, and maintain corporate profiles.

Features
1. Secure Authentication & Login
Entry Point: Custom-styled login page with a sleek purple gradient background.

Credentials: Uses hardcoded security credentials (Username: admin / Password: 1234).

Validation: Dynamic error messages for incorrect entries and automatic redirection upon successful authentication.

2. Dynamic Dashboard
Analytics Overview: Four summary cards displaying real-time statistics: Total Employees (25), Total Tasks (62), Completed (30), and Pending (32).

Visual Data: * Doughnut Chart: Visualizes the ratio of Completed vs. Pending tasks.

Bar Chart: Displays employee distribution across various departments (HR, Finance, IT, Operations, Projects).

3. Employee Directory & Profiles
Centralized Directory: A searchable table of all staff members including their position, department, and current status (Active, On Leave, Offline).

Profile Details: A dynamic detail page (profile-detail.html) that extracts employee information from URL parameters to display individual cards.

4. Task Management Segregation
Pending Tasks: Dedicated view for ongoing assignments, categorized by priority (High, Medium, Low) and due dates.

Completed Tasks: Historical log of all finalized tasks, including completion dates for audit purposes.

Search Functionality: Both task pages include a real-time JavaScript-powered search filter to find specific records instantly.

5. Corporate Home (About)
Live Monitoring: Features a functional system clock showing local time (en-MY format).

Administrative Profiles: Highlights key personnel, such as the Systems Administrator (Naim Zulhaziq) and IT Support Officer (Nabil Firdaus).

Frameworks & Libraries Used
HTML5: Semantic structure and content.

Tailwind CSS (via CDN): Advanced utility-first styling for a responsive, modern UI.

Chart.js (via CDN): Interactive data visualization for the dashboard.

Vanilla JavaScript: Logic for authentication, live clock, real-time table filtering, and dynamic profile rendering.
