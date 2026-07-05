# Future State Business Process Design

## Project Information

**Project Name:** EventSphere Salesforce Implementation

**Sprint:** Sprint 1 – Discovery & Planning

**Scenario:** Scenario 3 – Future-State (To-Be) Business Process Design

---

# Business Overview

Following the analysis of the current business process, EventSphere Pvt. Ltd. aims to transform its event management operations using Salesforce as a centralized platform. The future business process is designed to eliminate manual activities, improve collaboration between departments, and provide real-time visibility into event operations.

The objective of this document is to define the future ("To-Be") business process that will guide the design and implementation of the Salesforce solution.
---

# Future Event Lifecycle (To-Be Process)

The proposed future business process for EventSphere is as follows:

1. An Event Manager creates a new event in Salesforce.
2. The event is reviewed and approved before registrations begin.
3. Registration opens for approved events.
4. Attendees register through a centralized registration process.
5. The system validates event capacity before accepting registrations.
6. Registration confirmations are sent automatically.
7. Event Organizers assign speakers and manage event schedules.
8. The event is conducted as planned.
9. Attendance is recorded after the event.
10. Feedback is collected from attendees and speakers.
11. Management dashboards are automatically updated with the latest event information and performance metrics.

---

# Department Interactions

| Department | Future Role in Salesforce |
|------------|---------------------------|
| Marketing | Creates and promotes events while coordinating campaign activities. |
| Event Operations | Manages event details, schedules, venues, and overall event execution. |
| Finance | Tracks payments, refunds, and financial information using centralized records. |
| Customer Support | Assists attendees with registrations and resolves event-related inquiries. |
| Sales | Promotes events, manages customer relationships, and supports registrations. |
| Management | Monitors dashboards, reports, and key performance indicators (KPIs) to make business decisions. |

---

# Collaboration Between Departments

The future Salesforce platform will enable all departments to work from a single source of truth. Event information, attendee registrations, speaker details, and payment records will be shared across departments, reducing duplicate work and improving communication.

---

# Expected Business Improvements

| Current Process | Future Process |
|-----------------|----------------|
| Event information stored in Excel spreadsheets | Event information stored as centralized Salesforce records |
| Manual attendee registration tracking | Centralized attendee registration management |
| Manual confirmation emails | Automated confirmation notifications |
| Duplicate attendee records | Duplicate prevention through centralized data |
| Weekly manual reports | Real-time dashboards and reports |
| Separate department files | Shared Salesforce data across departments |
| Manual payment tracking | Centralized payment tracking |
| Limited visibility into event performance | Real-time event performance monitoring |

---

# Business Rules (Draft)

The following business rules have been identified during the discovery phase:

1. An event cannot exceed its maximum capacity.
2. Every attendee registration must be associated with exactly one event.
3. Only approved events can accept attendee registrations.
4. Duplicate attendee registrations for the same event should be prevented.
5. Every event must have an assigned Event Manager before it can be published.
6. Payments must be recorded before confirming registration for paid events.
7. Attendance can only be recorded after the event has been conducted.
8. Feedback can only be submitted by attendees who completed the event.

---

# Open Questions

The following business questions require clarification before implementation begins:

1. Can an attendee register multiple guests under a single registration?
2. Should free events and paid events follow different registration processes?
3. Should registered attendees be automatically notified if an event is cancelled or rescheduled?
4. Can speakers be assigned to multiple events occurring on the same day?
5. Should attendees be allowed to cancel their registrations online?
6. Is manager approval required for all events or only certain event types?
7. Should attendance be recorded manually or through a check-in process?
8. What information should be displayed on management dashboards by default?
---

# Summary

This document defines the proposed future ("To-Be") business process for EventSphere Pvt. Ltd. It establishes a shared vision of how the organization will operate after implementing Salesforce by centralizing data, improving collaboration, reducing manual work, and supporting future business growth. The documented business rules and open questions provide a foundation for the functional requirements and solution design in the upcoming project phases.