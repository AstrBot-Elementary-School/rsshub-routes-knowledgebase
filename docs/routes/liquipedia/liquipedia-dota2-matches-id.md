# Liquipedia - Dota2 战队最近比赛结果

## Coverage
`index-only`

## Route
- Namespace: `liquipedia`
- Namespace Name: `Liquipedia`
- Route Path: `/liquipedia/dota2/matches/:id`
- Route Name: `Dota2 战队最近比赛结果`
- Example: `/liquipedia/dota2/matches/Team_Aster`
- URL: `liquipedia.net`
- Language: `_None_`
- Categories: `game`
- Maintainers: `wzekin`
- Source Location: `dota2-matches.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 战队名称，可在url中找到。例如:https://liquipedia.net/dota2/Team_Aster


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `liquipedia.net/dota2/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/liquipedia/dota2/matches/Team_Aster",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dota2-matches.ts",
  "maintainers": [
    "wzekin"
  ],
  "name": "Dota2 战队最近比赛结果",
  "parameters": {
    "id": "战队名称，可在url中找到。例如:https://liquipedia.net/dota2/Team_Aster"
  },
  "path": "/dota2/matches/:id",
  "radar": [
    {
      "source": [
        "liquipedia.net/dota2/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
