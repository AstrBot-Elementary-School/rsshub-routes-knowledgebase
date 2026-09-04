# ProjectJAV - Actress

## Coverage
`index-only`

## Route
- Namespace: `projectjav`
- Namespace Name: `ProjectJAV`
- Route Path: `/projectjav/actress/:id`
- Route Name: `Actress`
- Example: `/projectjav/actress/rima-arai-22198`
- URL: `projectjav.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Exat1979`
- Source Location: `actress.ts`
- Source Module: `_None_`

## Description
Fetches the latest movies from a specific actress page on ProjectJAV.

## Parameters
- `id`: Actress ID or slug, can be found in the actress page URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `projectjav.com/actress/:id`
- `target`: `/actress/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Fetches the latest movies from a specific actress page on ProjectJAV.",
  "example": "/projectjav/actress/rima-arai-22198",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "actress.ts",
  "maintainers": [
    "Exat1979"
  ],
  "name": "Actress",
  "parameters": {
    "id": "Actress ID or slug, can be found in the actress page URL"
  },
  "path": "/actress/:id",
  "radar": [
    {
      "source": [
        "projectjav.com/actress/:id"
      ],
      "target": "/actress/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Rima Arai movies - ProjectJav - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1139641585395171328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://projectjav.com/actress/rima-arai-22198",
      "title": "Rima Arai movies - ProjectJav",
      "type": "feed",
      "url": "rsshub://projectjav/actress/rima-arai-22198"
    }
  ],
  "url": "projectjav.com/"
}
```
