# New Yorker - Articles

## Coverage
`index-only`

## Route
- Namespace: `newyorker`
- Namespace Name: `New Yorker`
- Route Path: `/newyorker/:category`
- Route Name: `Articles`
- Example: `/newyorker/latest`
- URL: `newyorker.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `IvanWng97, pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: tab name. can be found at url


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
  - `newyorker.com/:category?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "example": "/newyorker/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1643,
  "location": "news.ts",
  "maintainers": [
    "IvanWng97",
    "pseudoyu"
  ],
  "name": "Articles",
  "parameters": {
    "category": "tab name. can be found at url"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "newyorker.com/:category?"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Reporting, Profiles, breaking news, cultural coverage, podcasts, videos, and cartoons from The New Yorker. - Powered by RSSHub",
      "errorAt": "2026-08-23T15:16:09.108Z",
      "errorMessage": "200 ",
      "id": "49394735648572416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.newyorker.com/",
      "title": "The New Yorker - latest",
      "type": "feed",
      "url": "rsshub://newyorker/latest"
    },
    {
      "description": "Reporting, Profiles, breaking news, cultural coverage, podcasts, videos, and cartoons from The New Yorker. - Powered by RSSHub",
      "errorAt": "2026-08-24T09:54:27.673Z",
      "errorMessage": "200 ",
      "id": "62040507105143808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.newyorker.com/",
      "title": "The New Yorker - news",
      "type": "feed",
      "url": "rsshub://newyorker/news"
    }
  ],
  "view": 0
}
```
