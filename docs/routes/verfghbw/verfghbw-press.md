# Constitutional Court of Baden-Württemberg (Germany) - Press releases

## Coverage
`index-only`

## Route
- Namespace: `verfghbw`
- Namespace Name: `Constitutional Court of Baden-Württemberg (Germany)`
- Route Path: `/verfghbw/press`
- Route Name: `Press releases`
- Example: `/verfghbw/press`
- URL: `verfgh.baden-wuerttemberg.de/presse-und-service/pressemitteilungen/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `quinn-dev`
- Source Location: `press.ts`
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
  - `verfgh.baden-wuerttemberg.de/presse-und-service/pressemitteilungen/`
- `target`: `/press`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/verfghbw/press",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "press.ts",
  "maintainers": [
    "quinn-dev"
  ],
  "name": "Press releases",
  "path": "/press",
  "radar": [
    {
      "source": [
        "verfgh.baden-wuerttemberg.de/presse-und-service/pressemitteilungen/"
      ],
      "target": "/press"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Pressemitteilungen des Verfassungsgerichtshof für das Land Baden-Württemberg - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1271238062658945024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://verfgh.baden-wuerttemberg.de/presse-und-service/pressemitteilungen/",
      "title": "Verfassungsgerichtshof Baden-Württemberg - Pressemitteilungen",
      "type": "feed",
      "url": "rsshub://verfghbw/press"
    }
  ],
  "url": "verfgh.baden-wuerttemberg.de/presse-und-service/pressemitteilungen/"
}
```
