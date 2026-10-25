# ArenaPulse — Live Sports Landing Page

Modern sports landing page with **real-time live scores** powered by ESPN's public API.

## Features
- Live scores from ESPN (NBA, EPL, NFL, NHL)
- Bangladesh Time (Asia/Dhaka) for all match times
- Auto-refresh every 60 seconds
- Filter by sport
- Today's schedule view
- Fully responsive
- No API key required

## Tech
- HTML + Tailwind CSS (CDN)
- ESPN Public Scoreboard API (`site.api.espn.com`)
- Vanilla JavaScript

## Live Preview
Enable GitHub Pages or open `index.html` locally.

## APIs Used
| Sport | Endpoint |
|-------|----------|
| NBA | `/sports/basketball/nba/scoreboard` |
| EPL | `/sports/soccer/eng.1/scoreboard` |
| NFL | `/sports/football/nfl/scoreboard` |
| NHL | `/sports/hockey/nhl/scoreboard` |

Data source: ESPN public API (unofficial). Not affiliated with ESPN.

---
Created as a sample project for msh007.