# Hong Kong Department of Health 香港卫生署 - Press Release

## Coverage
`index-only`

## Route
- Namespace: `hongkong`
- Namespace Name: `Hong Kong Department of Health 香港卫生署`
- Route Path: `/hongkong/dh/:language?`
- Route Name: `Press Release`
- Example: `/hongkong/dh`
- URL: `dh.gov.hk/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `dh.ts`
- Source Module: `_None_`

## Description
Language

| English | 中文简体 | 中文繁體 |
| ------- | -------- | -------- |
| english | chs      | tc\_chi  |

## Parameters
- `language`: Language, see below, tc_chi by default


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
  - `dh.gov.hk/`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Language\n\n| English | 中文简体 | 中文繁體 |\n| ------- | -------- | -------- |\n| english | chs      | tc\\_chi  |",
  "example": "/hongkong/dh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "dh.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Press Release",
  "parameters": {
    "language": "Language, see below, tc_chi by default"
  },
  "path": "/dh/:language?",
  "radar": [
    {
      "source": [
        "dh.gov.hk/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-22T09:14:09.112Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "159537064166595584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://hongkong/dh"
    }
  ],
  "url": "dh.gov.hk/"
}
```
