# AP News - News (from mobile client API)

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/apnews/mobile/:path{.+}?`
- Route Name: `News (from mobile client API)`
- Example: `/apnews/mobile`
- URL: `apnews.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `mobile-api.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: {"default": "/", "description": "Corresponding path from AP News website"}


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
  - `apnews.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/mobile",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "mobile-api.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "News (from mobile client API)",
  "parameters": {
    "path": {
      "default": "/",
      "description": "Corresponding path from AP News website"
    }
  },
  "path": "/mobile/:path{.+}?",
  "radar": [
    {
      "source": [
        "apnews.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "TopNews - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "135162752276972544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apnews.com/",
      "title": "TopNews",
      "type": "feed",
      "url": "rsshub://apnews/mobile"
    }
  ],
  "view": 0
}
```
