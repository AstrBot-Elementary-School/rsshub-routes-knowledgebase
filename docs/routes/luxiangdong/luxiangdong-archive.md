# 土猛的员外 - 文章

## Coverage
`index-only`

## Route
- Namespace: `luxiangdong`
- Namespace Name: `土猛的员外`
- Route Path: `/luxiangdong/archive`
- Route Name: `文章`
- Example: `/luxiangdong/archive`
- URL: `luxiangdong.com/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Levix`
- Source Location: `archive.ts`
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
  - `luxiangdong.com/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/luxiangdong/archive",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 40,
  "location": "archive.ts",
  "maintainers": [
    "Levix"
  ],
  "name": "文章",
  "parameters": {},
  "path": "/archive",
  "radar": [
    {
      "source": [
        "luxiangdong.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 381745298660 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "土猛的员外 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62760380474850306",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.luxiangdong.com/",
      "title": "土猛的员外",
      "type": "feed",
      "url": "rsshub://luxiangdong/archive"
    }
  ],
  "url": "luxiangdong.com/"
}
```
