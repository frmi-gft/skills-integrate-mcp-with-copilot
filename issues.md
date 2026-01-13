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