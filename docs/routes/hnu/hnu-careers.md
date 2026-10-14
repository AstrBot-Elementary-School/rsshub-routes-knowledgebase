# 湖南大学 - 校园招聘

## Coverage
`index-only`

## Route
- Namespace: `hnu`
- Namespace Name: `湖南大学`
- Route Path: `/hnu/careers`
- Route Name: `校园招聘`
- Example: `/hnu/careers`
- URL: `scc.hnu.edu.cn/module/careers`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ningyougan`
- Source Location: `careers.ts`
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
  - `scc.hnu.edu.cn/module/careers`
  - `scc.hnu.edu.cn/`
- `target`: `/careers`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/hnu/careers",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "careers.ts",
  "maintainers": [
    "ningyougan"
  ],
  "name": "校园招聘",
  "parameters": {},
  "path": "/careers",
  "radar": [
    {
      "source": [
        "scc.hnu.edu.cn/module/careers",
        "scc.hnu.edu.cn/"
      ],
      "target": "/careers"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "校园招聘 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74406514359214080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://scc.hnu.edu.cn/module/getcareers",
      "title": "校园招聘",
      "type": "feed",
      "url": "rsshub://hnu/careers"
    }
  ],
  "url": "scc.hnu.edu.cn/module/careers"
}
```
