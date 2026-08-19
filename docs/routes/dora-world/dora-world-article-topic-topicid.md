# Doraemon Channel - Article

## Coverage
`index-only`

## Route
- Namespace: `dora-world`
- Namespace Name: `Doraemon Channel`
- Route Path: `/dora-world/article/:topic/:topicId?`
- Route Name: `Article`
- Example: `/dora-world/article/contents`
- URL: `www.dora-world.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `AChangAZha`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic name, can be found in URL. For example: the topic name of [https://www.dora-world.com/movie](https://www.dora-world.com/movie) is `movie`
- `topicId`: Topic id, can be found in URL. For example: the topic id of [https://www.dora-world.com/contents?t=197](https://www.dora-world.com/contents?t=197) is `197`


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
  - `www.dora-world.com/:topic`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/dora-world/article/contents",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "article.ts",
  "maintainers": [
    "AChangAZha"
  ],
  "name": "Article",
  "parameters": {
    "topic": "Topic name, can be found in URL. For example: the topic name of [https://www.dora-world.com/movie](https://www.dora-world.com/movie) is `movie`",
    "topicId": "Topic id, can be found in URL. For example: the topic id of [https://www.dora-world.com/contents?t=197](https://www.dora-world.com/contents?t=197) is `197`"
  },
  "path": "/article/:topic/:topicId?",
  "radar": [
    {
      "source": [
        "www.dora-world.com/:topic"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "映画ドラえもん のび太の絵世界物語 - ドラえもんチャンネル - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73747352310672384",
      "image": "https://dora-world.com/assets/images/DORAch_web-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dora-world.com/movie",
      "title": "映画ドラえもん のび太の絵世界物語 - ドラえもんチャンネル",
      "type": "feed",
      "url": "rsshub://dora-world/article/movie"
    },
    {
      "description": "新着 - ドラえもんチャンネル - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70014144165769216",
      "image": "https://dora-world.com/assets/images/DORAch_web-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dora-world.com/contents",
      "title": "新着 - ドラえもんチャンネル",
      "type": "feed",
      "url": "rsshub://dora-world/article/contents"
    }
  ],
  "view": 0
}
```
