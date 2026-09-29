# FeminIn Project Rules
Version: 1.0
Status: Mandatory

This document overrides personal preferences during development.
Every implementation decision must follow these rules.

====================================================
1. PROJECT MISSION
====================================================

Build the best women's health companion for Bangladeshi women.

The project should prioritize:

• Simplicity
• Privacy
• Reliability
• Low battery usage
• Low data usage
• Bengali-first experience

Never sacrifice these for flashy features.

====================================================
2. TARGET USERS
====================================================

Primary:
- Bangladeshi women
- Android users
- Budget phones
- Slow internet

Never optimize for flagship devices first.

====================================================
3. MVP RULES
====================================================

Only implement features listed in PRD.

If a feature is not inside the PRD,
DO NOT build it.

No feature creep.

====================================================
4. TECH STACK (Locked)
====================================================

Frontend
--------
Flutter

Language
--------
Dart

Backend
--------
FastAPI

Language
--------
Python

Database
--------
PostgreSQL

Offline Database
----------------
SQLite

Authentication
--------------
Firebase Authentication

Notifications
-------------
Firebase Cloud Messaging

Analytics
---------
Firebase Analytics

Crash Reporting
---------------
Firebase Crashlytics

Version Control
---------------
Git + GitHub

IDE
---
VS Code

AI Provider
-----------
Gemini API (Free Tier)

Architecture
------------
Clean Architecture

State Management
----------------
Riverpod

Routing
-------
GoRouter

Networking
----------
Dio

Dependency Injection
--------------------
Riverpod

Maps
----
Google Maps

PDF
---
pdf package (Flutter)
or backend ReportLab

====================================================
5. FREE TIER RULE
====================================================

Until FeminIn reaches 1,000 active users:

DO NOT purchase:

❌ Paid hosting

❌ Paid database

❌ Paid monitoring

❌ Paid analytics

❌ Paid AI plans

Use free tiers whenever possible.

====================================================
6. PERFORMANCE RULES
====================================================

Target APK

<80 MB

Maximum

150 MB

Startup

<3 seconds

Target RAM

<250 MB

Battery

Minimal background work

====================================================
7. UI RULES
====================================================

Use Material 3

Primary language:
বাংলা

Secondary:
English

No unnecessary animations.

No clutter.

Maximum
3 taps
to reach any important feature.

====================================================
8. AI RULES
====================================================

AI is NOT a doctor.

AI may:

✔ Explain

✔ Support

✔ Suggest

✔ Educate

AI may NEVER:

✘ Diagnose disease

✘ Prescribe medicine

✘ Replace doctors

Always include medical disclaimers when necessary.

====================================================
9. DATA RULES
====================================================

Store only required data.

Everything health-related is private.

Never collect unnecessary personal information.

Never share data.

Never sell data.

====================================================
10. LOCATION RULES
====================================================

GPS remains OFF by default.

Only activate when user enables:

• Carry Pad Reminder

or

• Pharmacy Reminder

Never poll GPS continuously.

Always use geofencing.

====================================================
11. NOTIFICATION RULES
====================================================

Maximum

3 notifications/day

Never spam.

Every notification must provide value.

====================================================
12. CODE RULES
====================================================

Use Clean Architecture.

Never duplicate business logic.

Meaningful variable names.

Comment only when necessary.

One responsibility per class.

====================================================
13. GIT RULES
====================================================

Commit often.

Commit messages:

feat:

fix:

docs:

refactor:

test:

Never push broken code to main.

====================================================
14. SECURITY RULES
====================================================

HTTPS only.

No API keys inside source code.

Secrets stored in .env.

Never commit credentials.

====================================================
15. DESIGN RULES
====================================================

Accessibility first.

Readable fonts.

High contrast.

Large touch targets.

====================================================
16. COST RULE
====================================================

Current Budget

≈ ৳185

Every technical decision must consider cost.

If there is a free alternative with acceptable quality,

choose it.

====================================================
17. FUTURE FEATURES
====================================================

Do NOT implement until MVP succeeds:

Pregnancy

Menopause

Partner Mode

Voice Assistant

Doctor Portal

Wearables

Telemedicine

====================================================
18. GOLDEN RULE
====================================================

Before implementing any feature ask:

"Does this solve a real problem for Bangladeshi women?"

If NO,

don't build it.

If MAYBE,

postpone it.

If YES,

build it properly.

====================================================
END
====================================================