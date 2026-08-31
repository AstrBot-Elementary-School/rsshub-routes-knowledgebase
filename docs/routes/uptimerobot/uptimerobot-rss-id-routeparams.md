# Uptime Robot - RSS

## Coverage
`index-only`

## Route
- Namespace: `uptimerobot`
- Namespace Name: `Uptime Robot`
- Route Path: `/uptimerobot/rss/:id/:routeParams?`
- Route Name: `RSS`
- Example: `/uptimerobot/rss/u358785-e4323652448755805d668f1a66506f2f`
- URL: `rss.uptimerobot.com`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `Rongronggg9`
- Source Location: `rss.tsx`
- Source Module: `_None_`

## Description
| Key    | Description                                                              | Accepts        | Defaults to |
| ------ | ------------------------------------------------------------------------ | -------------- | ----------- |
| showID | Show monitor ID (disabling it will also disable link for each RSS entry) | 0/1/true/false | true        |

## Parameters
- `id`: the last part of your RSS URL (e.g. `u358785-e4323652448755805d668f1a66506f2f` for `https://rss.uptimerobot.com/u358785-e4323652448755805d668f1a66506f2f`)
- `routeParams`: extra parameters, see the table below


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
  - `rss.uptimerobot.com/:id`
- `target`: `/rss/:id`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "| Key    | Description                                                              | Accepts        | Defaults to |\n| ------ | ------------------------------------------------------------------------ | -------------- | ----------- |\n| showID | Show monitor ID (disabling it will also disable link for each RSS entry) | 0/1/true/false | true        |",
  "example": "/uptimerobot/rss/u358785-e4323652448755805d668f1a66506f2f",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rss.tsx",
  "maintainers": [
    "Rongronggg9"
  ],
  "name": "RSS",
  "parameters": {
    "id": "the last part of your RSS URL (e.g. `u358785-e4323652448755805d668f1a66506f2f` for `https://rss.uptimerobot.com/u358785-e4323652448755805d668f1a66506f2f`)",
    "routeParams": "extra parameters, see the table below"
  },
  "path": "/rss/:id/:routeParams?",
  "radar": [
    {
      "source": [
        "rss.uptimerobot.com/:id"
      ],
      "target": "/rss/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
