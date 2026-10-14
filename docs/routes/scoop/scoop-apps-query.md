# Scoop - Apps

## Coverage
`index-only`

## Route
- Namespace: `scoop`
- Namespace Name: `Scoop`
- Route Path: `/scoop/apps/:query?`
- Route Name: `Apps`
- Example: `/scoop/apps`
- URL: `scoop.sh`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `apps.tsx`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Apps](https://scoop.sh/#/apps?s=2\&d=1\&n=true\&dm=true\&o=true), where the source URL is `https://scoop.sh/#/apps?s=2&d=1&n=true&dm=true&o=true`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/scoop/apps/s=2&d=1&n=true&dm=true&o=true`](https://rsshub.app/scoop/apps/s=2\&d=1\&n=true\&dm=true\&o=true).
:::

## Parameters
- `query`: {"description": "Query, `s=2&d=1&n=true&dm=true&o=true` by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `scoop.sh`
- `target`: `/apps`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nTo subscribe to [Apps](https://scoop.sh/#/apps?s=2\\&d=1\\&n=true\\&dm=true\\&o=true), where the source URL is `https://scoop.sh/#/apps?s=2&d=1&n=true&dm=true&o=true`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/scoop/apps/s=2&d=1&n=true&dm=true&o=true`](https://rsshub.app/scoop/apps/s=2\\&d=1\\&n=true\\&dm=true\\&o=true).\n:::",
  "example": "/scoop/apps",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "apps.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Apps",
  "parameters": {
    "query": {
      "description": "Query, `s=2&d=1&n=true&dm=true&o=true` by default"
    }
  },
  "path": "/apps/:query?",
  "radar": [
    {
      "source": [
        "scoop.sh"
      ],
      "target": "/apps"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Scoop - Apps - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "196204393325271040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scoop.sh/#/apps?s=2&d=1&n=true&dm=true&o=true",
      "title": "Scoop - Apps",
      "type": "feed",
      "url": "rsshub://scoop/apps"
    }
  ],
  "url": "scoop.sh",
  "view": 5
}
```
