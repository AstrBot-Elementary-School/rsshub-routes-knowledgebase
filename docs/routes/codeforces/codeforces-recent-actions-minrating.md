# Codeforces - Recent actions

## Coverage
`index-only`

## Route
- Namespace: `codeforces`
- Namespace Name: `Codeforces`
- Route Path: `/codeforces/recent-actions/:minrating?`
- Route Name: `Recent actions`
- Example: `/codeforces/recent-actions`
- URL: `codeforces.com/recent-actions`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `ftiasch`
- Source Location: `recent-actions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `minrating`: The minimum blog/comment rating required. Default: 1


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
  - `codeforces.com/recent-actions`
- `target`: `/recent-actions`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/codeforces/recent-actions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "recent-actions.ts",
  "maintainers": [
    "ftiasch"
  ],
  "name": "Recent actions",
  "parameters": {
    "minrating": "The minimum blog/comment rating required. Default: 1"
  },
  "path": "/recent-actions/:minrating?",
  "radar": [
    {
      "source": [
        "codeforces.com/recent-actions"
      ],
      "target": "/recent-actions"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Codeforces - Recent actions - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65056107225187328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://codeforces.com/recent-actions",
      "title": "Codeforces - Recent actions",
      "type": "feed",
      "url": "rsshub://codeforces/recent-actions"
    }
  ],
  "url": "codeforces.com/recent-actions"
}
```
