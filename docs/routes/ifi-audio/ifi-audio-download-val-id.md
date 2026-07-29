# iFi audio - Download Hub

## Coverage
`index-only`

## Route
- Namespace: `ifi-audio`
- Namespace Name: `iFi audio`
- Route Path: `/ifi-audio/download/:val/:id`
- Route Name: `Download Hub`
- Example: `/ifi-audio/download/1503007035/44472`
- URL: `ifi-audio.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `IvanWng97`
- Source Location: `download.ts`
- Source Module: `_None_`

## Description
::: warning

1. Open <https://ifi-audio.com/download-hub> and the Network panel
2. Select the device and the corresponding serial number in the website and click Search
3. Find the last request named `https://ifi-audio.com/wp-admin/admin-ajax.php` in the Network panel, find out the val and id in the Payload panel, and fill in the url

:::

## Parameters
- `val`: product val
- `id`: product id


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
    "program-update"
  ],
  "description": "::: warning\n\n1. Open <https://ifi-audio.com/download-hub> and the Network panel\n2. Select the device and the corresponding serial number in the website and click Search\n3. Find the last request named `https://ifi-audio.com/wp-admin/admin-ajax.php` in the Network panel, find out the val and id in the Payload panel, and fill in the url\n\n:::",
  "example": "/ifi-audio/download/1503007035/44472",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "download.ts",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Download Hub",
  "parameters": {
    "id": "product id",
    "val": "product val"
  },
  "path": "/download/:val/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
