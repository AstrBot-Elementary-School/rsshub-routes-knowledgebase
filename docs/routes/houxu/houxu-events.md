# 后续 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `houxu`
- Namespace Name: `后续`
- Route Path: `/houxu/events`
- Route Name: `专栏`
- Example: `/houxu/events`
- URL: `houxu.app/events`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `events.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `houxu.app/events`
  - `houxu.app/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/houxu/events",
  "heat": 5,
  "location": "events.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专栏",
  "path": "/events",
  "radar": [
    {
      "source": [
        "houxu.app/events",
        "houxu.app/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "后续 - 专栏 - Powered by RSSHub",
      "errorAt": "2025-12-22T09:59:52.300Z",
      "errorMessage": "[GET] \"https://houxu.app/api/1/events?limit=50\": <no response> fetch failed (redirect count exceeded)\n",
      "id": "66319032172271616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://houxu.app/events",
      "title": "后续 - 专栏",
      "type": "feed",
      "url": "rsshub://houxu/events"
    }
  ],
  "url": "houxu.app/events"
}
```
