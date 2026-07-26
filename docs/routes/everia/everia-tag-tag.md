# EVERIA.CLUB - Images with tag

## Coverage
`index-only`

## Route
- Namespace: `everia`
- Namespace Name: `EVERIA.CLUB`
- Route Path: `/everia/tag/:tag`
- Route Name: `Images with tag`
- Example: `/everia/tag/hinatazaka46-日向坂46`
- URL: `everia.club`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KTachibanaM, AiraNadih`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag of the image stream


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
  - `everia.club/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/everia/tag/hinatazaka46-日向坂46",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "tag.ts",
  "maintainers": [
    "KTachibanaM",
    "AiraNadih"
  ],
  "name": "Images with tag",
  "parameters": {
    "tag": "Tag of the image stream"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "everia.club/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "EVERIA.CLUB - Tag: gravure - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "153059637668516864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://everia.club/tag/gravure/",
      "title": "EVERIA.CLUB - Tag: gravure",
      "type": "feed",
      "url": "rsshub://everia/tag/gravure"
    },
    {
      "description": "EVERIA.CLUB - Tag: hinatazaka46-日向坂46 - Powered by RSSHub",
      "errorAt": "2026-06-17T02:28:19.716Z",
      "errorMessage": "Failed to fetch\n",
      "id": "153295667919122432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://everia.club/tag/hinatazaka46-%E6%97%A5%E5%90%91%E5%9D%8246/",
      "title": "EVERIA.CLUB - Tag: hinatazaka46-日向坂46",
      "type": "feed",
      "url": "rsshub://everia/tag/hinatazaka46-%E6%97%A5%E5%90%91%E5%9D%8246"
    }
  ]
}
```
