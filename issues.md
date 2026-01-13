# Issues for ActivityHub Features

## Issue 1: Implement Login Page
**Title:** Implement Login Page with Role Selection  
**Description:** Create a login page (`login.html`) with fields for username, password, and role selection (user or admin). Use JavaScript to redirect to `user.html` for users or `admin.html` for admins. Include basic CSS styling with a grid layout and centered form. No real authentication needed; simulate with role-based redirection.

**Labels:** frontend, authentication  
**Assignee:** None  

## Issue 2: Implement Admin Dashboard
**Title:** Implement Admin Dashboard  
**Description:** Create `admin.html` with a grid layout: header with "Admin Dashboard" and logout link, left menu with "Manage Activities", "Manage Students", "Reports", body with a table listing activities (S.no, Activity, Date, Location, Edit, Delete), right menu with notifications like "Pending registrations" and "Activity updates". Include sample data in the table. Style with CSS for responsiveness.

**Labels:** frontend, admin  
**Assignee:** None  

## Issue 3: Implement User Dashboard
**Title:** Implement User Dashboard  
**Description:** Create `user.html` with a grid layout: header with "User Dashboard" and logout link, left menu with "Dashboard", "My Activities", "Register Event", "Upcoming Events", body with a table of activities including a "Register" button, right menu with notifications like "Soccer practice rescheduled" and "New Music Night". Include sample data. Style with CSS.

**Labels:** frontend, user  
**Assignee:** None  

## Issue 4: Add Basic Styling and Responsiveness
**Title:** Add Basic Styling and Responsiveness  
**Description:** Ensure all pages use consistent CSS Grid layouts, colors (bisque, beige, aquamarine, etc.), and are responsive. Add hover effects to buttons and links. Test on different screen sizes.

**Labels:** frontend, styling  
**Assignee:** None  

## Issue 5: Add JavaScript Functionality
**Title:** Add JavaScript Functionality  
**Description:** Enhance the login page with the redirection logic. Add any interactive elements if needed (e.g., button clicks for register/edit, though static). Ensure logout links redirect to login.

**Labels:** frontend, javascript  
**Assignee:** None  

## Issue 6: Integrate with Existing MCP/Copilot Project
**Title:** Integrate Features into skills-integrate-mcp-with-copilot  
**Description:** Adapt the ActivityHub features to fit the existing Flask app (`src/app.py`) and static files (`static/index.html`, etc.). Convert HTML pages to templates or routes in Flask, add backend logic for activity management, user roles, and database integration if needed.

**Labels:** backend, integration  
**Assignee:** None  

# New Issues for Enhancing the Current Project

## Issue 7: Implement User Authentication and Roles
**Title:** Add User Authentication and Role-Based Access  
**Description:** Implement login system in FastAPI with JWT or session-based auth. Add roles (admin, student). Protect routes based on roles. Update frontend to include login page and role selection.

**Labels:** backend, authentication, security  
**Assignee:** None  

## Issue 8: Create Admin Dashboard
**Title:** Build Admin Dashboard for Managing Activities  
**Description:** Create a new HTML page or template for admins. Include table to list/edit/delete activities, manage students, view reports. Add backend endpoints for CRUD operations on activities. Integrate with existing API.

**Labels:** frontend, backend, admin  
**Assignee:** None  

## Issue 9: Enhance User Dashboard
**Title:** Develop User Dashboard with Menus and Notifications  
**Description:** Redesign the current index.html into a dashboard with left menu (Dashboard, My Activities, Register Event, Upcoming Events), body with activity table and register buttons, right menu for notifications. Add backend for user-specific data.

**Labels:** frontend, backend, user  
**Assignee:** None  

## Issue 10: Add Notifications System
**Title:** Implement Notifications for Users and Admins  
**Description:** Add backend logic for notifications (e.g., activity updates, registrations). Store and retrieve notifications. Display in dashboards.

**Labels:** backend, frontend, notifications  
**Assignee:** None  

## Issue 11: Improve Styling and Layout
**Title:** Update CSS for Grid Layouts and Responsiveness  
**Description:** Adopt grid-based layouts similar to ActivityHub. Ensure consistency across pages. Add colors and hover effects. Make fully responsive.

**Labels:** frontend, styling  
**Assignee:** None  

## Issue 12: Add JavaScript Enhancements
**Title:** Enhance JS for Role-Based UI and Interactions  
**Description:** Update app.js to handle role-based redirections, dynamic menus, and new interactions (e.g., edit/delete buttons). Add logout functionality.

**Labels:** frontend, javascript  
**Assignee:** None