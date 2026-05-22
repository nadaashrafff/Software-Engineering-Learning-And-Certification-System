# Software Engineering Learning and Certification System

## Project Overview

This repository contains the analysis, design, and documentation for **EduCertify**, a Learning and Certification System developed as part of a Software Engineering project.

EduCertify is an online educational platform designed to help learners enroll in courses, complete modules and assessments, track progress, and receive digital certificates after successful course completion. The system also supports instructors in creating courses, uploading course materials, grading assignments, and providing feedback.

The project follows a full software engineering lifecycle, including:

- System vision and stakeholder analysis
- Use case identification
- Software requirements specification
- Domain class modeling
- Behavioral modeling
- User interface design
- Application design
- Database integration

---

## Project Name

**EduCertify — Learning and Certification System**

---

## Repository Name

**Software-Engineering-Learning-And-Certification-System**

---

## Project Idea

The goal of EduCertify is to provide a flexible and accessible online learning environment where:

- Learners can search for courses, enroll, submit assessments, track progress, and earn certificates.
- Instructors can create and manage courses, upload materials, grade assignments, and provide feedback.
- Administrators can manage users, update the course catalog, and oversee platform operations.
- IT teams can maintain the system and resolve technical issues.
- Executives and investors can review financial, operational, and platform performance reports.

---

## Problem Statement

Many existing online learning platforms do not fully provide flexible, manageable, and certificate-focused learning experiences. Learners may struggle to find complete courses, track their progress, or obtain reliable certificates. Instructors may also face difficulties in managing courses, schedules, materials, and learner assessments.

EduCertify aims to solve these problems by offering a structured learning and certification system that supports both learners and instructors while also providing administrative and reporting features.

---

## System Capabilities

The system supports the following main capabilities:

- Course management
- Course creation and publishing
- Learner enrollment
- Course material upload
- Assignment submission
- Assignment grading
- Automated assessment grading
- Feedback management
- Learner progress tracking
- Digital certificate generation
- Technical support requests
- User account management
- Course catalog management
- Performance and financial reporting
- System maintenance tracking

---

## Stakeholders

The main stakeholders of the system are:

| Stakeholder | Role |
|---|---|
| Learner | Enrolls in courses, submits assessments, and earns certificates |
| Instructor | Creates courses, uploads materials, grades assignments, and provides feedback |
| Administrator | Manages users, courses, and platform operations |
| IT Team | Maintains the system and resolves technical issues |
| Customer Service | Handles user inquiries and support requests |
| Board of Directors | Reviews overall system performance |
| Senior Managers | Monitor operational performance |
| Investors | Review growth and financial reports |

---

## Main Actors

The system includes the following actors:

- Learner
- Instructor
- Administrator
- IT Team
- Customer Service
- Board of Directors
- Senior Managers
- Investors
- System

---

## Functional Requirements

The system supports several functional requirements, including:

### Learner Functionalities

- View available courses
- Search for courses
- Enroll in courses
- Submit assignments
- Submit final assessments
- Unlock next modules
- View grades
- Receive grade notifications
- Request certificates
- Download certificates
- Request technical support

### Instructor Functionalities

- Create new courses
- Upload course materials
- Organize course modules
- Grade assignments
- Provide feedback
- Generate learner progress reports
- Notify learners of grades
- Notify learners of scheduled sessions

### Administrator Functionalities

- Manage user accounts
- Create, update, and delete courses
- Update the course catalog
- Assign or reassign instructors
- Verify course completion
- Manage platform users and permissions

### IT Team Functionalities

- Perform system maintenance
- Resolve technical issues
- Log maintenance operations
- Roll back failed updates when needed

### Customer Service Functionalities

- Respond to user inquiries
- Categorize user requests
- Resolve non-technical issues
- Escalate technical issues to the IT team

### Executive and Investor Functionalities

- Review system performance
- Review financial performance
- View platform growth metrics
- Download performance reports

---

