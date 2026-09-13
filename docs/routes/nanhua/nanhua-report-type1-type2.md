# 南华期货 - 研报

## Coverage
`index-only`

## Route
- Namespace: `nanhua`
- Namespace Name: `南华期货`
- Route Path: `/nanhua/report/:type1/:type2`
- Route Name: `研报`
- Example: `/nanhua/report/WEEK/WEEK_black`
- URL: `mall.nanhua.net/mall/r/w/reportNew/report-list.html`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `report.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type1`: 一级分类代码，如 `WEEK`（周度报告）、`SEASON`（季年报告）、`HOT`（热点报告）等，需要使用 `encodeURIComponent` 编码
- `type2`: 二级分类代码，如 `WEEK_black`（黑色）、`WEEK_enchem`（能化）等，需要使用 `encodeURIComponent` 编码


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mall.nanhua.net/mall/r/w/reportNew/report-list.html`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/nanhua/report/WEEK/WEEK_black",
  "heat": 1,
  "location": "report.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "研报",
  "parameters": {
    "type1": "一级分类代码，如 `WEEK`（周度报告）、`SEASON`（季年报告）、`HOT`（热点报告）等，需要使用 `encodeURIComponent` 编码",
    "type2": "二级分类代码，如 `WEEK_black`（黑色）、`WEEK_enchem`（能化）等，需要使用 `encodeURIComponent` 编码"
  },
  "path": "/report/:type1/:type2",
  "radar": [
    {
      "source": [
        "mall.nanhua.net/mall/r/w/reportNew/report-list.html"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "南华期货 - 周度报告 - 黑色 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "266144713677243392",
      "image": "https://mall.nanhua.net/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://mall.nanhua.net/mall/r/w/reportNew/report-list.html?type1=WEEK&type2=WEEK_black",
      "title": "南华期货 - 周度报告 - 黑色",
      "type": "feed",
      "url": "rsshub://nanhua/report/WEEK/WEEK_black"
    }
  ],
  "url": "mall.nanhua.net/mall/r/w/reportNew/report-list.html"
}
```
