# Αγωνιστικό ημερολόγιο – program.heraklion-bridge.gr

The competition calendar of the Heraklion Bridge Club (Όμιλος Μπριτζ Ηρακλείου), as a plain static site (HTML/CSS/JS, no build step) for GitHub Pages at **https://program.heraklion-bridge.gr**.

- `index.html` – the page: **Ατζέντα** (list by month, scrolls to the next event) and **Ημερολόγιο** (month grid, tap a day for its events). Category filters, search, light/dark theme, print, and a `.ics` download for Google / Apple / Outlook calendars. The view and month are in the address (`#agenda`, `#calendar=2026-11`).
- `events.js` – **the only file to edit**: one line per event (`d` date, optional `e` last day, `t` title, `c` category, optional `tag`, `n` note). Instructions are at the top of the file. For next year, replace the list and the title.
- `assets/` – club logo and icons. `CNAME` – custom domain.

Categories (colours in the original document): `omh` = club events (yellow), `qual` = qualifiers of the Panhellenic championships played at the club (green), `student` = Μαθητική, `pan` = Panhellenic events (blue), `other` = other clubs and festivals (red), `holiday` = holidays and ΑΡΓΙΑ.
