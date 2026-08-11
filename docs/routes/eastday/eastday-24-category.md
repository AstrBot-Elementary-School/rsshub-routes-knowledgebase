# 东方网 - 24 小时热闻

## Coverage
`index-only`

## Route
- Namespace: `eastday`
- Namespace Name: `东方网`
- Route Path: `/eastday/24/:category?`
- Route Name: `24 小时热闻`
- Example: `/eastday/24`
- URL: `mini.eastday.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `24.ts`
- Source Module: `_None_`

## Description
| 推荐 | 社会 | 娱乐 | 国际 | 军事 |
| ---- | ---- | ---- | ---- | ---- |

| 养生 | 汽车 | 体育 | 财经 | 游戏 |
| ---- | ---- | ---- | ---- | ---- |

| 科技 | 国内 | 宠物 | 情感 | 人文 | 教育 |
| ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `category`: 分类，见下表，默认为社会


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
  - `mini.eastday.com/`
- `target`: `/24`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 推荐 | 社会 | 娱乐 | 国际 | 军事 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 养生 | 汽车 | 体育 | 财经 | 游戏 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 科技 | 国内 | 宠物 | 情感 | 人文 | 教育 |\n| ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/eastday/24",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 62,
  "location": "24.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "24 小时热闻",
  "parameters": {
    "category": "分类，见下表，默认为社会"
  },
  "path": "/24/:category?",
  "radar": [
    {
      "source": [
        "mini.eastday.com/"
      ],
      "target": "/24"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "24小时社会热闻 - 东方资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59852419254124544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mini.eastday.com/#shehui",
      "title": "24小时社会热闻 - 东方资讯",
      "type": "feed",
      "url": "rsshub://eastday/24"
    },
    {
      "description": "24小时教育热闻 - 东方资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896288583692",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mini.eastday.com/#jiaoyu",
      "title": "24小时教育热闻 - 东方资讯",
      "type": "feed",
      "url": "rsshub://eastday/24/%E6%95%99%E8%82%B2"
    }
  ],
  "url": "mini.eastday.com/"
}
```
