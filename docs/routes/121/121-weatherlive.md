# 深圳台风网 - 深圳天气直播

## Coverage
`index-only`

## Route
- Namespace: `121`
- Namespace Name: `深圳台风网`
- Route Path: `/121/weatherLive`
- Route Name: `深圳天气直播`
- Example: `/121/weatherLive`
- URL: `tf.121.com.cn`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `nczitzk`
- Source Location: `weather-live.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tf.121.com.cn`
  - `tf.121.com.cn/web/weatherLive`
- `target`: `/weatherLive`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/121/weatherLive",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "weather-live.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "深圳天气直播",
  "path": "/weatherLive",
  "radar": [
    {
      "source": [
        "tf.121.com.cn",
        "tf.121.com.cn/web/weatherLive"
      ],
      "target": "/weatherLive"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "tf.121.com.cn",
  "view": 5
}
```
