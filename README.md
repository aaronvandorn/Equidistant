# Equidistant

Pick a year (today's month and day in that year) or an exact date. Equidistant finds the mirror date: the day that sits exactly as many days before your pick as today sits after it.

For both the picked date and the mirror date, it reads English Wikipedia live and shows:

- **No. 1 song** — Billboard Hot 100 chart week in effect (from 1958)
- **No. 1 film** — U.S. weekend box office (lists start around the late 1970s)
- **Top TV show** — highest-rated U.S. network program of that season (from 1950–51)
- **Events** — Wikipedia's "On this day" feed plus the year article, with nearby dates when that exact day is quiet
- **Born that day**

Single file (`index.html`), no build step. Serve it with GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). A shareable link is `?date=YYYY-MM-DD` or `?year=YYYY`.
