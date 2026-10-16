# EventHub - Event Booking & Management Platform

EventHub is a web-based event booking and management platform designed to connect event organizers with attendees seamlessly. The application simplifies discovering, booking, and managing events through an intuitive, user-friendly digital interface.

---

## Project Overview

EventHub provides an integrated environment where users can browse and book event tickets online, while event organizers and system administrators receive robust management and analytics tools to oversee event operations efficiently.

---

## Key Features

### Role-Based Access & Dashboards
* **Event Enthusiasts (Attendees):** Browse events with advanced filters (category, date, location), book tickets online, receive notifications, and manage booked tickets with QR Code access.
* **Event Organizers:** Create, publish, edit, and cancel events, track total bookings and performance metrics, and manage attendee lists.
* **System Admin:** Review and approve or reject pending event listings, manage platform users and event data, and oversee support tickets.
* **Support Team:** Access user-reported issues, track problem status, and handle complaints efficiently through an interactive ticketing workflow.

### Core Functionalities
* **Authentication & Recovery:** Secure sign-up and login system tailored by user role and a password reset flow.
* **Search & Discovery:** Filter events dynamically by category, location, and date.
* **Ticket Management & Verification:** View booked tickets and generate unique QR codes for event check-in.
* **Support System:** Integrated support issue tracking and real-time live chat assistance.
* **Marketing Integration:** Dedicated Instagram integration to feature promotional content and increase engagement.

---

## Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Methodology:** Agile / Scrum Framework (2 Sprints)

---

## Project Structure & File Descriptions

### Core Folders
* `includes/header.php`: HTML document head and stylesheet includes.
* `includes/navbar.php`: Dynamic navigation bar based on user role and login status.
* `includes/footer.php`: Page footer with quick links and scripts.
* `DataBase/eventhub (3).sql`: Database schema, initial tables, triggers, and seed data.
* `config/EventBooking.php`: Core logic for booking tickets, transaction handling, and QR code generation.
* `config/auth.php`: Authentication, session management, and role-based access control functions.
* `config/db.php`: Database connection initialization script.
* `assets/style.css`: Main styling sheet for platform UI and responsive layouts.
* `assets/default.jpg`: Default placeholder image for events without custom images.

---

### Root System Files
* `signup.php`: User account registration page.
* `login.php`: User authentication and role-based redirection page.
* `logout.php`: Destroys active user sessions and logs out.
* `forgot_password.php`: Password recovery and reset interface.
* `index.php`: Platform landing page with featured events and vision summary.
* `about.php`: Public information page about the platform.
* `contact.php`: Contact info and social media channels page.
* `events.php`: Public event catalog with multi-criteria search and filter options.
* `event_details.php`: Detailed event view with ticket booking form.
* `book_event.php`: Backend script processing booking transactions.
* `my_bookings.php`: Attendee booking history display page.
* `my_tickets.php`: Display page for active tickets and check-in QR codes.
* `my_notifications.php`: User notification log and updates page.
* `organizer_dashboard.php`: Organizer metrics overview page.
* `organizer_events.php`: Organizer event management and creation interface.
* `organizer_edit_event.php`: Event details editing interface for organizers.
* `organizer_delete_event.php`: Backend script for canceling or removing events.
* `admin_dashboard.php`: System administrator analytics dashboard.
* `admin_events.php`: Admin interface for reviewing and approving event listings.
* `admin_users.php`: Admin user management console.
* `admin_support.php`: Admin support ticket overview page.
* `support_dashboard.php`: Support agent issue metrics dashboard.
* `support_all_issues.php`: Support staff workspace for managing open tickets.
* `support_my_issues.php`: User workspace for submitting and tracking support requests.
