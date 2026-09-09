# Seisin

> Every application in one place. Watch the patterns surface.

Seisin keeps your whole job search in one place, every application, interview and
offer, and turns it into analytics automatically. Instead of a spreadsheet that
records the search without ever explaining it, Seisin reads the patterns back to
you: your pace, your pipeline, and which sources are actually getting you replies.
It runs on Windows, macOS, and Linux. No account, no sign-in, and it is free.

**This repository hosts the public downloads, changelog, and issue tracker.**
The application is proprietary; the source code is not published here.

## What's new in 1.2.0

- **Seisin now runs on macOS and Linux**, alongside Windows
- **Weekly goals**: set your own targets for the week and tick them off from the
  top bar
- **A report when you land a role**: accepting an offer opens a summary of the
  whole search, your strongest source and resume, and how long it took
- **A cleaner Withdrawn flow**: abandoned applications get their own status and
  stay out of your active pipeline
- **Per-application currency**, an original-currency view on the offer comparison,
  and one-click editing on the Applications table
- Faster startup and navigation, ranked search across the app, and a visual pass
  throughout

See [CHANGELOG.md](CHANGELOG.md) for the full history.

---

## Download

| Platform | Download |
|---|---|
| Windows | [Seisin-Setup.exe](https://github.com/abdulsheibani/seisin/releases/latest/download/Seisin-Setup.exe) |
| macOS (Apple Silicon) | [Seisin-Setup.dmg](https://github.com/abdulsheibani/seisin/releases/latest/download/Seisin-Setup.dmg) |
| Linux | [Seisin-Setup.deb](https://github.com/abdulsheibani/seisin/releases/latest/download/Seisin-Setup.deb) or [Seisin-Setup.AppImage](https://github.com/abdulsheibani/seisin/releases/latest/download/Seisin-Setup.AppImage) |

Or browse all versions on the [Releases page](https://github.com/abdulsheibani/seisin/releases).
None of the builds are code-signed yet, so each platform shows a first-run warning:

- **Windows**: run `Seisin-Setup.exe`; if SmartScreen warns, click **More info -> Run anyway**.
- **macOS**: Apple Silicon only. Open the `.dmg`, drag Seisin to Applications, then right-click the app and choose **Open** the first time. If **Open** is not offered, use **System Settings -> Privacy & Security -> Open Anyway**.
- **Linux**: install the `.deb` like any package (or `sudo dpkg -i Seisin-Setup.deb`), or `chmod +x Seisin-Setup.AppImage` and run it. If the AppImage will not start, your distribution is missing `libfuse2` - run `./Seisin-Setup.AppImage --appimage-extract-and-run` instead.

---

## Features

- **Application tracking**: company, role, status, location, salary range and
  currency, salary period, work type, employment type, relocation, source and
  notes, with a Planned -> Applied -> Assessment -> Interview -> Offer -> Rejected
  pipeline plus a Withdrawn status
- **Planned pipeline**: track roles before you apply, watch their closing dates,
  and log an application as applied in one click
- **Analytics**: weekly pace, pipeline health, a conversion funnel, response time,
  and response rate by source split by outcome, each with a plain-English
  explanation
- **Weekly goals**: set your own targets for the week and tick them off from the
  top bar
- **Job search report**: accepting an offer opens a summary of the whole search,
  your strongest source and resume, and how long it took
- **Resume builder**: five templates with full control over fonts, spacing,
  colour, accent and section order; import from PDF or Word; offline analysis;
  export to PDF or Word; and a link from each CV to the applications it was sent with
- **Interview suite**: rounds, contacts, research notes, prep checklists, a
  searchable question bank, and a STAR answer builder
- **Calendar**: every interview and offer deadline on one grid, exportable as
  `.ics` or linked straight to Google or Outlook
- **Offer comparison**: record what you were actually offered, kept separate from
  the advertised range, each offer shown in your converted view or its own currency
- **World map**: choropleth of where you are applying, with click-to-zoom
- **Search**: ranked, fuzzy matching across applications, interviews, and the
  question bank
- **Import / export**: import from CSV or Excel with automatic column mapping;
  export to CSV, Excel, or a full JSON backup
- **Sounds, themes, privacy mode**: subtle audio and celebrations (all toggleable);
  light, dark and midnight themes with a custom accent; and a privacy mode that
  blurs salary figures and names for screen sharing

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
