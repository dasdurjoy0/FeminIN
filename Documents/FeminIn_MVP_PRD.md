# FeminIn MVP Product Requirements Document (PRD)

**Version:** 0.5 (MVP)
**Status:** Draft
**Platform:** Android (Flutter)
**Target Market:** Bangladesh

---

# 1. Vision

Build the most trusted women's health companion for Bangladeshi women by combining period tracking, practical daily assistance, and AI-powered guidance in a lightweight mobile application.

# 2. Goals

## Primary
- Accurate menstrual cycle tracking
- Personalized reminders
- Bengali-first experience
- Offline-first operation
- Low-end Android compatibility

## Success Metrics
- 100 beta users
- 30-day retention > 40%
- Crash-free sessions > 99%
- Average app rating > 4.5

# 3. Non-Goals (MVP)

- Telemedicine
- Doctor booking
- Menopause mode
- Wearable integration
- Partner mode
- In-app purchases

# 4. Target Users

1. Teenagers
2. University students
3. Working women
4. Newly married women
5. Mothers
6. Women planning pregnancy

# 5. Core Features

## Cycle Tracking
- Log period start/end
- Flow level
- Symptoms
- Mood
- Notes
- Prediction

## Symptom Tracking
- Cramps
- Back pain
- Headache
- Acne
- Bloating
- Fatigue
- Nausea

## Pad Tracker
- Pad changes
- Daily usage
- Remaining stock
- Reminder intervals

## Smart Reminders
- Expected period
- Pad change
- Carry extra pad
- Low stock reminder (manual stock only in MVP)

## AI Companion (One-time API)

The assistant:
- Answers menstrual health questions
- Gives food suggestions
- Gives hydration reminders
- Suggests pain relief methods
- Explains common symptoms
- Provides emotional support
- Never diagnoses disease
- Always recommends consulting a healthcare professional when appropriate

AI writes to the database only after user confirmation.

## PDF Summary

Generate a six-month summary containing:
- Cycle history
- Average cycle
- Symptoms
- Mood
- Flow
- Notes

# 6. User Flow

Onboarding
→ Account
→ First cycle setup
→ Home Dashboard
→ Daily Check-in
→ AI Companion
→ Reports

# 7. Functional Requirements

FR-01 User registration
FR-02 Login
FR-03 Local database
FR-04 Cloud sync
FR-05 Notifications
FR-06 AI chat
FR-07 Report generation
FR-08 Settings
FR-09 Export PDF

# 8. Tech Stack

Frontend:
- Flutter

Backend:
- FastAPI

Database:
- PostgreSQL

Local:
- SQLite

Authentication:
- Firebase Authentication

Notifications:
- Firebase Cloud Messaging

Analytics:
- Firebase Analytics

Crash Reporting:
- Crashlytics

AI:
- API abstraction layer (Gemini/OpenAI interchangeable)

Hosting:
- Free-tier VPS when needed

# 9. Privacy

- Encrypt sensitive data in transit
- Request explicit consent for health and location data
- Allow account deletion
- Never sell user data

# 10. Performance

- Android 9+
- <150 MB storage
- Startup <3 seconds
- Offline support
- Battery optimized

# 11. MVP Roadmap

Sprint 1
- UI
- Navigation
- SQLite

Sprint 2
- Tracking
- Notifications

Sprint 3
- Firebase
- Sync

Sprint 4
- AI
- Reports

Sprint 5
- Testing
- Play Store preparation

# 12. Future Versions

v1.0
- Pregnancy mode
- Geofencing
- Pharmacy reminders

v2.0
- Menopause support
- Voice assistant
- Bengali speech
- Doctor portal
- Partner mode

# 13. Risks

- AI hallucinations
- Sensitive health data
- Battery usage
- Notification fatigue
- API cost growth

# 14. Definition of Done

- Core features functional
- Crash-free testing
- Offline synchronization works
- AI responses reviewed
- Privacy policy completed
- Ready for closed beta testing
