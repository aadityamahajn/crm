# Django CRM - CRUD Mastery Project

### Project Metadata
| Key | Value |
| :--- | :--- |
| **Project Name** | Django Customer Relationship Management (CRM) |
| **Framework** | Django (Python) |
| **Application Type** | Full-Stack CRUD Application |
| **Core Functionality** | Create, Read, Update, Delete (Records) |
| **Styling** | Bootstrap 5, Font Awesome Icons |
| **Frontend Logic** | JavaScript (Notification Timeouts) |
| **Environment** | Python Virtual Environment (venv) |

---

## Project Overview
This is a robust Customer Relationship Management application built with Django. The system allows users to manage client records through a secure, authenticated dashboard. It features a complete user authentication system and persistent data management for customer information.

## Key Features
- **User Authentication:** Secure registration, login, and logout functionality.
- **Dashboard Interface:** A centralized view of all customer records in a dynamic table.
- **Full CRUD Operations:**
  - **Create:** Add new customer records (Name, Email, Phone, Address, etc.).
  - **Read:** Individual record viewing for detailed information.
  - **Update:** Edit existing record details with pre-filled forms.
  - **Delete:** Remove records from the database with a single action.
- **Dynamic Notifications:** Flash messages for user actions (e.g., "Record created successfully") with automatic JavaScript timeouts.
- **Responsive Design:** Mobile-friendly UI utilizing Bootstrap.

## Technical Stack
- **Backend:** Django 4.x
- **Frontend:** HTML5, CSS3 (Custom + Bootstrap), JavaScript
- **Database:** SQLite (Default Django DB)
- **Dependencies:** - `django`
  - `font-awesome` (Icons)
  - `bootstrap` (UI Components)

## Installation & Setup

1. **Initialize Environment**
   ```bash
   `python -m venv venv`
    *Windows*
   `venv\Scripts\activate`
   *Mac/Linux*
   `source venv/bin/activate`

2. **Install Requirements**
   `pip install django`

3. **Database Migration**
   `python manage.py makemigrations`
   `python manage.py migrate`

4. **Static File Configuration**
Ensure `STATIC_URL` and `STATICFILES_DIRS` are configured in settings.py to serve CSS and JS files correctly.

5. **Run Development Server**
   `python manage.py runserver`
