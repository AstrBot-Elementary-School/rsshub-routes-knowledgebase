# GIS Reports - 报告

## Coverage
`index-only`

## Route
- Namespace: `gisreportsonline`
- Namespace Name: `GIS Reports`
- Route Path: `/gisreportsonline/:path{.+}?`
- Route Name: `报告`
- Example: `/gisreportsonline/gis/c/security-challenges/`
- URL: `www.gisreportsonline.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `dzx-dzx`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: 包含"Reports"页面下的路径


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.gisreportsonline.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/gisreportsonline/gis/c/security-challenges/",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "报告",
  "parameters": {
    "path": "包含\"Reports\"页面下的路径"
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "www.gisreportsonline.com"
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
