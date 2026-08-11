# Seisin

> Every application in one place. Watch the patterns surface.

Seisin keeps your whole job search in one place, every application, interview and
offer, and turns it into analytics automatically. Instead of a spreadsheet that
records the search without ever explaining it, Seisin reads the patterns back to
you: your pace, your pipeline, and which sources are actually getting you replies.
No account, no sign-in, and it is free.

**This repository hosts the public downloads, changelog, and issue tracker.**
The application is proprietary; the source code is not published here.

## What's new in v1.1.0

- A resume builder: five templates, import from PDF or Word, and offline analysis
- Interview suite revamp: a searchable question bank and a STAR answer builder
- Offer comparison: record what you were actually offered, kept separate from the
  advertised range, compared side by side
- One calendar for every interview and offer deadline, exportable as `.ics` or
  linked straight to Google or Outlook

See [CHANGELOG.md](CHANGELOG.md) for the full history.

---

## Download

**[Download Seisin for Windows](https://github.com/abdulsheibani/seisin/releases/latest/download/Seisin-Setup.exe)**

Or browse all versions on the [Releases page](https://github.com/abdulsheibani/seisin/releases).

1. Download `Seisin-Setup.exe` from the latest release
2. Run the installer
3. Choose whether to create a Desktop shortcut and/or Start Menu entry
4. Launch Seisin from your desktop or Start Menu

> **Note:** Windows may show a SmartScreen warning on first launch. Click **More info -> Run anyway**.
> This is expected for apps without a paid code signing certificate.

A packaged macOS build is not published yet. It is planned for a future release.

---

## Features

- **Application Tracking**: every application, interview, offer and resume in one
  place, with a full status pipeline from Planned -> Applied -> Assessment ->
  Interview -> Offer -> Rejected
- **Planned Pipeline**: track roles before you apply, watch their closing dates,
  and log an application as applied in one click
- **Analytics**: weekly pace, pipeline health, a conversion funnel, response time,
  and response rate by source split by outcome, each with a plain-English
  explanation
- **Resume Builder**: five templates, import from PDF or Word, offline rule-based
  analysis, and export to PDF or Word
- **Interview Suite**: rounds, contacts, research notes, prep checklists, a
  searchable question bank, and a STAR answer builder
- **Calendar**: every interview and offer deadline on one grid, exportable as
  `.ics` or linked straight to Google or Outlook
- **Offer Comparison**: record what you were actually offered, kept separate from
  the advertised range, and compare offers side by side
- **World Map**: choropleth map of where you are applying, with click-to-zoom
- **Import / Export**: import from CSV or Excel with automatic column mapping;
  export to CSV, Excel, or a full JSON backup

---

## Free and paid

Seisin is free and stays free. A paid tier will come later so the project can sustain
itself, but the rule is that every feature has a usable free version and paying buys
depth rather than access. The tracker, your full history, and the analytics you see
today do not move behind a paywall.

## Data and the network

Your data is a SQLite database on your own machine, with no account and no sign-in, and
there is no telemetry. An optional account with cloud sync is planned for a future
version; it will stay optional, local-only will remain supported, and nothing is
uploaded unless you choose it.

Seisin makes three network requests, none of which carry anything about you. A version
check against the GitHub releases API runs on launch and can be turned off in Settings.
The other two fire only when you click them: pasting a job URL fetches that public page
to read the role and company, and the Offers screen can pull the European Central Bank's
daily exchange rates. See the [Privacy page](https://getseisin.com/privacy.html) for
details.

---

## Support

Found a bug or have a feature request? [Open an issue](https://github.com/abdulsheibani/seisin/issues)
or email [support@getseisin.com](mailto:support@getseisin.com).

---

## License

Proprietary. Copyright (c) 2026 Abdelrahman Sheibani. All rights reserved.
See [LICENSE](LICENSE) for the full terms. The Seisin source code is not open source.

---

## Author

Abdelrahman Sheibani ([GitHub](https://github.com/abdulsheibani))
