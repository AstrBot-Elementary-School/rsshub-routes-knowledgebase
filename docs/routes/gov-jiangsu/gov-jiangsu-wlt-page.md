# 江苏省人民政府 - 文旅局审批公告

## Coverage
`index-only`

## Route
- Namespace: `gov/jiangsu`
- Namespace Name: `江苏省人民政府`
- Route Path: `/gov/jiangsu/wlt/:page?`
- Route Name: `文旅局审批公告`
- Example: `/gov/jiangsu/wlt`
- URL: `wlt.jiangsu.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `GideonSenku`
- Source Location: `wlt/index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `page`: 旧页数参数，仅支持第 1 页；可省略


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
  - `wlt.jiangsu.gov.cn/`
- `target`: `/wlt`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/jiangsu/wlt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "wlt/index.tsx",
  "maintainers": [
    "GideonSenku"
  ],
  "name": "文旅局审批公告",
  "parameters": {
    "page": "旧页数参数，仅支持第 1 页；可省略"
  },
  "path": "/wlt/:page?",
  "radar": [
    {
      "source": [
        "wlt.jiangsu.gov.cn/"
      ],
      "target": "/wlt"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "wlt.jiangsu.gov.cn/"
}
```
