# MedCare

A clickable prototype of a patient healthcare app: find a doctor, book an appointment, see medical records and medication, chat with a doctor and request a home visit.

ICT Endterm project, team **ICT Boys** (Astana, 2026): Azka Zikry Zia Al Khalifa, Nurgaliyev Ildar, Skak Abuali, Abildayev Tamerlan.

## Run it

Open `index.html` in any browser. No install or build step is needed.

To sign in, tap **Use demo account** on the login screen, then **Log In**. You can also create a new account.

## Screens

| # | Screen | What works |
|---|--------|------------|
| S1 | Login | IIN or +7 phone validation, sign-up, password reset |
| S2 | Dashboard | Service shortcuts, next medicine dose, upcoming appointments (reschedule / cancel) |
| S3 | Find a Doctor | Search, specialty filter, 14-day schedule, booking with slot and double-booking checks |
| S4 | Profile | Personal info editing, appointments history, settings, help |
| S5 | Ask the Doctor | Chat with doctors, unread badges, demo auto-replies |
| S6 | Medical Records | Filters (visits, lab results, prescriptions), search, lab result details |
| S7 | Medication | Current / upcoming / history, mark doses as taken, next dose |
| S8 | Home Visit | Request a visit, status tracking (pending → confirmed), cancel |

## Limitations

This is a prototype. There is no backend: all data (accounts, bookings, messages) is stored in the browser's `localStorage` on the current device. Passwords are not hashed and doctor replies are pre-written. Do not enter real medical data.
