# 深圳证券交易所 - 上市公司公告

## Coverage
`index-only`

## Route
- Namespace: `szse`
- Namespace Name: `深圳证券交易所`
- Route Path: `/szse/disclosure/listed/notice/:query?`
- Route Name: `上市公司公告`
- Example: `/szse/disclosure/listed/notice`
- URL: `www.szse.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `disclosure/listed-notice.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `query`: Filter options. can filte by "stock","beginDate","endDate". example:"stock=000001&beginDate=2025-07-01&endDate=2025-08-30"


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
  - `www.szse.cn/disclosure/listed/notice/index.html`
- `target`: `/disclosure/listed/notice`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/szse/disclosure/listed/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 51,
  "location": "disclosure/listed-notice.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "上市公司公告",
  "parameters": {
    "query": "Filter options. can filte by \"stock\",\"beginDate\",\"endDate\". example:\"stock=000001&beginDate=2025-07-01&endDate=2025-08-30\""
  },
  "path": "/disclosure/listed/notice/:query?",
  "radar": [
    {
      "source": [
        "www.szse.cn/disclosure/listed/notice/index.html"
      ],
      "target": "/disclosure/listed/notice"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "深交所官网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "115195943416981504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.szse.cn/disclosure/listed/notice",
      "title": "深圳证券交易所 - 上市公司公告",
      "type": "feed",
      "url": "rsshub://szse/disclosure/listed/notice"
    },
    {
      "description": "深交所官网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "243896126078777344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.szse.cn/disclosure/listed/notice",
      "title": "深圳证券交易所 - 上市公司公告",
      "type": "feed",
      "url": "rsshub://szse/disclosure/listed/notice/stock=301081"
    }
  ],
  "url": "www.szse.cn",
  "view": 0
}
```
