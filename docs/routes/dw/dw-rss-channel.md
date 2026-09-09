# DW Deutsche Welle - RSS

## Coverage
`index-only`

## Route
- Namespace: `dw`
- Namespace Name: `DW Deutsche Welle`
- Route Path: `/dw/rss/:channel?`
- Route Name: `RSS`
- Example: `/dw/rss/rss-en-all`
- URL: `dw.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `rss.ts`
- Source Module: `_None_`

## Description
For a full list of RSS Feed Channels in English, please refer to [DW RSS Feeds](https://corporate.dw.com/en/rss-feeds/a-68693346).
RSS Feed Channels in other languages are also available, for example: `rss-chi-all` renders the RSS feed in Chinese and `rss-de-all` for the RSS Feed in German

## Parameters
- `category`: RSS Feed Channel, see below, `rss-en-all` by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "For a full list of RSS Feed Channels in English, please refer to [DW RSS Feeds](https://corporate.dw.com/en/rss-feeds/a-68693346).\nRSS Feed Channels in other languages are also available, for example: `rss-chi-all` renders the RSS feed in Chinese and `rss-de-all` for the RSS Feed in German",
  "example": "/dw/rss/rss-en-all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 22,
  "location": "rss.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "RSS",
  "parameters": {
    "category": "RSS Feed Channel, see below, `rss-en-all` by default"
  },
  "path": "/rss/:channel?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Deutsche Welle - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80331041578519552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dw.com/english/?maca=en-rss-en-all-1573-rdf",
      "title": "Deutsche Welle",
      "type": "feed",
      "url": "rsshub://dw/rss/rss-en-all"
    },
    {
      "description": "Deutsche Welle: DW-WORLD.DE - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80330476301410304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dw.com/chinese/?maca=chi-rss-chi-all-1127-rdf",
      "title": "Deutsche Welle: DW-WORLD.DE",
      "type": "feed",
      "url": "rsshub://dw/rss/rss-chi-all"
    }
  ]
}
```
