# Resource-Mgt
## Introduction
### Purpose:
* Designed to manage existing resources, features, and tasks for each employee and their corresponding teams.
* Addressed the limitations of handling this data in Excel sheets by providing a more flexible and user-friendly solution.

## Main Features
### User Interface
* Login Page: Secure authentication gateway.
* Dashboard:
  * Displays charts and numerical data.
  * Data is sourced from subsequent app pages.

### Data Management
* Data-Grids:
  * Display data of all features (existing and upcoming) and their details.
  * Details include Sprint, Release, Pod, and Category information.
  * Supports CRUD operations based on user authorities and access levels.
  * Provides sorting and filtering options on rows and columns.
  * Allows data to be exported as Excel sheets for individual tables or multiple tables in one workbook.

### Additional Features
* Backlog Entries Table: Tracks pending tasks.
* Recycle Bin: Stores deleted entries temporarily.
* Approval Table: Manages approvals for various tasks and entries.
* Search Functionality: Search tables based on POD, Team Member, etc.
* Theme Toggle: Switch between dark and light modes for better user experience.

## Technical Details
### Frontend
* Built with React JS for a dynamic and responsive user interface.

### Backend
* Developed using SQL Alchemy and Django framework.
* Ensures robust data management and business logic implementation.

### Database
* MySQL is used for reliable and scalable data storage.

### Authentication System
* JWT Authentication: Ensures secure user authentication.
* RBAC (Role-Based Access Control):
  * Five roles defined with specific access levels:
    * Super-Admin:
      * Full CRUD operations.
      * Access to "Admin Page" for creating new users and assigning roles.
    * Other Roles: Specific access levels and permissions tailored to organizational needs.

## Conclusion
The application enhances resource management efficiency by replacing Excel sheets with a more versatile and easy-to-use platform.
Offers comprehensive features and a robust technical foundation to meet the organization's needs.
