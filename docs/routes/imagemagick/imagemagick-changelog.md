# ImageMagick - Changelog

## Coverage
`index-only`

## Route
- Namespace: `imagemagick`
- Namespace Name: `ImageMagick`
- Route Path: `/imagemagick/changelog`
- Route Name: `Changelog`
- Example: `/imagemagick/changelog`
- URL: `imagemagick.org/script/download.php`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changelog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `imagemagick.org/script/download.php`
  - `imagemagick.org/script`
  - `imagemagick.org/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/imagemagick/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "changelog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Changelog",
  "parameters": {},
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "imagemagick.org/script/download.php",
        "imagemagick.org/script",
        "imagemagick.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ImageMagick - ChangeLog - Powered by RSSHub",
      "errorAt": "2026-07-08T01:20:29.008Z",
      "errorMessage": "[GET] \"https://raw.githubusercontent.com/ImageMagick/Website/main/ChangeLog.md\": 404 Not Found\n",
      "id": "74365916922083328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://imagemagick.org/script/download.php",
      "title": "ImageMagick - ChangeLog",
      "type": "feed",
      "url": "rsshub://imagemagick/changelog"
    }
  ],
  "url": "imagemagick.org/script/download.php"
}
```
