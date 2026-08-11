# Seisin

> Every application in one place. Watch the patterns surface.

Seisin keeps your whole job search in one place, every application, interview and
offer, and turns it into analytics automatically. Instead of a spreadsheet that
records the search without ever explaining it, Seisin reads the patterns back to
you: your pace, your pipeline, and which sources are actually getting you replies.
No account, no sign-in, and it is free.

**This repository hosts the public downloads, changelog, and issue tracker.**
The application is proprietary; the source code is not published here.

See [CHANGELOG.md](CHANGELOG.md) for what's new in each release.

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

- **Application Tracking**: add, edit, and delete applications with company, role,
  status, location, salary range, work type, relocation, source, and notes
- **Status Pipeline**: track every stage from Planned -> Applied -> Assessment ->
  Interview -> Offer -> Rejected, with planned roles excluded from conversion stats
- **Analytics**: applications over time, weekly pace, pipeline health, a conversion
  funnel, response time, and response rate by source split by whether the reply
  progressed or was a rejection, each with a plain-English explanation tooltip
- **World Map**: choropleth map of where you are applying, with click-to-zoom
- **Offer Comparison**: side-by-side offer cards with relocation-adjusted salary
  and work type
- **Interview Suite**: track rounds, contacts, research notes, and a prep checklist
- **Resume Storage**: keep up to three CVs locally, tag them, and link them to applications
- **Import / Export**: import from CSV or Excel with automatic column mapping;
  export to CSV, Excel, or a full JSON backup
- **Themes & Accent Color**: light, dark, and midnight themes, plus a custom accent
  color applied across the top bar, buttons, and charts
- **Privacy Mode**: blur salary figures and names for screen sharing
- **Update Notifications**: Seisin checks GitHub on launch and tells you when a newer
  version is available; this launch check can be turned off in Settings

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
