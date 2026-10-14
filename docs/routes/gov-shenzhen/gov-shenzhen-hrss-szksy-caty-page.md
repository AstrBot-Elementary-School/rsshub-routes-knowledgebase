# 深圳市人民政府 - 考试院

## Coverage
`index-only`

## Route
- Namespace: `gov/shenzhen`
- Namespace Name: `深圳市人民政府`
- Route Path: `/gov/shenzhen/hrss/szksy/:caty/:page?`
- Route Name: `考试院`
- Example: `/gov/shenzhen/hrss/szksy/bmxx/2`
- URL: `hrss.sz.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `zlasd`
- Source Location: `hrss/szksy/index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 报名信息 | 成绩信息 | 合格标准 | 合格人员公示 | 证书发放信息 |
| :------: | :------: | :------: | :------: | :----------: | :----------: |
|   tzgg   |   bmxx   |   cjxx   |   hgbz   |    hgrygs    |     zsff     |

## Parameters
- `caty`: 信息类别
- `page`: 历史兼容参数，所有值均返回第 1 页，不翻页


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
  - `hrss.sz.gov.cn/szksy/zwgk/:caty/index.html`
- `target`: `/hrss/szksy/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 | 报名信息 | 成绩信息 | 合格标准 | 合格人员公示 | 证书发放信息 |\n| :------: | :------: | :------: | :------: | :----------: | :----------: |\n|   tzgg   |   bmxx   |   cjxx   |   hgbz   |    hgrygs    |     zsff     |",
  "example": "/gov/shenzhen/hrss/szksy/bmxx/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hrss/szksy/index.ts",
  "maintainers": [
    "zlasd"
  ],
  "name": "考试院",
  "parameters": {
    "caty": "信息类别",
    "page": "历史兼容参数，所有值均返回第 1 页，不翻页"
  },
  "path": "/hrss/szksy/:caty/:page?",
  "radar": [
    {
      "source": [
        "hrss.sz.gov.cn/szksy/zwgk/:caty/index.html"
      ],
      "target": "/hrss/szksy/:caty"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "hrss.sz.gov.cn/*"
}
```
