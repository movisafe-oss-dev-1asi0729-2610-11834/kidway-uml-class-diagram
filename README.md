# KidWay UML Class Diagram Design

Professional UML class diagram repository for **KidWay**, a smart school transport management platform focused on routes, students, fleet operations, trips, attendance, alerts, incidents, reporting, analytics, and operational traceability.

This repository contains the **Object-Oriented Design Software** artifacts for KidWay, using UML class diagrams organized by bounded context.

---

## Project Overview

KidWay is designed for independent school transport operators and transport companies that need to manage routes, vehicles, students, attendance, trips, notifications, and incidents in real time.

The UML class diagrams in this repository describe the main domain entities, relationships, enumerations, and responsibilities required to support the KidWay business model.

---

## Repository Structure

```text
.
├── diagrams
│   ├── AlertsNotificationsClassDiagram.puml
│   ├── AssignmentManagementClassDiagram.puml
│   ├── AttendanceTrackingClassDiagram.puml
│   ├── CompanyManagementClassDiagram.puml
│   ├── DashboardAnalyticsClassDiagram.puml
│   ├── DriverManagementClassDiagram.puml
│   ├── FleetManagementClassDiagram.puml
│   ├── IdentityAccessClassDiagram.puml
│   ├── IncidentManagementClassDiagram.puml
│   ├── RealTimeTrackingClassDiagram.puml
│   ├── RouteManagementClassDiagram.puml
│   ├── StudentManagementClassDiagram.puml
│   ├── SubscriptionPaymentsClassDiagram.puml
│   ├── TripManagementClassDiagram.puml
│   └── UserProfilesClassDiagram.puml
├── kidway-uml-diagrams.csproj
├── kidway-uml-diagrams.sln
└── src
    └── images/
```

---

## Bounded Contexts Included

### Generic / Supporting

1. **Identity & Access Management**  
   Manages authentication, authorization, users, roles, sessions, credentials, and access permissions.

2. **User Profiles**  
   Manages user profile information, company profiles, contact data, preferences, and notification settings.

3. **Subscription & Payments**  
   Manages plans, subscriptions, invoices, payments, and billing accounts.

4. **Dashboard & Analytics**  
   Provides dashboard widgets, KPIs, summaries, filters, and operational overview information.

### Core Domain

5. **Fleet Management**  
   Models vehicles, capacity, maintenance records, availability, and fleet assignments.

6. **Driver Management**  
   Models drivers, licenses, availability, schedules, and operational assignments.

7. **Route Management**  
   Models routes, stops, schedules, pickup points, and route optimization rules.

8. **Student Management**  
   Models students, guardians, contacts, pickup authorizations, and school information.

9. **Assignment Management**  
   Models assignments between students, routes, vehicles, drivers, and schedules.

10. **Real-Time Tracking**  
    Models GPS positions, live trips, ETA calculations, route progress, and tracking history.

11. **Trip Management**  
    Models trips, trip states, execution records, delays, cancellations, and completion events.

12. **Attendance Tracking**  
    Models boarding records, drop-off confirmations, absences, attendance states, and timestamps.

13. **Alerts & Notifications**  
    Models alerts, notifications, recipients, delivery rules, and escalation policies.

14. **Incident Management**  
    Models incidents, severity levels, assignments, corrective actions, and resolution evidence.

15. **Reports & Analytics**  
    Models reports, templates, metrics, trends, dashboards, and export files.

16. **Company Management**  
    Models company profiles, branches, operational settings, internal structure, and preferences.

---

## Technologies

- PlantUML
- UML Class Diagrams
- C#
- .NET Solution Structure
- Domain-Driven Design (DDD)

---

## How to Generate Diagrams

Install PlantUML and run:

```bash
plantuml diagrams/*.puml
```

Generated images can be stored in:

```text
src/images/
```

---

## Purpose

This repository supports the following project section:

```text
4.7. Object-Oriented Design Software
4.7.1. Class Diagrams
```

It provides the object-oriented model used to connect KidWay's bounded contexts with future database design and implementation artifacts.

---

## Recommended Workflow

1. Update or create `.puml` files inside `diagrams/`.
2. Generate diagram images with PlantUML.
3. Store exported images in `src/images/`.
4. Reference the diagrams in the final project report.
5. Keep class names, relationships, and enumerations aligned with KidWay's bounded contexts.

---

## License

Academic and educational use only.
