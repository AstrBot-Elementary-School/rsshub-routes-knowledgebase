# Google - Search

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/search/:keyword/:language?`
- Route Name: `Search`
- Example: `/google/search/rss/zh-CN,zh`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Keyword
- `language`: Accept-Language. Example: `zh-CN,zh;q=0.9,en;q=0.8,ja;q=0.7`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/google/search/rss/zh-CN,zh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Keyword",
    "language": "Accept-Language. Example: `zh-CN,zh;q=0.9,en;q=0.8,ja;q=0.7`"
  },
  "path": "/search/:keyword/:language?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "AI赚钱 - Google Search - Powered by RSSHub",
      "errorAt": "2025-10-27T06:01:24.457Z",
      "errorMessage": "[GET] \"https://www.google.com/search?q=AI%E8%B5%9A%E9%92%B1\": 429 Too Many Requests\n",
      "id": "179590418034543616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.google.com/search?q=AI%E8%B5%9A%E9%92%B1",
      "title": "AI赚钱 - Google Search",
      "type": "feed",
      "url": "rsshub://google/search/AI%E8%B5%9A%E9%92%B1"
    },
    {
      "description": "被查+site:thepaper.cn - Google Search - Powered by RSSHub",
      "errorAt": "2025-09-10T17:16:47.805Z",
      "errorMessage": "[GET] \"https://www.google.com/search?q=%E8%A2%AB%E6%9F%A5%2Bsite%3Athepaper.cn\": 429 Too Many Requests\n",
      "id": "68685709659153408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.google.com/search?q=%E8%A2%AB%E6%9F%A5%2Bsite%3Athepaper.cn",
      "title": "被查+site:thepaper.cn - Google Search",
      "type": "feed",
      "url": "rsshub://google/search/%E8%A2%AB%E6%9F%A5+site:thepaper.cn"
    }
  ]
}
```
