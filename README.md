# HCI — University Library Mobile App

**MOBILE APP GROUP TERM ASSIGNMENT**

## University Library App — Mobile App Design Project

A mobile app concept that lets university library patrons browse the catalogue, check book availability, reserve or borrow titles, and manage their account — all from their phone, without needing to visit the library desk to find out if a book is in.


### Problem

University students frequently have no easy way to check whether a book is available before walking to the library, or to track when their borrowed books are due. This leads to wasted trips, missed return dates, and unnecessary fines. The University Library App puts the catalogue, availability status, and loan/reservation history directly in students' pockets.

### Target Users

- **Undergraduate and postgraduate students** who use the university library regularly for coursework and research, are comfortable with mobile apps, and want a quick way to check availability before making a trip.
- **Returning/renewing borrowers** who need a fast way to see what they currently have out, when it's due, and to renew without visiting the desk.

---

### Features

- Browse "Recently Added" and "Popular Books" on the Home screen
- Search the full catalogue by title/author
- View book details: description, rating, and live availability status
- Reserve a book for pickup, or borrow it directly
- Confirmation screens for both reservations and borrowing
- Track all borrowed books and reservations from a Profile screen, with dedicated list views
- Cancel reservations or renew borrowed books
- Notifications for pickup-ready reservations, due-date reminders, and new arrivals
- Full account flow: Sign Up, Log In, **Forgot Password**, and password-reset confirmation
- Account settings (edit profile, notification preferences, change password, log out)

---

### Screens (16 total)

| # | Screen | Description |
|---|--------|-------------|
| 1 | App Icon / Splash | Brand entry point; tap to continue |
| 2 | Welcome / Onboarding | Value proposition + "Get Started" |
| 3 | Sign Up / Log In | Email + password; links to Sign Up and Forgot Password |
| 4 | Sign Up | Full name, email, password, confirm password |
| 5 | Forgot Password | Enter email to request a reset link |
| 6 | Check Your Email (Reset Sent) | Confirmation that a reset link was sent |
| 7 | Home | Recently Added, Popular Books, search entry, notifications |
| 8 | Search Results | Full catalogue list |
| 9 | Book Details | Cover, description, rating, availability, Reserve / Borrow |
| 10 | Reservation Confirmation | Success state + pickup date |
| 11 | Borrowing Confirmation | Success state + due date |
| 12 | Profile | Avatar, borrowed books preview, reservations preview |
| 13 | My Reservations | Full list with cancel action |
| 14 | My Borrowed Books | Full list with renew action |
| 15 | Notifications | Unread indicators, pickup & due reminders |
| 16 | Settings | Edit profile, notification prefs, change password, log out |

---

### Prototype

**Figma link:** [paste link here once screens are rebuilt/linked in Figma — set sharing to "Anyone with the link can view"]

**Wireframe source files:** `/artefacts/wireframes/*.svg` — import these directly into Figma (drag onto canvas) for a fully editable starting point.

**Working reference prototype:** `/artefacts/wireframes/prototype.html` — open in any browser for a functional click-through with live state (reserving/borrowing actually updates the lists). Use this to sanity-check flows before rebuilding them as linked Figma frames, and as the test instrument for usability sessions if you don't want to wait on the Figma version.

#### Recent prototype updates (auth flow)

- **Forgot Password** screen is fully linked from the Log In screen.
- Email validation on "Send Reset Link" (empty field shows a toast).
- **Check Your Email** confirmation screen added after a successful reset request.
- All three auth-related screens (Sign Up, Forgot Password, Reset Sent) share consistent back-navigation to Log In.

#### Scenarios demonstrated

1. **New user sign-up → reserve a book**  
   Welcome → Sign Up → Home → Book Details → Reservation Confirmation → My Reservations

2. **Search → borrow a book**  
   Home → Search Results → Book Details → Borrowing Confirmation → My Borrowed Books

3. **Forgot password recovery**  
   Log In → Forgot Password → enter email → Send Reset Link → Check Your Email → Back to Log In

4. **Check notifications → manage account**  
   Home (bell icon) → Notifications; Profile (gear icon) → Settings → Log Out

---

### Usability Testing

- **Participants:** 5 representative users (university students who currently use, or would use, library services)
- **Method:** moderated, think-aloud sessions — see `/artefacts/testing/test-script.md` for the full script and per-task success criteria
- **Tasks tested:** the scenarios above (including the new password-recovery path)
- **Findings:** logged in `/artefacts/testing/findings-template.md`
- **Revisions:** changes made in direct response to findings are tracked in `/artefacts/testing/revisions-template.md`, with a before/after for each change

---

### Repository Structure
/README.md
/University Library App SVG files
/welcome_page
  welcome_page.svg
/signup and Login
  03_signup_login 1 copy.svg
/Sign_Up_Screen
  sign_up.svg
/Forgot_Password
  forgot_password_screen.svg
/home
  home_page.svg
/search Results
  search_results.svg
/Book_Details
  book_details.svg
/reservation_confirmation
  07_reservation_confirmation.svg
/Borrowing confirmation
  08_borrowing_confirmation.svg
/Profile
  09_profile.svg
/my_reservations
  10_my_reservations.svg
/Borrow_Page
  my_borrowed_books.svg
/Notifications
  notifications.svg
/settings
  13_settings.svg
/prototype
  University Library App.fig
  University Library App.html
/settings and Borrow_Page
  Settings_and_Borrow_Page.fig
/welcome Page
  University Library App.fig
/University Library Mobile App.bmpr
