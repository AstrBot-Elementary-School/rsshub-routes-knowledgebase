# NEW 字幕组 - 指定剧集

## Coverage
`index-only`

## Route
- Namespace: `newzmz`
- Namespace Name: `NEW 字幕组`
- Route Path: `/newzmz/:id?/:downLinkType?`
- Route Name: `指定剧集`
- Example: `/newzmz/qEzRyY3v`
- URL: `newzmz.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
[雪国列车 (剧版)](https://nzmz.xyz/details-qEzRyY3v.html) 的下载页 URL 为 `https://v.ys99.xyz/view/qEzRyY3v.html`，即剧集 id 为 `qEzRyY3v`
:::

## Parameters
- `id`: 剧集 id，可在剧集下载页 URL 中找到
- `downLinkType`: 下载链接类型，默认为磁力链


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
  - `newzmz.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n[雪国列车 (剧版)](https://nzmz.xyz/details-qEzRyY3v.html) 的下载页 URL 为 `https://v.ys99.xyz/view/qEzRyY3v.html`，即剧集 id 为 `qEzRyY3v`\n:::",
  "example": "/newzmz/qEzRyY3v",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "指定剧集",
  "parameters": {
    "downLinkType": "下载链接类型，默认为磁力链",
    "id": "剧集 id，可在剧集下载页 URL 中找到"
  },
  "path": "/:id?/:downLinkType?",
  "radar": [
    {
      "source": [
        "newzmz.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Redirecting... - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "133788689281561656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nzmz.xyz/index.html",
      "title": "Redirecting...",
      "type": "feed",
      "url": "rsshub://newzmz"
    }
  ],
  "url": "newzmz.com/"
}
```
