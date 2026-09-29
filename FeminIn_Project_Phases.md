# FeminIn Development Phases

## Goal
Build FeminIn incrementally. Each phase must produce a working application before moving to the next.

---

# Phase 0 - Foundation
- Create GitHub repository
- Configure Flutter project
- Configure FastAPI project
- Set up folder structure
- Add linting and formatting
- Create CI workflow
- Define app theme and colors

**Exit Criteria:** Project builds successfully.

---

# Phase 1 - Core UI
- Splash screen
- Onboarding
- Login/Register UI
- Home screen
- Bottom navigation
- Settings UI

**Exit Criteria:** User can navigate all screens.

---

# Phase 2 - Local Data
- SQLite integration
- Cycle model
- Symptom model
- Pad model
- Local CRUD

**Exit Criteria:** Fully usable without internet.

---

# Phase 3 - Tracking
- Period logging
- Cycle calendar
- Prediction
- Symptoms
- Mood
- Notes

**Exit Criteria:** Complete cycle tracking works.

---

# Phase 4 - Pad Management
- Pad inventory
- Pad change timer
- Low stock
- Daily statistics

**Exit Criteria:** Pad tracking complete.

---

# Phase 5 - Notifications
- Period reminders
- Pad reminders
- Carry-extra-pad reminder
- Custom reminder settings

**Exit Criteria:** Notification system stable.

---

# Phase 6 - Backend
- FastAPI
- PostgreSQL
- Authentication
- Cloud sync
- API endpoints

**Exit Criteria:** Data syncs across devices.

---

# Phase 7 - AI Companion
- AI chat UI
- API integration
- Conversation history
- Context from tracker
- User confirmation before logging data

**Exit Criteria:** AI answers health questions safely.

---

# Phase 8 - Reports
- Six-month summary
- PDF export
- Share PDF

**Exit Criteria:** Doctor-ready report generated.

---

# Phase 9 - Optimization
- Offline sync improvements
- Performance
- Battery optimization
- Bug fixing
- Accessibility
- Bengali localization

**Exit Criteria:** Stable MVP.

---

# Phase 10 - Closed Beta
- Internal testing
- Fix critical issues
- Prepare Play Store assets
- Privacy policy
- Release to 50-100 users

**Exit Criteria:** MVP released for feedback.

---

# Post-MVP
- Pregnancy mode
- Geofencing
- Pharmacy reminder
- Menopause mode
- Voice assistant
- Doctor portal
- Partner mode

## Rule
Do not begin the next phase until the current phase is complete and tested.
