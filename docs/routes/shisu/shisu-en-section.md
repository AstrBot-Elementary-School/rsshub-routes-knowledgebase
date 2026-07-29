# 上海外国语大学 - SISU TODAY | FEATURED STORIES

## Coverage
`index-only`

## Route
- Namespace: `shisu`
- Namespace Name: `上海外国语大学`
- Route Path: `/shisu/en/:section`
- Route Name: `SISU TODAY | FEATURED STORIES`
- Example: `/shisu/en/news`
- URL: `shisu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Duuckjing`
- Source Location: `en.ts`
- Source Module: `_None_`

## Description
- features: Read a series of in-depth stories about SISU faculty, students, alumni and beyond campus.
  - news: SISU TODAY English site.

## Parameters
- `section`: The name of resources


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `en.shisu.edu.cn/resources/:section/`
- `target`: `/en/:section`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "- features: Read a series of in-depth stories about SISU faculty, students, alumni and beyond campus.\n  - news: SISU TODAY English site.",
  "example": "/shisu/en/news",
  "heat": 0,
  "location": "en.ts",
  "maintainers": [
    "Duuckjing"
  ],
  "name": "SISU TODAY | FEATURED STORIES",
  "parameters": {
    "section": "The name of resources"
  },
  "path": "/en/:section",
  "radar": [
    {
      "source": [
        "en.shisu.edu.cn/resources/:section/"
      ],
      "target": "/en/:section"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
