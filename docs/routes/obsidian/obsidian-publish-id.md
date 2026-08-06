# Obsidian - Publish

## Coverage
`index-only`

## Route
- Namespace: `obsidian`
- Namespace Name: `Obsidian`
- Route Path: `/obsidian/publish/:id`
- Route Name: `Publish`
- Example: `/obsidian/publish/marshallontheroad`
- URL: `publish.obsidian.md/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Xy2002`
- Source Location: `publish.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 网站 id，由Publish持有者自定义


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
  - `publish.obsidian.md/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/obsidian/publish/marshallontheroad",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 46,
  "location": "publish.ts",
  "maintainers": [
    "Xy2002"
  ],
  "name": "Publish",
  "parameters": {
    "id": "网站 id，由Publish持有者自定义"
  },
  "path": "/publish/:id",
  "radar": [
    {
      "source": [
        "publish.obsidian.md/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Obsidian Publish - Powered by RSSHub",
      "errorAt": "2026-02-26T02:32:22.133Z",
      "errorMessage": "[GET] \"https://publish.obsidian.md/marshallontheroad\": 404 Not Found\n",
      "id": "61600181436221440",
      "image": null,
      "ownerUserId": "59203816531726336",
      "siteUrl": "https://publish.obsidian.md/",
      "title": "Obsidian Publish",
      "type": "feed",
      "url": "rsshub://obsidian/publish/marshallontheroad"
    }
  ],
  "url": "publish.obsidian.md/"
}
```
