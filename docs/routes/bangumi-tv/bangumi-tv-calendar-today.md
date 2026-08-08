# Bangumi 番组计划 - 放送列表

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/calendar/today`
- Route Name: `放送列表`
- Example: `/bangumi.tv/calendar/today`
- URL: `bgm.tv/calendar`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `magic-akari`
- Source Location: `calendar/today.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `bgm.tv/calendar`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/calendar/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 281,
  "location": "calendar/today.tsx",
  "maintainers": [
    "magic-akari"
  ],
  "name": "放送列表",
  "parameters": {},
  "path": "/calendar/today",
  "radar": [
    {
      "source": [
        "bgm.tv/calendar"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bangumi 每日放送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72444158362373120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/calendar",
      "title": "bangumi 每日放送",
      "type": "feed",
      "url": "rsshub://bangumi.tv/calendar/today"
    }
  ],
  "url": "bgm.tv/calendar"
}
```
