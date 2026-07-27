# 品玩 - 实时要闻

## Coverage
`index-only`

## Route
- Namespace: `pingwest`
- Namespace Name: `品玩`
- Route Path: `/pingwest/status`
- Route Name: `实时要闻`
- Example: `/pingwest/status`
- URL: `pingwest.com/status`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `sanmmm`
- Source Location: `status.ts`
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
  - `pingwest.com/status`
  - `pingwest.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/pingwest/status",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 551,
  "location": "status.ts",
  "maintainers": [
    "sanmmm"
  ],
  "name": "实时要闻",
  "parameters": {},
  "path": "/status",
  "radar": [
    {
      "source": [
        "pingwest.com/status",
        "pingwest.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "品玩 - 实时要闻 - Powered by RSSHub",
      "errorAt": "2026-05-25T06:27:49.864Z",
      "errorMessage": "[GET] \"https://www.pingwest.com/api/state/list?page=1\": 405 Not Allowed\nAuthentication failed. Access denied.\n/pingwest/status\n[GET] \"https://www.pingwest.com/api/state/list?page=1\": 405 Not Allowed\n502 \n[GET] \"https://www.pingwest.com/api/state/list?page=1\": 405 Not Allowed\n[GET] \"https://www.pingwest.com/api/state/list?page=1\": 405 Not Allowed\n[GET] \"https://www.pingwest.com/api/state/list?page=1\": 405 Not Allowed\n",
      "id": "41390414693046277",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pingwest.com/status",
      "title": "品玩 - 实时要闻",
      "type": "feed",
      "url": "rsshub://pingwest/status"
    }
  ],
  "url": "pingwest.com/status"
}
```
