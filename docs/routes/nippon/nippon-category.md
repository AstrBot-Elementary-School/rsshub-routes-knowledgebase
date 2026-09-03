# 走进日本 - 政治外交

## Coverage
`index-only`

## Route
- Namespace: `nippon`
- Namespace Name: `走进日本`
- Route Path: `/nippon/:category?`
- Route Name: `政治外交`
- Example: `/nippon/Politics`
- URL: `www.nippon.com`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `laampui`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 政治     | 经济    | 社会    | 展览预告 | 焦点专题           | 深度报道 | 话题         | 日本信息库 | 日本一蹩      | 人物访谈 | 编辑部通告    |
| -------- | ------- | ------- | -------- | ------------------ | -------- | ------------ | ---------- | ------------- | -------- | ------------- |
| Politics | Economy | Society | Culture  | Science,Technology | In-depth | japan-topics | japan-data | japan-glances | People   | Announcements |

## Parameters
- `category`: 默认政治，可选如下


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
  - `www.nippon.com/nippon/:category?`
  - `www.nippon.com/cn`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "description": "| 政治     | 经济    | 社会    | 展览预告 | 焦点专题           | 深度报道 | 话题         | 日本信息库 | 日本一蹩      | 人物访谈 | 编辑部通告    |\n| -------- | ------- | ------- | -------- | ------------------ | -------- | ------------ | ---------- | ------------- | -------- | ------------- |\n| Politics | Economy | Society | Culture  | Science,Technology | In-depth | japan-topics | japan-data | japan-glances | People   | Announcements |",
  "example": "/nippon/Politics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "index.ts",
  "maintainers": [
    "laampui"
  ],
  "name": "政治外交",
  "parameters": {
    "category": "默认政治，可选如下"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.nippon.com/nippon/:category?",
        "www.nippon.com/cn"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "走进日本 - Politics - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56644563871459336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nippon.com/cn/economy/",
      "title": "走进日本 - Politics",
      "type": "feed",
      "url": "rsshub://nippon/Politics"
    },
    {
      "description": "走进日本 - Society - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82398566855976960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nippon.com/cn/economy/",
      "title": "走进日本 - Society",
      "type": "feed",
      "url": "rsshub://nippon/Society"
    }
  ]
}
```
