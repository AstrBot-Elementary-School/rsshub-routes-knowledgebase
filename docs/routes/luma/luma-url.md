# LuMa - Events

## Coverage
`index-only`

## Route
- Namespace: `luma`
- Namespace Name: `LuMa`
- Route Path: `/luma/:url`
- Route Name: `Events`
- Example: `/luma/singapore`
- URL: `luma.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `url`: LuMa URL


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
  - `luma.com/:url`
- `target`: `/:url`
### Rule 2
- `source`:
  - `lu.ma/:url`
- `target`: `/:url`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/luma/singapore",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "index.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Events",
  "parameters": {
    "url": "LuMa URL"
  },
  "path": "/:url",
  "radar": [
    {
      "source": [
        "luma.com/:url"
      ],
      "target": "/:url"
    },
    {
      "source": [
        "lu.ma/:url"
      ],
      "target": "/:url"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "LangChain Events - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62716706890373120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lu.ma/langchain",
      "title": "LangChain Events",
      "type": "feed",
      "url": "rsshub://luma/langchain"
    },
    {
      "description": "Reading Rhythms Global - Powered by RSSHub",
      "errorAt": "2026-10-08T02:31:19.621Z",
      "errorMessage": "[GET] \"https://api.lu.ma/url?url=readingrhythms-global\": 429 Too Many Requests\n",
      "id": "265967037132484608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lu.ma/readingrhythms-global",
      "title": "Reading Rhythms Global",
      "type": "feed",
      "url": "rsshub://luma/readingrhythms-global"
    }
  ],
  "url": "luma.com"
}
```
