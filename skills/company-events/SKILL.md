---
name: company-events
description: Skill for answering questions about company events, such as scheduled meetings, town halls, workshops, holidays, offsites, webinars, and other calendar activities. Use when the user asks what events are coming up, when an event is scheduled, or wants details about a company event.
---

# Company Events Skill

## Purpose
Help users find out about upcoming or past company events, including their date, time, location (physical or virtual), and purpose, by consulting the company's event calendar or announcements.

## When to use this skill
- The user asks "what events are scheduled?" or "when is the next town hall / offsite / workshop?"
- The user wants details (date, time, venue, organizer, agenda) about a specific event.
- The user asks about company holidays or scheduled downtime that is tracked as an event.
- The user wants a list of upcoming events within a given time range.

## Instructions
1. Determine the type of event the user is asking about (e.g., town hall, holiday, training, offsite, product launch, webinar) and any relevant timeframe.
2. Look up the company's event calendar, announcements, or events log (e.g., shared calendar, intranet events page, or repository events file) for matching entries.
3. Present event details clearly: event name, date, time (with timezone if relevant), location or meeting link, and a brief description/agenda.
4. If multiple events match, list them in chronological order.
5. Cite the source of the event information so the user can verify or get further details (e.g., calendar invite, announcement link).
6. If no matching event is found, tell the user clearly rather than guessing, and suggest checking the official calendar or asking the event organizer.
7. Note any events that are tentative, rescheduled, or cancelled if that status is available in the source.

## Notes
- Always use the most current version of the event schedule, since events can be added, rescheduled, or cancelled.
- Respect privacy for events that may be restricted to specific teams or roles.

## Sample Data
The following is illustrative sample data for testing and demonstration purposes only (not real company data):

| Date | Time (Timezone) | Event | Type | Location / Link | Status |
|------|------------------|-------|------|------------------|--------|
| 2025-10-02 | 10:00 AM (PT) | Quarterly Town Hall | Town Hall | Zoom: company.zoom.us/townhall | Confirmed |
| 2025-10-14 | All Day | Company Holiday - Indigenous Peoples' Day | Holiday | N/A | Confirmed |
| 2025-10-21 | 1:00 PM (PT) | New Hire Onboarding Workshop | Workshop | HQ Training Room B | Confirmed |
| 2025-11-05 | 9:00 AM (PT) | Annual Company Offsite | Offsite | Lake Tahoe Conference Center | Confirmed |
| 2025-11-18 | 11:00 AM (PT) | Product Roadmap Webinar | Webinar | Zoom: company.zoom.us/webinar | Tentative |
| 2025-12-19 | All Day | Winter Break (Company Holiday) | Holiday | N/A | Confirmed |
| 2026-01-08 | 2:00 PM (PT) | Security Awareness Training | Training | Microsoft Teams | Rescheduled from 2025-12-11 |
