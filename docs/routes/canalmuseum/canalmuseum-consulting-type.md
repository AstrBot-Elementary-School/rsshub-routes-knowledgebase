# The Grand Canal Museum of Beijing - NEWS

## Coverage
`index-only`

## Route
- Namespace: `canalmuseum`
- Namespace Name: `The Grand Canal Museum of Beijing`
- Route Path: `/canalmuseum/consulting/:type`
- Route Name: `NEWS`
- Example: `/canalmuseum/consulting/tzgg`
- URL: `www.canalmuseum.org.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `consulting.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: News type, supported values: tzgg（通知公告）, xwdt（新闻动态）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.canalmuseum.org.cn/consulting.html`
- `target`: `/consulting/tzgg`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/canalmuseum/consulting/tzgg",
  "heat": 0,
  "location": "consulting.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "NEWS",
  "parameters": {
    "type": "News type, supported values: tzgg（通知公告）, xwdt（新闻动态）"
  },
  "path": "/consulting/:type",
  "radar": [
    {
      "source": [
        "www.canalmuseum.org.cn/consulting.html"
      ],
      "target": "/consulting/tzgg"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:541:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
