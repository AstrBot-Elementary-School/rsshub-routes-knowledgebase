# 客家電視台 - 新聞首頁

## Coverage
`index-only`

## Route
- Namespace: `hakkatv`
- Namespace Name: `客家電視台`
- Route Path: `/hakkatv/news/:type?`
- Route Name: `新聞首頁`
- Example: `/hakkatv/news`
- URL: `hakkatv.org.tw/news`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 客家焦點 | 政經要聞  | 民生醫療 | 地方風采 | 國際萬象      |
| -------- | --------- | -------- | -------- | ------------- |
| hakka    | political | medical  | local    | international |

## Parameters
- `type`: 新聞，見下表，留空為全部


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
  - `hakkatv.org.tw/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 客家焦點 | 政經要聞  | 民生醫療 | 地方風采 | 國際萬象      |\n| -------- | --------- | -------- | -------- | ------------- |\n| hakka    | political | medical  | local    | international |",
  "example": "/hakkatv/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新聞首頁",
  "parameters": {
    "type": "新聞，見下表，留空為全部"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "hakkatv.org.tw/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "客家電視是屬於全民、以至於全世界客家族群的頻道，亦是為傳播客家文化而存在，定位為「全體客家族群之媒體」。 - Powered by RSSHub",
      "errorAt": "2026-05-15T19:48:21.195Z",
      "errorMessage": "500 Internal Server Error\n",
      "id": "167304163667564544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hakkatv.org.tw/news",
      "title": "新聞首頁 - 客家電視台",
      "type": "feed",
      "url": "rsshub://hakkatv/news"
    }
  ],
  "url": "hakkatv.org.tw/news"
}
```
