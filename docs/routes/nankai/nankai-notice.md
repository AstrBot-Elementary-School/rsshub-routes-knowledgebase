# 南开大学 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/notice`
- Route Name: `通知公告`
- Example: `/nankai/notice`
- URL: `yzb.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `vicguo0724`
- Source Location: `notice.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.nankai.edu.cn`
  - `www.nankai.edu.cn/157/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nankai/notice",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "notice.ts",
  "maintainers": [
    "vicguo0724"
  ],
  "name": "通知公告",
  "parameters": {},
  "path": "/notice",
  "radar": [
    {
      "source": [
        "www.nankai.edu.cn",
        "www.nankai.edu.cn/157/list.htm"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "南开大学通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168828048058138624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nankai.edu.cn/157/list.htm",
      "title": "南开大学通知公告",
      "type": "feed",
      "url": "rsshub://nankai/notice"
    }
  ]
}
```
