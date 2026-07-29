# 罗戈网 - 报告

## Coverage
`index-only`

## Route
- Namespace: `logclub`
- Namespace Name: `罗戈网`
- Route Path: `/logclub/lc_report/:id?`
- Route Name: `报告`
- Example: `/logclub/lc_report`
- URL: `logclub.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `report.ts`
- Source Module: `_None_`

## Description
| 罗戈研究出品 | 物流报告       | 绿色双碳报告          |
| ------------ | -------------- | --------------------- |
| Report       | IndustryReport | GreenDualCarbonReport |

## Parameters
- `id`: 报告 id，见下表，默认为罗戈研究出品


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
  - `logclub.com/lc_report`
- `target`: `/lc_report`
### Rule 2
- `title`: `报告 - 罗戈研究出品`
- `source`:
  - `logclub.com/lc_report`
- `target`: `/lc_report/Report`
### Rule 3
- `title`: `报告 - 物流报告`
- `source`:
  - `logclub.com/lc_report`
- `target`: `/lc_report/IndustryReport`
### Rule 4
- `title`: `报告 - 绿色双碳报告`
- `source`:
  - `logclub.com/lc_report`
- `target`: `/lc_report/GreenDualCarbonReport`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 罗戈研究出品 | 物流报告       | 绿色双碳报告          |\n| ------------ | -------------- | --------------------- |\n| Report       | IndustryReport | GreenDualCarbonReport |",
  "example": "/logclub/lc_report",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "report.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "报告",
  "parameters": {
    "id": "报告 id，见下表，默认为罗戈研究出品"
  },
  "path": "/lc_report/:id?",
  "radar": [
    {
      "source": [
        "logclub.com/lc_report"
      ],
      "target": "/lc_report"
    },
    {
      "source": [
        "logclub.com/lc_report"
      ],
      "target": "/lc_report/Report",
      "title": "报告 - 罗戈研究出品"
    },
    {
      "source": [
        "logclub.com/lc_report"
      ],
      "target": "/lc_report/IndustryReport",
      "title": "报告 - 物流报告"
    },
    {
      "source": [
        "logclub.com/lc_report"
      ],
      "target": "/lc_report/GreenDualCarbonReport",
      "title": "报告 - 绿色双碳报告"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "罗戈网（www.logclub.com）-物流商业伙伴, - Powered by RSSHub",
      "errorAt": "2025-10-01T05:58:34.062Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slice')\n",
      "id": "122905311734382592",
      "image": "https://www.logclub.com/public/static/front/images/pc_logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.logclub.com/lc_report",
      "title": "【罗戈网】 报告",
      "type": "feed",
      "url": "rsshub://logclub/lc_report"
    }
  ]
}
```
