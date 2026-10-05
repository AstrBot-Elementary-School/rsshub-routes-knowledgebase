# osu! - Beatmap Packs

## Coverage
`index-only`

## Route
- Namespace: `osu`
- Namespace Name: `osu!`
- Route Path: `/osu/packs/:type?`
- Route Name: `Beatmap Packs`
- Example: `/osu/packs`
- URL: `osu.ppy.sh`
- Language: `_None_`
- Categories: `game`
- Maintainers: `JimenezLi`
- Source Location: `beatmaps/packs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: pack type, default to `standard`, can choose from `featured`, `tournament`, `loved`, `chart`, `theme` and `artist`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/osu/packs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "beatmaps/packs.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "Beatmap Packs",
  "parameters": {
    "type": "pack type, default to `standard`, can choose from `featured`, `tournament`, `loved`, `chart`, `theme` and `artist`"
  },
  "path": "/packs/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:64:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:90:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:109:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "osu! Beatmap Pack - standard - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83063680805214208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://osu.ppy.sh/beatmaps/packs?type=standard",
      "title": "osu! Beatmap Pack - standard",
      "type": "feed",
      "url": "rsshub://osu/packs"
    }
  ]
}
```
