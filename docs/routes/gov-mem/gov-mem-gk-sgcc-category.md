# 中华人民共和国应急管理部 - 事故及灾害查处

## Coverage
`index-only`

## Route
- Namespace: `gov/mem`
- Namespace Name: `中华人民共和国应急管理部`
- Route Path: `/gov/mem/gk/sgcc/:category?`
- Route Name: `事故及灾害查处`
- Example: `/gov/mem/gk/sgcc/tbzdsgdcbg`
- URL: `www.mem.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `sgcc.ts`
- Source Module: `_None_`

## Description
| 挂牌督办 | 调查报告   |
| -------- | ---------- |
| sggpdbqk | tbzdsgdcbg |

## Parameters
- `category`: 分类，见下表，默认为挂牌督办


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
  - `www.mem.gov.cn/gk/sgcc/:category`
- `target`: `/gk/sgcc/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 挂牌督办 | 调查报告   |\n| -------- | ---------- |\n| sggpdbqk | tbzdsgdcbg |",
  "example": "/gov/mem/gk/sgcc/tbzdsgdcbg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "sgcc.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "事故及灾害查处",
  "parameters": {
    "category": "分类，见下表，默认为挂牌督办"
  },
  "path": "/gk/sgcc/:category?",
  "radar": [
    {
      "source": [
        "www.mem.gov.cn/gk/sgcc/:category"
      ],
      "target": "/gk/sgcc/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "调查报告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62730408567519232",
      "image": "https://www.mem.gov.cn/jg/images/P020250415553134787719.png",
      "ownerUserId": null,
      "siteUrl": "https://www.mem.gov.cn/gk/sgcc/tbzdsgdcbg",
      "title": "调查报告--中华人民共和国应急管理部",
      "type": "feed",
      "url": "rsshub://gov/mem/gk/sgcc/tbzdsgdcbg"
    },
    {
      "description": "挂牌督办 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73327086064622592",
      "image": "https://www.mem.gov.cn/jg/images/P020250415553134787719.png",
      "ownerUserId": null,
      "siteUrl": "https://www.mem.gov.cn/gk/sgcc/sggpdbqk",
      "title": "挂牌督办--中华人民共和国应急管理部",
      "type": "feed",
      "url": "rsshub://gov/mem/gk/sgcc/sggpdbqk"
    }
  ]
}
```