## Business Benefits

EduCertify provides several business benefits:

- Increased accessibility for learners
- Reduced need for physical learning resources
- Better scalability for future growth
- Global reach through online learning
- Competitive advantage through certification-focused learning
- Improved instructor and learner management
- Better reporting for decision-makers

---

## System Analysis Artifacts

This repository includes system analysis documents covering:

- System vision document
- Stakeholder identification
- User stories
- Event decomposition
- Use case descriptions
- Use case diagrams
- Domain class identification
- CRUD matrix
- Behavioral modeling

---

## Domain Classes

The system includes the following major domain classes:

- Learner
- Instructor
- Course
- Module
- Assessment
- Submission
- Certificate
- Notification
- Session
- Request
- Report
- Feedback
- Material
- User Account
- Operation
- Progress Report
- Financial Report

---

## Use Cases

The project includes simple, moderate, and complex use cases.

### Simple Use Cases

- Enroll in Course
- Issue Certificate
- Search Courses
- View Available Courses
- Submit Assessment
- Notify Learners of Scheduled Session
- Notify Learners of Grades

### Moderate Use Cases

- Manage User Accounts
- Grade Assignment
- Provide Feedback
- Generate Progress Report
- Resolve Technical Issues
- Unlock Next Module
- Submit Final Assignment
- Review System Performance
- Review Financial Performance

### Complex Use Cases

- Create Course
- Upload Course Materials
- Automatically Grade Assignments
- Request Technical Support
- Perform System Maintenance
- Update Course Catalog
- Respond to User Inquiries

---

## Behavioral Modeling

The behavioral modeling phase includes:

- Workflow behavior of the entire system
- Activity diagrams
- System sequence diagrams
- Use case interaction flows

### Main Activity Diagrams

- Request Technical Support / Respond to User Inquiries
- Issue Certificate
- Create Course

### Main System Sequence Diagrams

- Automatically Grade Assessments
- Create Course
- Enroll in Course
- Generate Progress Report
- Grade Assessment
- Issue Certificate
- Manage User Accounts
- Notify Learners of Grades
- Notify Learners of Scheduled Session
- Perform System Maintenance

---

## User Interface Design

The system includes user interface designs and storyboards for the main user flows.

### Main UI Screens

- Home Page
- Course Search Page
- Available Courses Page
- Course Details Page
- Enrollment Confirmation Page
- Course Creation Form
- Course Material Upload Page
- Support Request Form
- Support Ticket Details Page
- User Account Management Page
- Reports Page

### Main Menu Hierarchy

| Menu | Menu Choices | Intended Users |
|---|---|---|
| Learning | View/Search Courses, Enroll, View Grades, Issue Certificate | Learners |
| Course Management | Create Course, Upload Materials, Grade Assignment, Provide Feedback | Instructors |
| Customer Support | Request Technical Support, View Ticket Status | Learners/Instructors |
| Customer Service | Respond to Inquiries, Resolve Issues | Customer Service |
| Administration | Manage Users, Update Course Catalog | Administrators |
| Insights & Reports | Review Financial and System Performance | Executives |

---

## Application Design

The application design phase includes:

- Communication diagrams
- Sequence diagrams
- Final design class diagrams
- Software classes and methods
- Controller classes
- Entity classes
- Data access classes
- Screen/interface classes

### Main Design Class Diagrams

- Create Course
- Upload Course Materials
- Enroll in Course
- Issue Certificate
- Manage User Accounts
- Update Course Catalog
- Request Technical Support
- Automatically Grade Assignment
- Generate Progress Report
- Review System Performance
- Review Financial Performance

---

## Database Integration

The project includes database integration for selected use cases using data access classes.

The database integration demonstrates:

- Creating user accounts
- Creating learner accounts
- Creating instructor accounts
- Creating courses
- Viewing available courses
- Connecting software classes to database operations
- Running SQL queries through data access classes
- Reflecting inserted records inside the database

---

## Repository Contents

