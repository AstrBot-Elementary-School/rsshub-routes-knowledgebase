# Rule34Video - Latest Updates

## Coverage
`index-only`

## Route
- Namespace: `rule34video`
- Namespace Name: `Rule34Video`
- Route Path: `/rule34video/latest`
- Route Name: `Latest Updates`
- Example: `/rule34video/latest`
- URL: `rule34video.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `ashi-koki`
- Source Location: `latest.ts`
- Source Module: `_None_`

## Description
Latest updates from Rule34 Video

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `rule34video.com/latest-updates/`
- `target`: `/latest`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Latest updates from Rule34 Video",
  "example": "/rule34video/latest",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "latest.ts",
  "maintainers": [
    "ashi-koki"
  ],
  "name": "Latest Updates",
  "path": "/latest",
  "radar": [
    {
      "source": [
        "rule34video.com/latest-updates/"
      ],
      "target": "/latest"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Latest updates from Rule34 Video - Powered by RSSHub",
      "errorAt": "2026-08-18T23:12:57.368Z",
      "errorMessage": "[GET] \"https://www.rule34video.com/latest-updates/\": 502 Bad Gateway\n",
      "id": "1094754492298952704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.rule34video.com/latest-updates/",
      "title": "Rule34 Video Latest Updates",
      "type": "feed",
      "url": "rsshub://rule34video/latest"
    }
  ]
}
```
