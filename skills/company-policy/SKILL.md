---
name: company-policy
description: Skill for answering questions about company policies, such as HR policies, leave/time-off rules, code of conduct, IT/security policies, expense and reimbursement rules, and other internal guidelines. Use when the user asks about a company policy, what the rules are for something, or whether an action is allowed under company guidelines.
---

# Company Policy Skill

## Purpose
Help users understand and navigate the company's official policies (HR, leave, conduct, IT/security, expenses, remote work, etc.) by locating the relevant policy document, summarizing it accurately, and pointing to the source for full details.

## When to use this skill
- The user asks "what is the policy on X?"
- The user asks whether something is allowed/required per company rules.
- The user needs a summary or excerpt of an HR, legal, security, or compliance policy.
- The user asks where to find a specific policy document.

## Instructions
1. Identify the specific policy topic the user is asking about (e.g., leave, remote work, expenses, code of conduct, data security).
2. Search the company's policy documentation source (e.g., internal wiki, HR portal, shared drive, or repository policy files) for the relevant document.
3. Summarize the applicable rules clearly and concisely, using plain language.
4. Always cite where the information came from (document name, section, or link) so the user can verify details or find full context.
5. If the policy cannot be located or is ambiguous, tell the user clearly instead of guessing, and suggest who to contact (e.g., HR or the policy owner) for an authoritative answer.
6. Do not provide legal, medical, or financial advice beyond what is explicitly stated in the company policy documents.
7. Flag outdated or conflicting policy information if multiple versions are found, and recommend confirming with the policy owner.

## Notes
- Policies may change over time; always prefer the most recently updated source available.
- Sensitive HR matters (e.g., disciplinary actions, personal leave details) should be handled with discretion and directed to HR when appropriate.

## Sample Data
The following is illustrative sample data for **Nimbus Robotics Inc.**, a fictional example company, used for testing and demonstration purposes only (not real company data):

| Policy ID | Policy | Category | Summary | Applies To | Last Updated | Version | Owner |
|-----------|--------|----------|---------|------------|--------------|---------|-------|
| POL-HR-001 | Paid Time Off (PTO) | Leave | Full-time employees accrue 15 PTO days per year (1.25 days/month), up to a max carryover of 5 days into the next calendar year. | All Full-Time Employees | 2025-01-10 | v3.2 | HR Department – Aisha Patel, Director of HR |
| POL-WA-004 | Remote Work Policy | Work Arrangement | Employees may work remotely up to 3 days per week with manager approval; fully remote roles require VP-level sign-off. | All Employees | 2025-02-14 | v2.0 | People Operations – Jordan Lee |
| POL-LC-002 | Code of Conduct | Conduct | All employees must act with integrity and respect, disclose conflicts of interest, and avoid accepting gifts over $100 from vendors. | All Employees & Contractors | 2024-11-01 | v4.1 | Legal & Compliance – Samuel Okafor, General Counsel |
| POL-FIN-007 | Expense Reimbursement | Finance | Business expenses under $75 do not require pre-approval; itemized receipts are required for all claims over $25 and must be submitted within 30 days. | All Employees | 2025-03-05 | v1.8 | Finance Team – Grace Muriithi, Controller |
| POL-SEC-003 | IT Security & Acceptable Use | IT/Security | Employees must use company-issued devices with MFA enabled for all internal systems; personal devices require MDM enrollment before accessing company data. | All Employees & Contractors | 2025-04-20 | v5.0 | IT Security Team – Devon Ashworth, CISO |
| POL-HR-005 | Parental Leave | Leave | Eligible employees receive 12 weeks of paid parental leave (birth, adoption, or foster placement), usable within 12 months of the qualifying event. | Employees with 6+ Months Tenure | 2024-12-01 | v2.3 | HR Department – Aisha Patel, Director of HR |
| POL-LC-006 | Anti-Harassment Policy | Conduct | Zero tolerance for harassment or discrimination based on protected class; report incidents to HR or the anonymous ethics hotline within 5 business days of awareness. | All Employees, Contractors & Vendors | 2025-01-25 | v3.0 | HR & Legal – Samuel Okafor, General Counsel |
| POL-FIN-009 | Travel & Business Expense Policy | Finance | Domestic flights must be booked in economy class; international flights over 6 hours may be booked in premium economy with manager approval. | Employees Traveling for Business | 2025-05-12 | v1.4 | Finance Team – Grace Muriithi, Controller |
| POL-SEC-010 | Data Classification & Handling | IT/Security | Customer robotics telemetry data is classified as "Confidential" and must be stored only in approved, encrypted cloud environments. | Engineering & Data Teams | 2025-06-30 | v1.1 | IT Security Team – Devon Ashworth, CISO |
