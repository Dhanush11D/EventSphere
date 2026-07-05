# Stakeholder Analysis

## Project Information

**Project Name:** EventSphere Salesforce Implementation

**Sprint:** Sprint 1 – Discovery & Planning

**Scenario:** Scenario 1 – Client Discovery Workshop & Stakeholder Identification

---

# Business Overview

EventSphere Pvt. Ltd. is an event management company that organizes corporate conferences, technical meetups, university events, workshops, and product launches.

Currently, the company manages its operations using spreadsheets, emails, and phone calls. As the business has grown, this approach has made it difficult to manage event information efficiently and has resulted in duplicate data, manual processes, and limited visibility into business performance.

To address these challenges, EventSphere has decided to implement Salesforce as a centralized platform to manage the complete event lifecycle.
---

# Current Business Challenges

The client identified the following operational challenges:

- Event information is scattered across multiple Excel spreadsheets.
- Attendee registrations are tracked manually, making the process time-consuming.
- Organizers do not have real-time visibility into available seats for events.
- Speaker information is stored separately from event details, leading to disconnected data.
- Different departments maintain duplicate copies of the same information.
- Senior management lacks real-time dashboards to monitor event performance and key business metrics.
---

# Stakeholder Analysis

| Stakeholder | Responsibilities | Expected Salesforce Access |
|-------------|------------------|----------------------------|
| System Administrator | Manages users, security, configurations, and overall system maintenance. | Full Administrative Access |
| Event Manager | Creates events, manages event lifecycle, and monitors overall event progress. | High Access |
| Event Organizer | Coordinates speakers, venues, schedules, and logistics for events. | Standard Internal User |
| Registration Executive | Manages attendee registrations and maintains registration records. | Standard Internal User |
| Speaker | Views assigned sessions and event information. | Limited Access (To be finalized) |
| Attendee | Registers for events and views registration confirmations. | External Access (To be finalized) |
| Finance Team | Tracks payments, refunds, and financial records related to events. | Finance-Specific Access |
| Senior Management | Monitors dashboards, reports, and business performance metrics. | Read-Only Executive Access |
---

# Initial Observations

- Event information is currently spread across multiple systems, creating data inconsistency.
- Different departments maintain duplicate records, indicating a need for centralized data management.
- Multiple user roles will require different levels of access within Salesforce.
- Reporting and dashboards will be important for management to monitor event performance.
- Several manual processes, such as attendee registration and seat tracking, could be automated in future phases.
---

# Questions for Future Clarification

1. Will speakers log in directly to Salesforce, or will they use an external portal?
2. Will attendees register through Salesforce Experience Cloud or another registration system?
3. Should the Finance Team manage payments and refunds within Salesforce?
4. Will event capacity be fixed, or can it be changed after an event is created?
5. Is manager approval required before an event is published?
6. Should Event Organizers only be able to view and manage events assigned to them?
7. Are integrations with payment gateways or email marketing platforms planned for future phases?
8. Which key performance indicators (KPIs) should appear on management dashboards?
---

# Summary

This stakeholder analysis provides a clear understanding of the users who will interact with the EventSphere platform and their responsibilities. The information documented in this analysis will serve as the foundation for designing Salesforce security, custom objects, page layouts, automations, reports, and user experiences in the upcoming project phases.