# 中国期货业协会 - 分析师园地

## Coverage
`index-only`

## Route
- Namespace: `cfachina`
- Namespace Name: `中国期货业协会`
- Route Path: `/cfachina/servicesupport/analygarden/:program?`
- Route Name: `分析师园地`
- Example: `/cfachina/servicesupport/analygarden`
- URL: `www.cfachina.org`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `analygarden.ts`
- Source Module: `_None_`

## Description
| 有色金属类 | 黑色金属类 | 能源化工类 | 贵金属类 | 农产品类 | 金融类 | 指数类 |
| ---------- | ---------- | ---------- | -------- | -------- | ------ | ------ |
| ysjsl      | hsjsl      | nyhgl      | gjsl     | ncpl     | jrl    | zsl    |

## Parameters
- `program`: 分类，见下表，留空为全部


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
  - `cfachina.org/servicesupport/analygarden/:program?`
  - `cfachina.org/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 有色金属类 | 黑色金属类 | 能源化工类 | 贵金属类 | 农产品类 | 金融类 | 指数类 |\n| ---------- | ---------- | ---------- | -------- | -------- | ------ | ------ |\n| ysjsl      | hsjsl      | nyhgl      | gjsl     | ncpl     | jrl    | zsl    |",
  "example": "/cfachina/servicesupport/analygarden",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "analygarden.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分析师园地",
  "parameters": {
    "program": "分类，见下表，留空为全部"
  },
  "path": "/servicesupport/analygarden/:program?",
  "radar": [
    {
      "source": [
        "cfachina.org/servicesupport/analygarden/:program?",
        "cfachina.org/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "分析师园地 - 中国期货业协会 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59799220289372187",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cfachina.org/servicesupport/analygarden/",
      "title": "分析师园地 - 中国期货业协会",
      "type": "feed",
      "url": "rsshub://cfachina/servicesupport/analygarden"
    }
  ]
}
```
