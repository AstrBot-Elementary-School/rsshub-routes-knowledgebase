# 上海市人民政府 - 职业能力考试院 考试项目

## Coverage
`index-only`

## Route
- Namespace: `gov/sh`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/sh/rsj/ksxm`
- Route Name: `职业能力考试院 考试项目`
- Example: `/gov/sh/rsj/ksxm`
- URL: `rsj.sh.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `rsj/ksxm.tsx`
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
  - `rsj.sh.gov.cn/`
- `target`: `/rsj/ksxm`
### Rule 2
- `source`:
  - `rsj.sh.gov.cn/tksxm_17825/index.html`
- `target`: `/rsj/ksxm`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/sh/rsj/ksxm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rsj/ksxm.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "职业能力考试院 考试项目",
  "parameters": {},
  "path": "/rsj/ksxm",
  "radar": [
    {
      "source": [
        "rsj.sh.gov.cn/"
      ],
      "target": "/rsj/ksxm"
    },
    {
      "source": [
        "rsj.sh.gov.cn/tksxm_17825/index.html"
      ],
      "target": "/rsj/ksxm"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "rsj.sh.gov.cn/"
}
```
