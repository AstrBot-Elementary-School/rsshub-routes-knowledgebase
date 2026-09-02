# ESPN - News

## Coverage
`index-only`

## Route
- Namespace: `espn`
- Namespace Name: `ESPN`
- Route Path: `/espn/news/:sport`
- Route Name: `News`
- Example: `/espn/news/nba`
- URL: `espn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `weijianduan0302`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
Get the news feed of the sport you love on ESPN.

| Sport                 | sport | Sport      | sport   |
| --------------------- | ----- | ---------- | ------- |
| 🏀 NBA                | nba   | 🎾 Tennis  | tennis  |
| 🏀 WNBA               | wnba  | ⛳️ Golf    | golf    |
| 🏈 NFL                | nfl   | 🏏 Cricket | cricket |
| ⚾️ MLB                | mlb   | ⚽️ Soccer  | soccer  |
| 🏒 NHL                | nhl   | 🏎️ F1      | f1      |
| ⛹️ College Basketball | ncb   | 🥊 MMA     | mma     |
| 🏟️️ College Football   | ncf   | 🏈 UFL     | ufl     |
| 🏉 Rugby              | rugby | 🃏 Poker   | poker   |

## Parameters
- `sport`: sport category, can be nba, nfl, mlb, nhl etc.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `espn.com/:sport*`
- `target`: `/news/:sport`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Get the news feed of the sport you love on ESPN.\n\n| Sport                 | sport | Sport      | sport   |\n| --------------------- | ----- | ---------- | ------- |\n| 🏀 NBA                | nba   | 🎾 Tennis  | tennis  |\n| 🏀 WNBA               | wnba  | ⛳️ Golf    | golf    |\n| 🏈 NFL                | nfl   | 🏏 Cricket | cricket |\n| ⚾️ MLB                | mlb   | ⚽️ Soccer  | soccer  |\n| 🏒 NHL                | nhl   | 🏎️ F1      | f1      |\n| ⛹️ College Basketball | ncb   | 🥊 MMA     | mma     |\n| 🏟️️ College Football   | ncf   | 🏈 UFL     | ufl     |\n| 🏉 Rugby              | rugby | 🃏 Poker   | poker   |",
  "example": "/espn/news/nba",
  "heat": 81,
  "location": "news.tsx",
  "maintainers": [
    "weijianduan0302"
  ],
  "name": "News",
  "parameters": {
    "sport": "sport category, can be nba, nfl, mlb, nhl etc."
  },
  "path": "/news/:sport",
  "radar": [
    {
      "source": [
        "espn.com/:sport*"
      ],
      "target": "/news/:sport"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ESPN NBA News - Powered by RSSHub",
      "errorAt": "2026-08-31T23:08:17.769Z",
      "errorMessage": "Invalid RSSHub JSON Feed from 98292582055262208\nCannot read properties of undefined (reading '0')\n",
      "id": "60547975805774848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.espn.com/espn/rss/nba/news",
      "title": "ESPN NBA News",
      "type": "feed",
      "url": "rsshub://espn/news/nba"
    },
    {
      "description": "ESPN SOCCER News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72477890360150016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.espn.com/espn/rss/soccer/news",
      "title": "ESPN SOCCER News",
      "type": "feed",
      "url": "rsshub://espn/news/soccer"
    }
  ]
}
```
