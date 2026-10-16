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
  - `www.espn.com/nba`
  - `www.espn.com/nba/*path`
- `target`: `/news/nba`
### Rule 2
- `source`:
  - `www.espn.com/wnba`
  - `www.espn.com/wnba/*path`
- `target`: `/news/wnba`
### Rule 3
- `source`:
  - `www.espn.com/nfl`
  - `www.espn.com/nfl/*path`
- `target`: `/news/nfl`
### Rule 4
- `source`:
  - `www.espn.com/mlb`
  - `www.espn.com/mlb/*path`
- `target`: `/news/mlb`
### Rule 5
- `source`:
  - `www.espn.com/nhl`
  - `www.espn.com/nhl/*path`
- `target`: `/news/nhl`
### Rule 6
- `source`:
  - `www.espn.com/mens-college-basketball`
  - `www.espn.com/mens-college-basketball/*path`
- `target`: `/news/ncb`
### Rule 7
- `source`:
  - `www.espn.com/college-football`
  - `www.espn.com/college-football/*path`
- `target`: `/news/ncf`
### Rule 8
- `source`:
  - `www.espn.com/rugby`
  - `www.espn.com/rugby/*path`
- `target`: `/news/rugby`
### Rule 9
- `source`:
  - `www.espn.com/tennis`
  - `www.espn.com/tennis/*path`
- `target`: `/news/tennis`
### Rule 10
- `source`:
  - `www.espn.com/golf`
  - `www.espn.com/golf/*path`
- `target`: `/news/golf`
### Rule 11
- `source`:
  - `www.espn.com/cricket`
  - `www.espn.com/cricket/*path`
- `target`: `/news/cricket`
### Rule 12
- `source`:
  - `www.espn.com/soccer`
  - `www.espn.com/soccer/*path`
- `target`: `/news/soccer`
### Rule 13
- `source`:
  - `www.espn.com/f1`
  - `www.espn.com/f1/*path`
- `target`: `/news/f1`
### Rule 14
- `source`:
  - `www.espn.com/mma`
  - `www.espn.com/mma/*path`
- `target`: `/news/mma`
### Rule 15
- `source`:
  - `www.espn.com/ufl`
  - `www.espn.com/ufl/*path`
- `target`: `/news/ufl`
### Rule 16
- `source`:
  - `www.espn.com/sports-betting`
  - `www.espn.com/sports-betting/*path`
- `target`: `/news/poker`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Get the news feed of the sport you love on ESPN.\n\n| Sport                 | sport | Sport      | sport   |\n| --------------------- | ----- | ---------- | ------- |\n| 🏀 NBA                | nba   | 🎾 Tennis  | tennis  |\n| 🏀 WNBA               | wnba  | ⛳️ Golf    | golf    |\n| 🏈 NFL                | nfl   | 🏏 Cricket | cricket |\n| ⚾️ MLB                | mlb   | ⚽️ Soccer  | soccer  |\n| 🏒 NHL                | nhl   | 🏎️ F1      | f1      |\n| ⛹️ College Basketball | ncb   | 🥊 MMA     | mma     |\n| 🏟️️ College Football   | ncf   | 🏈 UFL     | ufl     |\n| 🏉 Rugby              | rugby | 🃏 Poker   | poker   |",
  "example": "/espn/news/nba",
  "heat": 80,
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
        "www.espn.com/nba",
        "www.espn.com/nba/*path"
      ],
      "target": "/news/nba"
    },
    {
      "source": [
        "www.espn.com/wnba",
        "www.espn.com/wnba/*path"
      ],
      "target": "/news/wnba"
    },
    {
      "source": [
        "www.espn.com/nfl",
        "www.espn.com/nfl/*path"
      ],
      "target": "/news/nfl"
    },
    {
      "source": [
        "www.espn.com/mlb",
        "www.espn.com/mlb/*path"
      ],
      "target": "/news/mlb"
    },
    {
      "source": [
        "www.espn.com/nhl",
        "www.espn.com/nhl/*path"
      ],
      "target": "/news/nhl"
    },
    {
      "source": [
        "www.espn.com/mens-college-basketball",
        "www.espn.com/mens-college-basketball/*path"
      ],
      "target": "/news/ncb"
    },
    {
      "source": [
        "www.espn.com/college-football",
        "www.espn.com/college-football/*path"
      ],
      "target": "/news/ncf"
    },
    {
      "source": [
        "www.espn.com/rugby",
        "www.espn.com/rugby/*path"
      ],
      "target": "/news/rugby"
    },
    {
      "source": [
        "www.espn.com/tennis",
        "www.espn.com/tennis/*path"
      ],
      "target": "/news/tennis"
    },
    {
      "source": [
        "www.espn.com/golf",
        "www.espn.com/golf/*path"
      ],
      "target": "/news/golf"
    },
    {
      "source": [
        "www.espn.com/cricket",
        "www.espn.com/cricket/*path"
      ],
      "target": "/news/cricket"
    },
    {
      "source": [
        "www.espn.com/soccer",
        "www.espn.com/soccer/*path"
      ],
      "target": "/news/soccer"
    },
    {
      "source": [
        "www.espn.com/f1",
        "www.espn.com/f1/*path"
      ],
      "target": "/news/f1"
    },
    {
      "source": [
        "www.espn.com/mma",
        "www.espn.com/mma/*path"
      ],
      "target": "/news/mma"
    },
    {
      "source": [
        "www.espn.com/ufl",
        "www.espn.com/ufl/*path"
      ],
      "target": "/news/ufl"
    },
    {
      "source": [
        "www.espn.com/sports-betting",
        "www.espn.com/sports-betting/*path"
      ],
      "target": "/news/poker"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ESPN NBA News - Powered by RSSHub",
      "errorAt": "2026-09-07T13:36:18.003Z",
      "errorMessage": "[GET] \"https://onefeed.fan.api.espn.com/apis/v3/cached/contentEngine/oneFeed/leagues/nba?offset=0\": 403 Forbidden\n",
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
      "errorAt": "2026-09-26T09:35:45.769Z",
      "errorMessage": "[GET] \"https://onefeed.fan.api.espn.com/apis/v3/cached/contentEngine/oneFeed/leagues/soccer?offset=0\": 403 Forbidden\n",
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
