# RssEverything - Shared Feeds

## Coverage
`index-only`

## Route
- Namespace: `rsseverything`
- Namespace Name: `RssEverything`
- Route Path: `/rsseverything/:language/sharedfeeds`
- Route Name: `Shared Feeds`
- Example: `/rsseverything/zh/sharedfeeds`
- URL: `rsseverything.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `AboutRSS`
- Source Location: `sharedfeeds.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: {"description": "Language of the page, and of the feed addresses it links to. One of `de`, `en`, `es`, `fr`, `it`, `ja`, `ko`, `pt`, `ru`, `zh`, `zh-Hant`"}


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
  - `rsseverything.com/:language/sharedfeeds`
- `target`: `/:language/sharedfeeds`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/rsseverything/zh/sharedfeeds",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sharedfeeds.ts",
  "maintainers": [
    "AboutRSS"
  ],
  "name": "Shared Feeds",
  "parameters": {
    "language": {
      "description": "Language of the page, and of the feed addresses it links to. One of `de`, `en`, `es`, `fr`, `it`, `ja`, `ko`, `pt`, `ru`, `zh`, `zh-Hant`"
    }
  },
  "path": "/:language/sharedfeeds",
  "radar": [
    {
      "source": [
        "rsseverything.com/:language/sharedfeeds"
      ],
      "target": "/:language/sharedfeeds"
    }
  ],
  "topFeeds": []
}
```
