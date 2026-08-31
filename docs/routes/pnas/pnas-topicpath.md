# Proceedings of The National Academy of Sciences - Journal

## Coverage
`index-only`

## Route
- Namespace: `pnas`
- Namespace Name: `Proceedings of The National Academy of Sciences`
- Route Path: `/pnas/:topicPath{.+}?`
- Route Name: `Journal`
- Example: `/pnas/latest`
- URL: `pnas.org/*topicPath`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `emdoe, HenryQW, y9c`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
Some topics require adding `topic/` to `topicPath` like [`/pnas/topic/app-math`](https://rsshub.app/pnas/topic/app-math) and some don't like [`/pnas/biophysics-and-computational-biology`](https://rsshub.app/pnas/biophysics-and-computational-biology)
:::

## Parameters
- `topicPath`: Topic path, support **Featured Topics**, **Articles By Topic** and [**Collected Papers**](https://www.pnas.org/about/collected-papers), `latest` by default


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `pnas.org/*topicPath`
- `target`: `/:topicPath`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: tip\nSome topics require adding `topic/` to `topicPath` like [`/pnas/topic/app-math`](https://rsshub.app/pnas/topic/app-math) and some don't like [`/pnas/biophysics-and-computational-biology`](https://rsshub.app/pnas/biophysics-and-computational-biology)\n:::",
  "example": "/pnas/latest",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true,
    "supportScihub": true
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "emdoe",
    "HenryQW",
    "y9c"
  ],
  "name": "Journal",
  "parameters": {
    "topicPath": "Topic path, support **Featured Topics**, **Articles By Topic** and [**Collected Papers**](https://www.pnas.org/about/collected-papers), `latest` by default"
  },
  "path": "/:topicPath{.+}?",
  "radar": [
    {
      "source": [
        "pnas.org/*topicPath"
      ],
      "target": "/:topicPath"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "pnas.org/*topicPath"
}
```
