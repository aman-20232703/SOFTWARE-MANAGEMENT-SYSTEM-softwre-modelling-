# 📘 Software Requirements Specification – Event Management System

This repository contains the full *Software Requirements Specification (SRS)* document for an *Event Management Software System*. The software is designed to help organizers create, manage, and host events efficiently while providing essential features such as attendee registration, payment integration, team management, notifications, and analytics.

---

## 📄 Document Title

- *File:* SRS.pdf
- *Project:* Event Management Software

---

## 🎯 Purpose

This SRS outlines the complete functional and non-functional requirements for building a web-based Event Management System. It serves as a contract between stakeholders and the development team, ensuring all needs are clearly documented and agreed upon before development begins.

---

## 🧩 Key Features Covered

- Event creation and venue booking
- Attendee registration and ticketing
- Online payment integration (PayPal, Stripe)
- Team creation, task assignment, and tracking
- Email and SMS-based notifications
- Role-based access control (Admin, Organizer, Attendee, Team Leader)
- Analytics and reports dashboard
- Social media integration for event promotion
- Comprehensive user management and filtering

---

## 🧠 Functional Requirements

- *User Account Management:* Registration, login, password reset, roles
- *Event Lifecycle:* Create, update, cancel, reschedule
- *Ticketing & Payments:* Multi-type tickets, discount codes, secure payment handling
- *Notifications:* Alerts for event changes, reminders, and confirmations
- *Analytics:* Downloadable reports for registrations, revenue, demographics
- *Use Cases:* Defined for Admins, Attendees, Organizers, Vendors, Speakers, and Staff

---

## ⚙ Non-Functional Requirements

- ✅ Performance: Supports up to 10,000 users with <3s response time  
- ✅ Security: Role-based access, HTTPS, encrypted passwords, PCI-DSS compliant  
- ✅ Usability: Clean UI, mobile responsive, multi-language support  
- ✅ Scalability: Cloud readiness and load handling  
- ✅ Availability: 99.9% uptime and fault tolerance

---

## 🏗 System Design and Architecture

- ### *Layered Architecture:*
  - <b>UI Layer</b>: Dashboard, Registration, Admin Panel
  - <b>Application Layer</b>: Scheduling, Ticketing, Notifications
  - <b>Utility Layer</b>: APIs, Logging, Exception Handling
  - <b>Core Layer</b>: Event, Ticket, Venue, and User management modules

- ### *Component Design:* Includes detailed modules like Payment, Authentication, Notifications, Reporting

- ### *Data Design:* Entity-relationship tables (User, Event, Venue, Ticket, Payment, Notification)

---

## 📊 Estimation Metrics

- *Function Point Analysis:* Total FP = 81  
- *Effort Estimation:* 202.5 person-hours (based on 2.5 productivity factor)  
- *Schedule Table:* Task-wise timeline with roles and dates  
- *Risk Table:* Lists probability, impact, and mitigation plans for key project risks  
- *Timeline Chart:* Cross-functional team responsibilities across project phases

---

## 📁 Structure

```bash
📂 SRS-Event-Management/
 └── SRS.pdf           # Full Software Requirement Specification Document
