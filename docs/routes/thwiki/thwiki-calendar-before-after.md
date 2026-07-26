# THBWiki - Calendar

## Coverage
`index-only`

## Route
- Namespace: `thwiki`
- Namespace Name: `THBWiki`
- Route Path: `/thwiki/calendar/:before?/:after?`
- Route Name: `Calendar`
- Example: `/thwiki/calendar`
- URL: `thwiki.cc/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `aether17`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `before`: From how many days ago (default 30)
- `after`: To how many days after (default 30)


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
  - `thwiki.cc/`
  - `thwiki.cc/日程表`
- `target`: `/calendar`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/thwiki/calendar",
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
    "aether17"
  ],
  "name": "Calendar",
  "parameters": {
    "after": "To how many days after (default 30)",
    "before": "From how many days ago (default 30)"
  },
  "path": "/calendar/:before?/:after?",
  "radar": [
    {
      "source": [
        "thwiki.cc/",
        "thwiki.cc/日程表"
      ],
      "target": "/calendar"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "A Touhou related events calendar api from THBWiki - Powered by RSSHub",
      "errorAt": "2026-05-29T02:41:59.767Z",
      "errorMessage": "[GET] \"https://calendar-serverless.thwiki.cc/api/events/2026-06-25/2026-08-24\": <no response> fetch failed (60B4C9C150F70000:error:0A000410:SSL routines:ssl3_read_bytes:ssl/tls alert handshake failure:../deps/openssl/openssl/ssl/record/rec_layer_s3.c:918:SSL alert number 40\n)\n[GET] \"https://calendar-serverless.thwiki.cc/api/events/2026-06-25/2026-08-24\": <no response> fetch failed (C03210D7557F0000:error:0A000410:SSL routines:ssl3_read_bytes:ssl/tls alert handshake failure:../deps/openssl/openssl/ssl/record/rec_layer_s3.c:918:SSL alert number 40\n)\n",
      "id": "60280539896619008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://calendar.thwiki.cc/",
      "title": "Touhou events calendar (THBWiki)",
      "type": "feed",
      "url": "rsshub://thwiki/calendar"
    }
  ],
  "url": "thwiki.cc/"
}
```
