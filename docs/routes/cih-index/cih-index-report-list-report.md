# 中指研究院 - 报告

## Coverage
`index-only`

## Route
- Namespace: `cih-index`
- Namespace Name: `中指研究院`
- Route Path: `/cih-index/report/list/:report?`
- Route Name: `报告`
- Example: `/cih-index/report/list/p1-oaddtime-ddesc`
- URL: `www.cih-index.com/report/list/p1-oaddtime-ddesc`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `report.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `report`: 报告 id，可在 URL 中找到，留空为 `p1-oaddtime-ddesc`


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
  - `www.cih-index.com/report/list/:report`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/cih-index/report/list/p1-oaddtime-ddesc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 96,
  "location": "report.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "报告",
  "parameters": {
    "report": "报告 id，可在 URL 中找到，留空为 `p1-oaddtime-ddesc`"
  },
  "path": "/report/list/:report?",
  "radar": [
    {
      "source": [
        "www.cih-index.com/report/list/:report"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中指云基于中指研究院多年研究积累，提供最全房地产行业报告，可免费阅读房地产政策解读、市场趋势、房企研究及物业行业分析报告，可下载PDF格式报告，深度洞察房地产行业动向。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150104102533230592",
      "image": "https://www.cih-index.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.cih-index.com/report/list/f2022041315362473358-p1-oaddtime-ddesc",
      "title": "政策解读 - 中指报告",
      "type": "feed",
      "url": "rsshub://cih-index/report/list/f2022041315362473358-p1-oaddtime-ddesc"
    },
    {
      "description": "中指云基于中指研究院多年研究积累，提供最全房地产行业报告，可免费阅读房地产政策解读、市场趋势、房企研究及物业行业分析报告，可下载PDF格式报告，深度洞察房地产行业动向。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149713189464210432",
      "image": "https://www.cih-index.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.cih-index.com/report/list/p1-oaddtime-ddesc",
      "title": "中指报告",
      "type": "feed",
      "url": "rsshub://cih-index/report/list"
    }
  ],
  "url": "www.cih-index.com/report/list/p1-oaddtime-ddesc"
}
```
