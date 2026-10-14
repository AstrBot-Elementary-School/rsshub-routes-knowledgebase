# 上海市人民政府 - 卫健委 疫情通报

## Coverage
`index-only`

## Route
- Namespace: `gov/sh`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/sh/wsjkw/yqtb`
- Route Name: `卫健委 疫情通报`
- Example: `/gov/sh/wsjkw/yqtb`
- URL: `wsjkw.sh.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `zcf0508`
- Source Location: `wsjkw/yqtb/index.ts`
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
  - `wsjkw.sh.gov.cn/`
- `target`: `/wsjkw/yqtb`
### Rule 2
- `source`:
  - `wsjkw.sh.gov.cn/yqtb/index.html`
- `target`: `/wsjkw/yqtb`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/sh/wsjkw/yqtb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "wsjkw/yqtb/index.ts",
  "maintainers": [
    "zcf0508"
  ],
  "name": "卫健委 疫情通报",
  "parameters": {},
  "path": "/wsjkw/yqtb",
  "radar": [
    {
      "source": [
        "wsjkw.sh.gov.cn/"
      ],
      "target": "/wsjkw/yqtb"
    },
    {
      "source": [
        "wsjkw.sh.gov.cn/yqtb/index.html"
      ],
      "target": "/wsjkw/yqtb"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "wsjkw.sh.gov.cn/"
}
```
