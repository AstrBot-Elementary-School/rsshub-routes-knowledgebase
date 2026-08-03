# Telegram - Sticker Pack

## Coverage
`index-only`

## Route
- Namespace: `telegram`
- Namespace Name: `Telegram`
- Route Path: `/telegram/stickerpack/:name`
- Route Name: `Sticker Pack`
- Example: `/telegram/stickerpack/DIYgod`
- URL: `t.me`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `stickerpack.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: Sticker Pack name, available in the sharing URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/telegram/stickerpack/DIYgod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 362,
  "location": "stickerpack.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Sticker Pack",
  "parameters": {
    "name": "Sticker Pack name, available in the sharing URL"
  },
  "path": "/stickerpack/:name",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "哥哥奖励自己一下 @DoO_o - Telegram Sticker Pack - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62283323384780800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t.me/addstickers/DoO_o",
      "title": "哥哥奖励自己一下 @DoO_o - Telegram Sticker Pack",
      "type": "feed",
      "url": "rsshub://telegram/stickerpack/DoO_o"
    },
    {
      "description": "人气偶像DIYgod - Telegram Sticker Pack - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59261171820798976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t.me/addstickers/DIYgod",
      "title": "人气偶像DIYgod - Telegram Sticker Pack",
      "type": "feed",
      "url": "rsshub://telegram/stickerpack/DIYgod"
    }
  ],
  "view": 2
}
```
