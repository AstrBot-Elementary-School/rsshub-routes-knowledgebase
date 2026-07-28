# Polymarket - Events

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/polymarket/events/:tagSlug?`
- Route Name: `Events`
- Example: `/polymarket/events`
- URL: `polymarket.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `events.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tagSlug`: Tag slug to filter events, e.g. politics, sports, crypto. Omit for all events.


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
  - `polymarket.com`
  - `polymarket.com/:tagSlug`
- `target`: `/events/:tagSlug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/polymarket/events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "events.ts",
  "maintainers": [
    "heqi201255"
  ],
  "name": "Events",
  "parameters": {
    "tagSlug": "Tag slug to filter events, e.g. politics, sports, crypto. Omit for all events."
  },
  "path": "/events/:tagSlug?",
  "radar": [
    {
      "source": [
        "polymarket.com",
        "polymarket.com/:tagSlug"
      ],
      "target": "/events/:tagSlug"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Polymarket Events - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "264800045395592192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://polymarket.com/",
      "title": "Polymarket Events",
      "type": "feed",
      "url": "rsshub://polymarket/events"
    }
  ],
  "url": "polymarket.com"
}
```
