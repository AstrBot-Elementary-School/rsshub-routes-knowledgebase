# SegmentFault - 频道

## Coverage
`index-only`

## Route
- Namespace: `segmentfault`
- Namespace Name: `SegmentFault`
- Route Path: `/segmentfault/channel/:name`
- Route Name: `频道`
- Example: `/segmentfault/channel/frontend`
- URL: `segmentfault.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `LogicJake, Fatpandac`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 频道名称，在频道 URL 可以找到


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
  - `segmentfault.com/channel/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/segmentfault/channel/frontend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "channel.ts",
  "maintainers": [
    "LogicJake",
    "Fatpandac"
  ],
  "name": "频道",
  "parameters": {
    "name": "频道名称，在频道 URL 可以找到"
  },
  "path": "/channel/:name",
  "radar": [
    {
      "source": [
        "segmentfault.com/channel/:name"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-07-09T12:41:51.095Z",
      "errorMessage": "[GET] \"https://segmentfault.com/gateway/articles?query=channel&slug=backend&offset=0&size=20&mode=scrollLoad\": 403 Forbidden\n",
      "id": "165721162973752332",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://segmentfault/channel/backend"
    }
  ]
}
```
