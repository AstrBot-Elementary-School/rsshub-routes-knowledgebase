# hameln - chapter

## Coverage
`index-only`

## Route
- Namespace: `hameln`
- Namespace Name: `hameln`
- Route Path: `/hameln/chapter/:id`
- Route Name: `chapter`
- Example: `/hameln/chapter/264928`
- URL: `syosetu.org`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `huangliangshusheng`
- Source Location: `chapter.ts`
- Source Module: `_None_`

## Description
Eg: <https://syosetu.org/novel/264928>

## Parameters
- `id`: Novel id, can be found in URL


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
  - `syosetu.org/novel/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "Eg: <https://syosetu.org/novel/264928>",
  "example": "/hameln/chapter/264928",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "chapter.ts",
  "maintainers": [
    "huangliangshusheng"
  ],
  "name": "chapter",
  "parameters": {
    "id": "Novel id, can be found in URL"
  },
  "path": "/chapter/:id",
  "radar": [
    {
      "source": [
        "syosetu.org/novel/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
