# China.com 中华网 - News and current affairs 时事新闻

## Coverage
`index-only`

## Route
- Namespace: `china`
- Namespace Name: `China.com 中华网`
- Route Path: `/china/news/:category?`
- Route Name: `News and current affairs 时事新闻`
- Example: `/china/news`
- URL: `finance.china.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `jiaaoMario`
- Source Location: `news/highlights/news.ts`
- Source Module: `_None_`

## Description
Category of news

| China News | International News | Social News | Breaking News |
| ---------- | ------------------ | ----------- | ------------- |
| domestic   | international      | social      | news100       |

## Parameters
- `category`: Category of news. See the form below for details, default is china news.


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
  - `news.china.com/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Category of news\n\n| China News | International News | Social News | Breaking News |\n| ---------- | ------------------ | ----------- | ------------- |\n| domestic   | international      | social      | news100       |",
  "example": "/china/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 37,
  "location": "news/highlights/news.ts",
  "maintainers": [
    "jiaaoMario"
  ],
  "name": "News and current affairs 时事新闻",
  "parameters": {
    "category": "Category of news. See the form below for details, default is china news."
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.china.com/:category"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中华网-国内新闻 - Powered by RSSHub",
      "errorAt": "2026-01-20T09:48:46.713Z",
      "errorMessage": "[GET] \"https://news.china.com/domestic\": 403 Forbidden\n",
      "id": "56595070994110464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.china.com/domestic",
      "title": "中华网-国内新闻",
      "type": "feed",
      "url": "rsshub://china/news"
    },
    {
      "description": "中华网-国际新闻 - Powered by RSSHub",
      "errorAt": "2026-01-20T12:40:01.537Z",
      "errorMessage": "[GET] \"https://news.china.com/international\": 403 Forbidden\n",
      "id": "62419416331832320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.china.com/international",
      "title": "中华网-国际新闻",
      "type": "feed",
      "url": "rsshub://china/news/international"
    }
  ]
}
```
