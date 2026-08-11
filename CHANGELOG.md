# Changelog

All notable changes to Seisin are documented here. This project follows
[Semantic Versioning](https://semver.org/).

## v1.1.0 - TBD

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

## v1.0.0 - 2026-07-16

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
