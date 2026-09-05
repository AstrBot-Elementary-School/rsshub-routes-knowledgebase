# Nature Journal - Research Highlight

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/highlight/:journal?`
- Route Name: `Research Highlight`
- Example: `/nature/highlight`
- URL: `nature.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `highlight.ts`
- Source Module: `_None_`

## Description
::: warning
Only some journals are supported.
:::

## Parameters
- `journal`: short name for a journal, `nature` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/:journal/articles`
  - `nature.com/:journal`
  - `nature.com/`
- `target`: `/highlight/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: warning\nOnly some journals are supported.\n:::",
  "example": "/nature/highlight",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 510,
  "location": "highlight.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Research Highlight",
  "parameters": {
    "journal": "short name for a journal, `nature` by default"
  },
  "path": "/highlight/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/:journal/articles",
        "nature.com/:journal",
        "nature.com/"
      ],
      "target": "/highlight/:journal"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Browse the archive of articles on Nature - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73724428627161091",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/articles?type=research-highlight",
      "title": "Research Highlights | Nature",
      "type": "feed",
      "url": "rsshub://nature/highlight"
    },
    {
      "description": "Browse the archive of articles on Nature - Powered by RSSHub",
      "errorAt": "2026-06-19T22:03:13.377Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "121071135298905088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/articles?type=research-highlight",
      "title": "Research Highlights | Nature",
      "type": "feed",
      "url": "rsshub://nature/highlight/nature"
    }
  ]
}
```
