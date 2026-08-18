# Curius - User

## Coverage
`index-only`

## Route
- Namespace: `curius`
- Namespace Name: `Curius`
- Route Path: `/curius/links/:name`
- Route Name: `User`
- Example: `/curius/links/yuu-yuu`
- URL: `curius.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Ovler-Young`
- Source Location: `links.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: Username, can be found in URL


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
  - `curius.app/:name`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/curius/links/yuu-yuu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "links.tsx",
  "maintainers": [
    "Ovler-Young"
  ],
  "name": "User",
  "parameters": {
    "name": "Username, can be found in URL"
  },
  "path": "/links/:name",
  "radar": [
    {
      "source": [
        "curius.app/:name"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
