# HCI---University-Library-Mobile-App
MOBILE APP GROUP TERM ASSIGNMENT
University Library App — Mobile App Design Project
A mobile app concept that lets university library patrons browse the catalogue, check book availability, reserve or borrow titles, and manage their account — all from their phone, without needing to visit the library desk to find out if a book is in.
Team
Name	Role / contributions
[Name 1]	e.g. Wireframes (screens 1–6), README
[Name 2]	e.g. Prototype linking, usability testing
[Name 3]	e.g. Screens 7–13, test synthesis
(List every member here. Each name should map to commits/PRs in this repo — that's how "meaningful contribution" gets verified.)
Problem
University students frequently have no easy way to check whether a book is available before walking to the library, or to track when their borrowed books are due. This leads to wasted trips, missed return dates, and unnecessary fines. The University Library App puts the catalogue, availability status, and loan/reservation history directly in students' pockets.
Target Users
Undergraduate and postgraduate students who use the university library regularly for coursework and research, are comfortable with mobile apps, and want a quick way to check availability before making a trip.
Returning/renewing borrowers who need a fast way to see what they currently have out, when it's due, and to renew without visiting the desk.
Features
Browse "Recently Added" and "Popular Books" on the Home screen
Search the full catalogue by title/author
View book details: description, rating, and live availability status
Reserve a book for pickup, or borrow it directly
Confirmation screens for both reservations and borrowing
Track all borrowed books and reservations from a Profile screen, with dedicated list views
Cancel reservations or renew borrowed books
Notifications for pickup-ready reservations, due-date reminders, and new arrivals
Account settings (edit profile, notification preferences, log out)
Screens (13 total)
App Icon / Splash
Welcome / Onboarding
Sign Up / Log In
Home
Search Results
Book Details
Reservation Confirmation
Borrowing Confirmation
Profile
My Reservations
My Borrowed Books
Notifications
Settings
Prototype
Figma link: [paste link here once screens are rebuilt/linked in Figma — set sharing to "Anyone with the link can view"]
Wireframe source files: `/artefacts/wireframes/*.svg` — import these directly into Figma (drag onto canvas) for a fully editable starting point
Working reference prototype: `/artefacts/wireframes/prototype.html` — open in any browser for a functional click-through with live state (reserving/borrowing actually updates the lists). Use this to sanity-check flows before rebuilding them as linked Figma frames, and as the test instrument for usability sessions if you don't want to wait on the Figma version.
Scenarios demonstrated:
New user sign-up → reserve a book: Welcome → Sign Up/Log In → Home → Book Details → Reservation Confirmation → My Reservations
Search → borrow a book: Home → Search Results → Book Details → Borrowing Confirmation → My Borrowed Books
Check notifications → manage account: Home (bell icon) → Notifications; Profile (gear icon) → Settings → Log Out
Usability Testing
Participants: 5 representative users (university students who currently use, or would use, library services)
Method: moderated, think-aloud sessions — see `/artefacts/testing/test-script.md` for the full script and per-task success criteria
Tasks tested: the 3 scenarios above
Findings: logged in `/artefacts/testing/findings-template.md`
Revisions: changes made in direct response to findings are tracked in `/artefacts/testing/revisions-template.md`, with a before/after for each change
Repository Structure
```
/artefacts
  /wireframes
    01_app_icon.svg ... 13_settings.svg   → editable Figma-ready wireframes
    prototype.html                          → working interactive reference prototype
  /testing
    test-script.md         → usability test script for the 5 sessions
    findings-template.md   → synthesized results across participants
    revisions-template.md  → design changes made in response to findings
README.md
```
Findings & Reflection
(Fill in after testing is complete.) What did testing reveal overall? What worked well, what didn't, and what would the team do differently with more time or a larger sample?
