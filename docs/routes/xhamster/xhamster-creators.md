# xHamster - Newest Videos by Creator

## Coverage
`index-only`

## Route
- Namespace: `xhamster`
- Namespace Name: `xHamster`
- Route Path: `/xhamster/:creators`
- Route Name: `Newest Videos by Creator`
- Example: `/xhamster/faustina-pierre`
- URL: `xhamster.com/faustina-pierre/newest`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `eve2ptp`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `creators`: Creator slug from the URL (e.g. `faustina-pierre`)


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
  - `xhamster.com/creators/:creators`
  - `xhamster.com/creators/:creators/newest`
- `target`: `/:creators`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/xhamster/faustina-pierre",
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
  "location": "index.ts",
  "maintainers": [
    "eve2ptp"
  ],
  "name": "Newest Videos by Creator",
  "parameters": {
    "creators": "Creator slug from the URL (e.g. `faustina-pierre`)"
  },
  "path": "/:creators",
  "radar": [
    {
      "source": [
        "xhamster.com/creators/:creators",
        "xhamster.com/creators/:creators/newest"
      ],
      "target": "/:creators"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Latest videos from Xxx on xHamster - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1161921301883781120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xhamster.com/creators/Xxx/newest",
      "title": "Xxx - newest videos on xHamster",
      "type": "feed",
      "url": "rsshub://xhamster/Xxx"
    }
  ],
  "url": "xhamster.com/faustina-pierre/newest"
}
```
