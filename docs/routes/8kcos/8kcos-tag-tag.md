# 8KCosplay - 标签

## Coverage
`index-only`

## Route
- Namespace: `8kcos`
- Namespace Name: `8KCosplay`
- Route Path: `/8kcos/tag/:tag`
- Route Name: `标签`
- Example: `/8kcos/tag/cosplay`
- URL: `8kcosplay.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KotoriK`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: 标签名


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
  - `8kcosplay.com/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/8kcos/tag/cosplay",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 34,
  "location": "tag.ts",
  "maintainers": [
    "KotoriK"
  ],
  "name": "标签",
  "parameters": {
    "tag": "标签名"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "8kcosplay.com/tag/:tag"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "鹿八岁 Archives - 8k Cosplay Zone - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "251905695964091392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.8kcosplay.com/tag/%E9%B9%BF%E5%85%AB%E5%B2%81/",
      "title": "鹿八岁 Archives - 8k Cosplay Zone",
      "type": "feed",
      "url": "rsshub://8kcos/tag/%E9%B9%BF%E5%85%AB%E5%B2%81"
    },
    {
      "description": "Cosplay Archives - 8k Cosplay Zone - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "251905826635286528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.8kcosplay.com/tag/cosplay/",
      "title": "Cosplay Archives - 8k Cosplay Zone",
      "type": "feed",
      "url": "rsshub://8kcos/tag/cosplay"
    }
  ],
  "url": "8kcosplay.com/"
}
```
