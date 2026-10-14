# Bandcamp - Tag

## Coverage
`index-only`

## Route
- Namespace: `bandcamp`
- Namespace Name: `Bandcamp`
- Route Path: `/bandcamp/tag/:tag?`
- Route Name: `Tag`
- Example: `/bandcamp/tag/united-kingdom`
- URL: `bandcamp.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `tag.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag, can be found in URL. All music by default.


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
  - `bandcamp.com/tag/:tag`
  - `bandcamp.com/discover/:tag`
- `target`: `/tag/:tag`
### Rule 2
- `source`:
  - `bandcamp.com/discover`
- `target`: `/tag`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bandcamp/tag/united-kingdom",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tag.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Tag",
  "parameters": {
    "tag": "Tag, can be found in URL. All music by default."
  },
  "path": "/tag/:tag?",
  "radar": [
    {
      "source": [
        "bandcamp.com/tag/:tag",
        "bandcamp.com/discover/:tag"
      ],
      "target": "/tag/:tag"
    },
    {
      "source": [
        "bandcamp.com/discover"
      ],
      "target": "/tag"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
