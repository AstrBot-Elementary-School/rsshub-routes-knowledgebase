# DEV Community - Top Posts

## Coverage
`index-only`

## Route
- Namespace: `dev.to`
- Namespace Name: `DEV Community`
- Route Path: `/dev.to/top/:period`
- Route Name: `Top Posts`
- Example: `/dev.to/top/week`
- URL: `dev.to/top`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `dwemerx, Rjnishant530`
- Source Location: `top.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `period`: Period (week, month, year, infinity)


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
  - `dev.to/top/:period`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/dev.to/top/week",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 132,
  "location": "top.ts",
  "maintainers": [
    "dwemerx",
    "Rjnishant530"
  ],
  "name": "Top Posts",
  "parameters": {
    "period": "Period (week, month, year, infinity)"
  },
  "path": "/top/:period",
  "radar": [
    {
      "source": [
        "dev.to/top/:period"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Top dev.to posts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "151151136731356160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dev.to/top/week",
      "title": "dev.to top (week)",
      "type": "feed",
      "url": "rsshub://dev.to/top/week"
    },
    {
      "description": "Top dev.to posts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "145315249048801291",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dev.to/top/month",
      "title": "dev.to top (month)",
      "type": "feed",
      "url": "rsshub://dev.to/top/month"
    }
  ],
  "url": "dev.to/top"
}
```
