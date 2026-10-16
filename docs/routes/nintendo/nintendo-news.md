# Nintendo - News（Hong Kong only）

## Coverage
`index-only`

## Route
- Namespace: `nintendo`
- Namespace Name: `Nintendo`
- Route Path: `/nintendo/news`
- Route Name: `News（Hong Kong only）`
- Example: `/nintendo/news`
- URL: `nintendo.com.hk/topics`
- Language: `_None_`
- Categories: `game`
- Maintainers: `HFO4`
- Source Location: `news.ts`
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
  - `nintendo.com.hk/topics`
  - `nintendo.com.hk/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/nintendo/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "news.ts",
  "maintainers": [
    "HFO4"
  ],
  "name": "News（Hong Kong only）",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "nintendo.com.hk/topics",
        "nintendo.com.hk/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Nintendo 香港有限公司官网刊登的资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "161614209329340417",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nintendo.com.hk/topics/",
      "title": "Nintendo（香港）主页资讯",
      "type": "feed",
      "url": "rsshub://nintendo/news"
    }
  ],
  "url": "nintendo.com.hk/topics"
}
```
