# Twitch - Stream Schedule

## Coverage
`index-only`

## Route
- Namespace: `twitch`
- Namespace Name: `Twitch`
- Route Path: `/twitch/schedule/:login`
- Route Name: `Stream Schedule`
- Example: `/twitch/schedule/riotgames`
- URL: `www.twitch.tv`
- Language: `_None_`
- Categories: `live`
- Maintainers: `hoilc`
- Source Location: `schedule.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `login`: Twitch username


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
  - `www.twitch.tv/:login/schedule`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/twitch/schedule/riotgames",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "schedule.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "Stream Schedule",
  "parameters": {
    "login": "Twitch username"
  },
  "path": "/schedule/:login",
  "radar": [
    {
      "source": [
        "www.twitch.tv/:login/schedule"
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
