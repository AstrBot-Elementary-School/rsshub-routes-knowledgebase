# AP News - Topics

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/apnews/topics/:topic?`
- Route Name: `Topics`
- Example: `/apnews/topics/apf-topnews`
- URL: `apnews.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: {"default": "trending-news", "description": "Topic name, can be found in URL. For example: the topic name of AP Top News [https://apnews.com/apf-topnews](https://apnews.com/apf-topnews) is `apf-topnews`"}


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
  - `apnews.com/hub/:topic`
- `target`: `/topics/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/topics/apf-topnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 747,
  "location": "topics.ts",
  "maintainers": [
    "zoenglinghou",
    "mjysci",
    "TonyRL"
  ],
  "name": "Topics",
  "parameters": {
    "topic": {
      "default": "trending-news",
      "description": "Topic name, can be found in URL. For example: the topic name of AP Top News [https://apnews.com/apf-topnews](https://apnews.com/apf-topnews) is `apf-topnews`"
    }
  },
  "path": [
    "/topics/:topic?",
    "/nav/:nav{.+}?"
  ],
  "radar": [
    {
      "source": [
        "apnews.com/hub/:topic"
      ],
      "target": "/topics/:topic"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Trending News | What's New Around the World | AP News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52388449895612416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apnews.com/hub/trending-news",
      "title": "Trending News | What's New Around the World | AP News",
      "type": "feed",
      "url": "rsshub://apnews/topics/trending-news"
    },
    {
      "description": "Associated Press News: Breaking News, Latest Headlines and Videos | AP News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41648644680942592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apnews.com/hub/apf-topnews",
      "title": "Associated Press News: Breaking News, Latest Headlines and Videos | AP News",
      "type": "feed",
      "url": "rsshub://apnews/topics/apf-topnews"
    }
  ],
  "view": 0
}
```
