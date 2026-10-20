# 国家税务总局 - 最新文件

## Coverage
`index-only`

## Route
- Namespace: `gov/chinatax`
- Namespace Name: `国家税务总局`
- Route Path: `/gov/chinatax/latest`
- Route Name: `最新文件`
- Example: `/gov/chinatax/latest`
- URL: `fgk.chinatax.gov.cn/zcfgk/c100027/list.html`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk, fuzy112`
- Source Location: `latest.ts`
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
  - `fgk.chinatax.gov.cn/zcfgk/c100027/list.html`
- `target`: `/latest`
### Rule 2
- `source`:
  - `www.chinatax.gov.cn/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/chinatax/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1176,
  "location": "latest.ts",
  "maintainers": [
    "nczitzk",
    "fuzy112"
  ],
  "name": "最新文件",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "fgk.chinatax.gov.cn/zcfgk/c100027/list.html"
      ],
      "target": "/latest"
    },
    {
      "source": [
        "www.chinatax.gov.cn/*"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "国家税务总局 - 最新文件 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62722084868717571",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fgk.chinatax.gov.cn/zcfgk/c100027/list.html",
      "title": "国家税务总局 - 最新文件",
      "type": "feed",
      "url": "rsshub://gov/chinatax/latest"
    }
  ],
  "url": "fgk.chinatax.gov.cn/zcfgk/c100027/list.html"
}
```
