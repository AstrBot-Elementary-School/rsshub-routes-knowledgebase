# Japan Foodservice Association - 外食産業市場動向調査（月次）

## Coverage
`index-only`

## Route
- Namespace: `jfnet`
- Namespace Name: `Japan Foodservice Association`
- Route Path: `/jfnet/industry-report`
- Route Name: `外食産業市場動向調査（月次）`
- Example: `/jfnet/industry-report`
- URL: `www.jfnet.or.jp`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `industry-report.ts`
- Source Module: `_None_`

## Description
Monthly releases of the 外食産業市場動向調査 from [業界データ](https://www.jfnet.or.jp/industry_report/). One item per survey month linking the PDF and Excel files; `_extra` carries `month` (YYYY-MM), `pdf`, `xls` and `released_at` (the file's upload date from the site's WordPress media API). The segment figures (売上高・客数・客単価 前年同月比) are only published inside the files and are not extracted: the site's 利用規約 reserves reproduction of its 資料 to prior permission.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.jfnet.or.jp/industry_report`
- `target`: `/industry-report`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Monthly releases of the 外食産業市場動向調査 from [業界データ](https://www.jfnet.or.jp/industry_report/). One item per survey month linking the PDF and Excel files; `_extra` carries `month` (YYYY-MM), `pdf`, `xls` and `released_at` (the file's upload date from the site's WordPress media API). The segment figures (売上高・客数・客単価 前年同月比) are only published inside the files and are not extracted: the site's 利用規約 reserves reproduction of its 資料 to prior permission.",
  "example": "/jfnet/industry-report",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "industry-report.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "外食産業市場動向調査（月次）",
  "parameters": {},
  "path": "/industry-report",
  "radar": [
    {
      "source": [
        "www.jfnet.or.jp/industry_report"
      ],
      "target": "/industry-report"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.jfnet.or.jp"
}
```
