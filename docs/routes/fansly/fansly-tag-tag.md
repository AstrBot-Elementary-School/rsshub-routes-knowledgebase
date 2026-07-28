# Fansly - Hashtag

## Coverage
`index-only`

## Route
- Namespace: `fansly`
- Namespace Name: `Fansly`
- Route Path: `/fansly/tag/:tag`
- Route Name: `Hashtag`
- Example: `/fansly/tag/free`
- URL: `fansly.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Hashtag


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
  - `fansly.com/explore/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/fansly/tag/free",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "tag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Hashtag",
  "parameters": {
    "tag": "Hashtag"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "fansly.com/explore/tag/:tag"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "#china - Fansly - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79121801531701248",
      "image": "https://fansly.com/assets/images/icons/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://fansly.com/explore/tag/china",
      "title": "#china - Fansly",
      "type": "feed",
      "url": "rsshub://fansly/tag/china"
    },
    {
      "description": "#asian - Fansly - Powered by RSSHub",
      "errorAt": "2026-07-05T14:06:55.195Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "79119861632400384",
      "image": "https://fansly.com/assets/images/icons/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://fansly.com/explore/tag/asian",
      "title": "#asian - Fansly",
      "type": "feed",
      "url": "rsshub://fansly/tag/asian"
    }
  ]
}
```
