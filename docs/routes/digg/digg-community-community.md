# Digg - Topic Stories

## Coverage
`index-only`

## Route
- Namespace: `digg`
- Namespace Name: `Digg`
- Route Path: `/digg/community/:community`
- Route Name: `Topic Stories`
- Example: `/digg/community/tech`
- URL: `digg.com/`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `community.tsx`
- Source Module: `_None_`

## Description
Digg now publishes topic stories instead of the former community posts. Retired communities such as askdigg are unavailable. Only the current first page of published stories is returned.

## Parameters
- `community`: Current topic slug from the Digg URL, such as tech, ai, gaming, entertainment, world-business, science, or sports


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
  - `digg.com/:community`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Digg now publishes topic stories instead of the former community posts. Retired communities such as askdigg are unavailable. Only the current first page of published stories is returned.",
  "example": "/digg/community/tech",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "community.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Topic Stories",
  "parameters": {
    "community": "Current topic slug from the Digg URL, such as tech, ai, gaming, entertainment, world-business, science, or sports"
  },
  "path": "/community/:community",
  "radar": [
    {
      "source": [
        "digg.com/:community"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "digg.com/"
}
```
