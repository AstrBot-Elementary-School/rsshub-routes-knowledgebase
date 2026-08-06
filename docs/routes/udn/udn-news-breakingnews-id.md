# 聯合新聞網 - 即時新聞

## Coverage
`index-only`

## Route
- Namespace: `udn`
- Namespace Name: `聯合新聞網`
- Route Path: `/udn/news/breakingnews/:id`
- Route Name: `即時新聞`
- Example: `/udn/news/breakingnews/99`
- URL: `udn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `miles170, pseudoyu`
- Source Location: `breaking-news.tsx`
- Source Module: `_None_`

## Description
| 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 11   | 12   | 13   | 99     |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |
| 精選 | 要聞 | 社會 | 地方 | 兩岸 | 國際 | 財經 | 運動 | 娛樂 | 生活 | 股市 | 文教 | 數位 | 不分類 |

## Parameters
- `id`: 类别


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
  - `udn.com/news/breaknews/1/:id`
  - `udn.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 11   | 12   | 13   | 99     |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |\n| 精選 | 要聞 | 社會 | 地方 | 兩岸 | 國際 | 財經 | 運動 | 娛樂 | 生活 | 股市 | 文教 | 數位 | 不分類 |",
  "example": "/udn/news/breakingnews/99",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 255,
  "location": "breaking-news.tsx",
  "maintainers": [
    "miles170",
    "pseudoyu"
  ],
  "name": "即時新聞",
  "parameters": {
    "id": "类别"
  },
  "path": "/news/breakingnews/:id",
  "radar": [
    {
      "source": [
        "udn.com/news/breaknews/1/:id",
        "udn.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "udn.com 提供即時新聞以及豐富的政治、社會、地方、兩岸、國際、財經、數位、運動、NBA、娛樂、生活、健康、旅遊新聞，以最即時、多元的內容，滿足行動世代的需求 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67002999442518016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://udn.com/news/breaknews/1/99#breaknews",
      "title": "即時不分類 - 聯合新聞網",
      "type": "feed",
      "url": "rsshub://udn/news/breakingnews/99"
    },
    {
      "description": "udn.com 提供即時新聞以及豐富的政治、社會、地方、兩岸、國際、財經、數位、運動、NBA、娛樂、生活、健康、旅遊新聞，以最即時、多元的內容，滿足行動世代的需求 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62014591710445580",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://udn.com/news/breaknews/1/4#breaknews",
      "title": "即時兩岸 - 聯合新聞網",
      "type": "feed",
      "url": "rsshub://udn/news/breakingnews/4"
    }
  ]
}
```
