# Lens - Lens Profile

## Coverage
`index-only`

## Route
- Namespace: `lens`
- Namespace Name: `Lens`
- Route Path: `/lens/profile/:handle`
- Route Name: `Lens Profile`
- Example: `/lens/profile/stani`
- URL: `www.lens.xyz`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: Lens handle


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
  - `hey.xyz/u/:handle`
- `target`: `/profile/:handle`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/lens/profile/stani",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "profile.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Lens Profile",
  "parameters": {
    "handle": "Lens handle"
  },
  "path": "/profile/:handle",
  "radar": [
    {
      "source": [
        "hey.xyz/u/:handle"
      ],
      "target": "/profile/:handle"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
