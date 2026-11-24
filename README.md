# SamarthaJ.github.io

Test site for ShipFarmy AI Navi QA, TC-9 (a trusted site with a partial robots.txt).

- `robots.txt`: `User-agent: *` / `Disallow: /archive/`
- Allowed: `/news/*.html` (5 pages)
- Disallowed: `/archive/*.html` (5 pages on the same topics, plus the archive index)

Each article ends with a test marker (`NEWS-ALLOWED-...` or `ARCHIVE-DISALLOWED-...`) so you can tell which page an answer came from.
