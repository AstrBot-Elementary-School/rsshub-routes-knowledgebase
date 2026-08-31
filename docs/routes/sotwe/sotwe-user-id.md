# X (Twitter) - User timeline - Sotwe

## Coverage
`index-only`

## Route
- Namespace: `sotwe`
- Namespace Name: `X (Twitter)`
- Route Path: `/sotwe/user/:id`
- Route Name: `User timeline - Sotwe`
- Example: `/sotwe/user/_RSSHub`
- URL: `x.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Twitter username


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.sotwe.com/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/sotwe/user/_RSSHub",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User timeline - Sotwe",
  "parameters": {
    "id": "Twitter username"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "www.sotwe.com/:id"
      ],
      "target": "/user/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 2
}
```
