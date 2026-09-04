# Nautilus - Topics

## Coverage
`index-only`

## Route
- Namespace: `nautil`
- Namespace Name: `Nautilus`
- Route Path: `/nautil/topic/:tid`
- Route Name: `Topics`
- Example: `/nautil/topic/arts`
- URL: `nautil.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `topics.tsx`
- Source Module: `_None_`

## Description
This route provides a flexible plan with full text content to subscribe specific topic(s) on the Nautilus. Please visit [nautil.us](https://nautil.us) and click `Topics` to acquire whole topic list.

## Parameters
- `tid`: topic


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
  - `nautil.us/topics/:tid`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "This route provides a flexible plan with full text content to subscribe specific topic(s) on the Nautilus. Please visit [nautil.us](https://nautil.us) and click `Topics` to acquire whole topic list.",
  "example": "/nautil/topic/arts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 65,
  "location": "topics.tsx",
  "maintainers": [
    "emdoe"
  ],
  "name": "Topics",
  "parameters": {
    "tid": "topic"
  },
  "path": "/topic/:tid",
  "radar": [
    {
      "source": [
        "nautil.us/topics/:tid"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Nautilus | Arts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84839684406711296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nautil.us/topics/arts/",
      "title": "Nautilus | Arts",
      "type": "feed",
      "url": "rsshub://nautil/topic/arts"
    },
    {
      "description": "Nautilus | Health - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85929973486211072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nautil.us/topics/health/",
      "title": "Nautilus | Health",
      "type": "feed",
      "url": "rsshub://nautil/topic/health"
    }
  ]
}
```
