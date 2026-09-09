# Changelog

All notable changes to Seisin are documented here. This project follows
[Semantic Versioning](https://semver.org/).

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
