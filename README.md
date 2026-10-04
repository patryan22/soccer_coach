# Sideline Subs

Offline-capable mobile web app for tracking youth soccer playing time (9v9, two halves).

- Roster, lineup setup, goalie tracking, continuous game clock (survives screen lock)
- Tap a field player, then a bench player to sub; bench sorted by least time played
- Sub-reminder banner at a set interval, undo, mark players out
- Late arrivals, injury tracking (with notes), per-game history, season totals
- Share a game summary (text) or export CSV

## Use on iPhone
Host the files on any static host (e.g. GitHub Pages), open the URL in Safari,
then Share > Add to Home Screen. After the first load it works offline.

Local preview: `npx http-server .`
