# Foresight News - 文章

## Coverage
`index-only`

## Route
- Namespace: `foresightnews`
- Namespace Name: `Foresight News`
- Route Path: `/foresightnews/article`
- Route Name: `文章`
- Example: `/foresightnews/article`
- URL: `foresightnews.pro/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `foresightnews.pro/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/foresightnews/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 167,
  "location": "article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {},
  "path": "/article",
  "radar": [
    {
      "source": [
        "foresightnews.pro/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "文章 - Foresight News - Powered by RSSHub",
      "errorAt": "2026-03-25T07:02:11.981Z",
      "errorMessage": "[GET] \"https://api.foresightnews.pro/v1/articles?size=50\": 403 Forbidden\n[GET] \"https://api.foresightnews.pro/v1/articles?size=50\": 403 Forbidden\n",
      "id": "41756159863260160",
      "image": "https://img.foresightnews.pro/vertical_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://foresightnews.pro/",
      "title": "Foresight News - 文章",
      "type": "feed",
      "url": "rsshub://foresightnews/article"
    }
  ],
  "url": "foresightnews.pro/"
}
```
