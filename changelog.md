### Detailed Changelog

---

**Version 0.1 — 17 June 2025**

**\[Added]**

* 3.8.1 Validation

**\[Changed / Updated]**

* 1.2.1 Functional Scope: Parking Availability & Rewards split into two sections.
* 1.2.1 Matching is manual changed to Acceptance is manual.
* 1.2.1 MMU SSO wording updated to clarify "prevent multiple logins in system".
* 1.2.2 Clarified definition of Phase 1 (pilot semester) and reworded fallback behavior for delayed parking data.
* 1.2.3 Reworded stakeholder needs statements for clarity and readability.
* 1.3.2 Removed FR-17 (record audio — privacy concern).
* 1.3.2 Added "Receive Notification" as new FR-10.
* 1.3 Relocated Product Overview section.
* 1.3.1 Relocated and modified Context Diagram.
* Removed duplicated Interface Requirements.

---

**Version 0.2 — 18–19 June 2025**

**\[Added]**

* 3.1.5 Request Ride — Alternate Flow for "no drivers available" scenario.
* 3.1.9 View Parking — Exception Flow for real-time data unavailability.
* 3.6 Scalability & Performance Constraints — details on performance degradation and reservation confirmation.

**\[Changed / Updated]**

* PR-2: Reworded parking system update rate (“refreshed at maximum every 2 minutes").
* PR-3: Revised acceptable performance degradation threshold from 25% → 15%.
* Clarified performance metrics: response time, availability, data accuracy (PR-5).
* PR-1: Added monitoring method (real device simulations on 4G).

---

**Version 0.3 — 18 June 2025**

**\[Added]**

* Fallback mechanism for Campus Parking API and MMU SSO (IF-004).

**\[Changed / Updated]**

* IF-007: Reworded “95% accuracy” — added calculation method.
* DB-005: Normalized vehicleInfo field into separate fields in Driver Table.
* DB-006: Moved vehicleType from Ride Offer Table to Driver Table.
* Corrected typo: vechicleType → vehicleType; separated vehicleInfo fields (Model, Type, Color, Year).

---

**Version 0.4 — 21 June 2025**

**\[Added]**

* 3.6 Security & Data Protection: WCAG 2.1 AA, ISO 27001, Malaysian PDPA compliance.
* 3.7 SSA-17, SSA-18: OWASP Top 10, SSO authentication only.
* 3.7 SSA-24, SSA-25: MTTR ≤ 4 hrs for critical bugs, code complexity threshold.
* 4.1 Verification Approach: Clarified testing responsibilities (Dev/QA/UAT).
* 5.1 Assumptions: Added network stability and third-party API dependencies.

**\[Changed / Updated]**

* 3.7 SSA-36 (previous SSA-32): Updated System Usability Scale target and user satisfaction rating.
* 4.2 Verification Criteria: Clarified target metrics for post-UAT user satisfaction.

**\[Removed]**

* Removed old SSA-36.
