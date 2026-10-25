# ArenaPulse — Live Sports Landing Page

Modern sports landing page with **real-time live scores** powered by ESPN's public API.

## Features
- Live scores from ESPN (no API key needed)
- Leagues: **NBA, EPL, Champions League, La Liga, NFL, NHL, MLB**
- All match times in **Bangladesh Time** (Asia/Dhaka, UTC+6)
- Auto-refresh every 60 seconds
- Filter by sport / league
- Today's schedule view
- Fully responsive design

## Tech
- HTML + Tailwind CSS (CDN)
- ESPN Public Scoreboard API (`site.api.espn.com`)
- Vanilla JavaScript

## Covered Endpoints
| League | Path |
|--------|------|
| NBA | `/sports/basketball/nba/scoreboard` |
| Premier League | `/sports/soccer/eng.1/scoreboard` |
| Champions League | `/sports/soccer/uefa.champions/scoreboard` |
| La Liga | `/sports/soccer/esp.1/scoreboard` |
| NFL | `/sports/football/nfl/scoreboard` |
| NHL | `/sports/hockey/nhl/scoreboard` |
| MLB | `/sports/baseball/mlb/scoreboard` |

## How to view
1. Enable **GitHub Pages** (Settings → Pages → Deploy from `main`)
2. Or open `index.html` locally in a browser

---
Data source: ESPN public API (unofficial). Not affiliated with ESPN.  
Sample project for [msh007](https://github.com/msh007).