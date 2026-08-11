# Meteor - 看板

## Coverage
`index-only`

## Route
- Namespace: `meteor`
- Namespace Name: `Meteor`
- Route Path: `/meteor/:board?`
- Route Name: `看板`
- Example: `/meteor/all`
- URL: `meteor.today`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `board`: 看板 ID 或簡稱，可在 URL 或下方路由找到，預設為 `all`


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
    "bbs"
  ],
  "example": "/meteor/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 38,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "看板",
  "parameters": {
    "board": "看板 ID 或簡稱，可在 URL 或下方路由找到，預設為 `all`"
  },
  "path": "/:board?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "全部看板 | Meteor 學生社群 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "156722143970531328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://meteor.today/board/all/new",
      "title": "全部看板 | Meteor 學生社群",
      "type": "feed",
      "url": "rsshub://meteor"
    },
    {
      "description": "全部看板 | Meteor 學生社群 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81180270991733760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://meteor.today/board/all/new",
      "title": "全部看板 | Meteor 學生社群",
      "type": "feed",
      "url": "rsshub://meteor/all"
    }
  ]
}
```
