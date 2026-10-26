# Changelog

All notable changes to Seisin are documented here. This project follows
[Semantic Versioning](https://semver.org/).

## 1.4.0 - 26/10/2026

### Save jobs from your browser
- A free Seisin extension for Chrome, Edge and Firefox (Brave and Opera use the
  Chrome one). On a job posting a small Seisin mark appears in the corner: click
  it, check the role and company it found, and click Planned or Applied. The
  location, salary, work type and description come with it
- Works on any job board or careers page that publishes the job's details, with
  dedicated reading for LinkedIn, Indeed, Glassdoor, Workday, Google, Amazon,
  Apple and more; anything it can't find you type in. Saving is unlimited
- The toolbar icon opens the same card on any page, and the mark can be hidden
  on any site
- Saving the same posting twice warns you first, with the date you saved it
- The job description is saved with it, so you still have the advert after it
  comes down. Read it on the application and in the Interview Suite, and search
  it from Applications ("which job mentioned visa sponsorship?")
- Saving as Applied lets you pick the resume you sent
- Seisin closed? Choose "Add it when Seisin opens": the job waits in your browser
  and goes into your Planned list within seconds of Seisin opening
- Alt+Shift+S opens it from the keyboard (Option+Shift+S on a Mac)
- The first time you install it, a short setup page opens once in a new tab on getseisin.com
- To show its mark it checks the pages you open for job details, inside your
  browser, and sends nothing; a posting is sent only when you save it, and only
  to Seisin on your own computer: no account, no analytics
- Connect it once with a button in the extension and Allow in Seisin, or with a
  one-time code from Settings. Disconnect any browser in Settings
- Back in Seisin, a summary shows the jobs saved from your browser while you
  were away

### Job descriptions
- Every application has a Job description section: filled in by the extension or
  by pasting a job link, or paste the advert in yourself
- CSV and Excel exports include it

### Runs in the background, if you want it to
- Seisin can stay in the tray when you close its window and open when you sign
  in, so the extension can save jobs any time. You choose on first launch, and
  can change it in Settings under Startup. Nothing is sent while it runs

### Updates install themselves
- On Windows and the Linux AppImage, new versions download in the background and
  install when you restart, with a Restart now / Later choice. Later installs it
  the next time you quit
- macOS and the .deb keep the update banner that links to the download page
- Settings shows the update's progress: checking, downloading, ready to restart

### An anonymous launch count, only if you ask for it
- At most once a day Seisin can send a simple counter: the version, the operating
  system and the installer type. No identifier, no account, and nothing from your
  job search (applications, offers, resumes, cover letters, interviews or notes)
- It is off unless you tick the box on the welcome or What's New screen, or turn
  it on in Settings
- An optional one-tap "Where did you hear about Seisin?" in a small corner card,
  asked once and sent once with the count

### Backup, restore and delete
- Back Up Everything now saves everything in one file: your data, uploaded resume
  files and settings such as offer notes. The new Restore from Backup loads it
  back, here or on another computer; before, the backup held applications only
  and could not be restored
- Export to Excel gives one workbook with a sheet each for applications, interview
  rounds and questions, offers, Network, cover letters, resumes and weekly goals
- Settings > Data Management has Delete All Data, which removes everything after
  you type a confirmation, with the backup and the Excel copy offered first

### Dates follow your own clock
- Dates now use your own time zone instead of UTC: an application added just after
  midnight gets your day, and the Added date, backup file names and the date a
  free-plan limit resets all match your clock
- Settings has a new Date Format: DD/MM/YYYY, MM/DD/YYYY or YYYY-MM-DD. It sets how
  dates read across Seisin, and how a date like 03/04/2026 is read when you import
- Weekly goals are filed under your own week start; goals saved by 1.2 and 1.3 are
  moved to the right week automatically the first time you open 1.4

### Smaller changes
- Recruiter is now an application source, and CSV import recognises it
- Apprenticeship is now an employment type, alongside Internship
- The Interview Suite follows each application's stage: assessments (online tests, assessment centres, take-home tasks) get their own types, due dates and time limits, and an offer links to its offer sheet with a "Before you accept" checklist. Suggested checklists follow the rounds still ahead, next one first, and the list filters by stage
- Source takes any job board: the common ones are listed (Glassdoor, Handshake, Reed and more), and you can type your own
- Notifications, Settings and the Documents and Interview Suite tabs have a cleaner look, and Settings uses the full width of a large window
- Deleting one thing (an application, a round, a contact, an offer sheet, a resume file) is now press and hold, with a few seconds to undo; bulk deletes still ask first
- Long lists and panels fade at the edge when there's more to scroll; drop zones react as soon as a file is dragged over the window, and the resume builder's import takes a dropped file
- Buttons that change their label (Saving..., Copied) ease to their new size, and the loading screen draws the Seisin mark
- Every Analytics chart and the map can show their numbers as a table, and the "?" explanations (including how the best offer is chosen) open from the keyboard too
- Keyboard use throughout: Escape closes only the topmost window, focus returns where it came from, and every control can be reached with Tab
- Reaching a free-plan limit now says when it resets and that premium will lift it
- Settings: "Check on Launch" is now "Check for Updates Automatically", next to the
  new "Share an Anonymous Launch Count"

## 1.3.0 - 28/09/2026

### Cover letter builder
- A new Cover Letters area, alongside resumes in Documents: paragraph-by-paragraph
  prompts help you write your own letter, nothing is generated for you
- A real header: your contact details, who you're writing to, and a sign-off
- A rule-based completeness check for each section, and export to PDF or Word
- Attach a letter to an application, the same way resumes already link through
- Resume and cover letter exports never run onto a second page: if the content
  would, Seisin tightens spacing and text size automatically and lets you know

### Network
- Track the people behind your search separately from any one application:
  recruiters, referrals, coworkers, people from school, and everyone in between
- Log a dated note after each conversation, and tag a contact to an application
- Adding an application flags anyone you already know at that company
- Writing a letter for a company where you already know someone surfaces
  that contact too, with a nudge to check with them first before you name
  them; the wording is still yours, never generated for you

### Free plan limits
- Exporting a resume is 10/month and exporting a cover letter is 3/week, whether
  as PDF, Word, or print. A save you cancel does not count, and Print is
  unavailable once a limit is reached so it cannot be used to get around it
- Adding new contacts to Network is 20 in your first 30 days, then 5/month
- Saving, editing, and viewing are never limited, and nothing you already have is
  removed
- Settings has a new Your Free Plan section showing what is left and when each
  limit resets, and each action shows its remaining count before you use it

### Applications
- A No Response status for roles that went quiet, kept separate from
  Rejected and out of the "still waiting" reminder
- The Add/Edit form is wider, with more fields visible per row

### Everywhere else
- Settings moved to its own icon in the top bar, making room for Network
  alongside the other sections
- Ctrl+scroll or a trackpad pinch zooms the resume and cover letter preview

## 1.2.0 - 10/09/2026

### macOS and Linux
- Seisin now runs on macOS (Apple Silicon) and Linux, alongside Windows

### Weekly goals
- Set your own targets for the week, like applications sent or follow-ups
  made, and tick them off from a checklist in the top bar

### A report when you land a role
- Accepting an offer opens a summary of the whole search: what worked,
  your strongest sources, and how long it took

### Resume builder
- Every stored CV now shows the applications it was used on, and links
  straight through to them

### Applications
- Each application can carry its own currency, filled in from the job
  link where it is there, and kept through import and export
- The offer comparison switches between your converted totals and each
  offer in the currency it was made in
- One click edits a row, and an application can move to its next stage
  straight from the table

### Withdrawing an application
- A dedicated Withdrawn status keeps abandoned applications out of your
  active pipeline
- Cancelling an accepted offer now offers to reopen any applications you
  withdrew along the way

### Sounds and celebrations
- Subtle sounds and a cleaner set of celebrations as an application moves
  forward, with confetti kept for offers. All of it toggleable in Settings.
- Status-change confirmations now show on a dimmed backdrop so they stay
  legible over any page

### Everywhere else
- Faster startup and instant navigation, holding up with hundreds of
  applications tracked
- Search now ranks results by relevance across applications, interviews
  and the question bank
- Pasting a job link recognises more sites and fills in more of the form
- A visual and contrast pass across the app, plus a long list of smaller
  fixes

## 1.1.0 - 12/08/2026

### Planned pipeline
- Track roles before you apply and watch their closing dates
- Log an application as applied in one click straight from Planned
- Follow-through rate in Analytics, and a nudge on Planned roles left
  untouched for three weeks

### Resume builder
- Build a resume from five templates, with full control over fonts,
  spacing, colour, accent and section order
- Import an existing resume from PDF or Word
- Offline analysis: a completeness meter, plain-language tips, nudges
  against weak bullet openers, and a template recommendation
- Export to PDF or Word

### Interview suite
- Track every round with contacts, research notes, and a prep checklist
  tailored to the round type
- Follow-up reminders when a round has gone quiet
- A searchable question bank with a STAR answer builder
- An in-app calendar bringing every interview and offer deadline onto one
  grid, exportable as `.ics` or linked straight to Google or Outlook

### Offers
- Record what you were actually offered, kept separate from the
  advertised salary range, and compare offers side by side in a
  redesigned comparison view
- Offer deadlines now show on the Applications table and the calendar
- Delete an offer sheet you no longer need
- New filters for work type, employment type, and upcoming deadlines

### Applications
- Salary period (yearly, monthly, or total for the term) and employment
  type (full-time, part-time, contract, internship, temporary), with a
  fixed-term length where it applies

### Everywhere else
- A lighter, more typographic visual style across every page
- A restyled world map
- Dates now read DD/MM/YYYY

### Your data
- Imported files (a CV as PDF or Word, applications as CSV or Excel) are
  read on your own machine. Resume analysis runs entirely on-device.

## 1.0.0 - 16/07/2026

First public release. Windows only. Seisin is a free desktop app that keeps an
entire job search in one place, every application, interview and offer, and turns
the record into analytics automatically.

### Highlights
- Application tracking with a full status pipeline, from planned to offer
- Analytics: weekly pace, pipeline health, response by source, average response
  time, and a conversion funnel, each with a plain-English explanation
- Interview suite with rounds, contacts, research notes, and a prep checklist
- Offer comparison side by side, with currency conversion for roles abroad
- Resume storage with tagging, linked to the applications each version was used for
- Interactive world map of where you are applying
- Add roles by hand, paste a job URL to parse the posting, or import from CSV or
  Excel with column mapping; export to CSV, Excel, or JSON
- Light, dark, and midnight themes with a custom accent colour
- Privacy mode that blurs salary figures and names

### Your data
- Everything is stored in a SQLite file on your own machine. There is no account
  and no sign-in.
- Seisin makes three network requests. None of them carry your data, and every one
  can be avoided: the update check on launch, which you can switch off in Settings
  under About; job-URL autofill, only when you paste a link; and the exchange-rate
  refresh, only when you ask for it.