The repository includes the following main documentation files:

```text
System Analysis Phase - Use Cases.pdf
System Analysis Phase - Domain Classes.pdf
Software Requirements Specification.pdf
System Analysis Phase - Behavioral Modeling.pdf
System Design Phase.pdf
Database Integration with Software Deliverable.docx
Application Design.pdf
```

---

## File Descriptions

### `System Analysis Phase - Use Cases.pdf`

Contains the system vision document, stakeholders, user stories, event decomposition, and use case analysis.

### `System Analysis Phase - Domain Classes.pdf`

Contains the noun technique, domain class identification, domain class diagram, and CRUD matrix.

### `Software Requirements Specification.pdf`

Contains the software requirements specification, project drivers, constraints, functional requirements, business rules, and Volere requirement cards.

### `System Analysis Phase - Behavioral Modeling.pdf`

Contains workflow behavior, activity diagrams, and system sequence diagrams for the main use cases.

### `System Design Phase.pdf`

Contains user interface design, menu hierarchy, storyboards, first-cut class design diagrams, and design modeling.

### `Database Integration with Software Deliverable.docx`

Contains database integration work, data access classes, SQL integration, and database reflection screenshots.

### `Application Design.pdf`

Contains communication diagrams, sequence diagrams, final design class diagrams, and application design details.

---

## Main Features

- Learner enrollment system
- Course search and filtering
- Course creation and publishing
- Course material upload
- Assignment submission and grading
- Automated grading support
- Certificate generation
- Progress report generation
- Technical support ticketing
- User account management
- Course catalog management
- Financial and system performance reporting
- Database integration through data access classes

---

## Software Engineering Concepts Applied

This project applies several software engineering concepts, including:

- Requirements engineering
- Stakeholder analysis
- Use case modeling
- User story writing
- Acceptance criteria
- Domain modeling
- CRUD analysis
- Activity diagrams
- System sequence diagrams
- Communication diagrams
- Design class diagrams
- User interface design
- Storyboarding
- Database integration
- Data access layer design

---

## System Workflow Summary

1. Learners search for available courses.
2. Learners enroll in selected courses.
3. Instructors create courses and upload materials.
4. Learners complete modules and submit assessments.
5. Instructors grade assignments and provide feedback.
6. The system tracks progress and unlocks next modules.
7. Learners request certificates after completing course requirements.
8. The system validates completion and generates digital certificates.
9. Users can request technical support when needed.
10. Administrators manage users and course catalog data.
11. Executives and investors review platform performance reports.

---

## Business Rules

The main business rules include:

- Only certified instructors can create and publish courses.
- Learners must complete all course modules before receiving a certificate.
- The system must validate course completion before issuing certificates.
- User accounts should be managed according to roles and permissions.
- Major maintenance actions should be logged.
- Users should receive notifications for grades, certificates, and scheduled sessions.

---

## Project Scope

The scope of the system includes:

- Learning management
- Certification management
- Course management
- User account management
- Technical support management
- Reporting and analytics
- Database integration

The system is designed as a complete software engineering model for an online learning and certification platform.

---

## Expected Users

- Students and independent learners
- Freelance instructors
- Course creators
- Platform administrators
- Customer service teams
- IT support teams
- Senior managers
- Board members
- Investors

---

## Conclusion

EduCertify is a software engineering project that models a complete Learning and Certification System from analysis to design and database integration.

The project demonstrates how software engineering techniques can be used to transform a real-world educational platform idea into structured system requirements, models, diagrams, user interfaces, design classes, and database-connected components.

Through this project, the system shows how learners, instructors, administrators, support teams, and executives can interact within one integrated online learning platform.

---

## Team Members

- Nada Ashraf
- Aly Zaki
- Ahmed Waleed
- Omar Bayoumi

---

## Academic Context

This project was developed as part of a Software Engineering course and includes multiple deliverables covering the software development lifecycle from requirements analysis to system and application design.
