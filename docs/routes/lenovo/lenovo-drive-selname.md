# 联想 - 驱动

## Coverage
`index-only`

## Route
- Namespace: `lenovo`
- Namespace Name: `联想`
- Route Path: `/lenovo/drive/:selName`
- Route Name: `驱动`
- Example: `/lenovo/drive/PF3WRD2G`
- URL: `lenovo.com.cn`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `cscnk52`
- Source Location: `drive.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `selName`: 产品序列号


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
  - `lenovo.com.cn`
- `target`: `/drive/:selName`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/lenovo/drive/PF3WRD2G",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "drive.tsx",
  "maintainers": [
    "cscnk52"
  ],
  "name": "驱动",
  "parameters": {
    "selName": "产品序列号"
  },
  "path": "/drive/:selName",
  "radar": [
    {
      "source": [
        "lenovo.com.cn"
      ],
      "target": "/drive/:selName"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Lenovo Legion Y9000X IAH7(2022款) 驱动 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149976636465854464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Lenovo Legion Y9000X IAH7(2022款) 驱动",
      "type": "feed",
      "url": "rsshub://lenovo/drive/PF3WRD2G"
    }
  ]
}
```
