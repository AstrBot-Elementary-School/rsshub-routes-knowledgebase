# 哔哩轻小说 - 卷

## Coverage
`index-only`

## Route
- Namespace: `linovelib`
- Namespace Name: `哔哩轻小说`
- Route Path: `/linovelib/volume/:id`
- Route Name: `卷`
- Example: `/linovelib/volume/8`
- URL: `linovelib.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `rkscv`
- Source Location: `volume.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 ID，可在小说页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.linovelib.com/novel/:id/catalog`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/linovelib/volume/8",
  "heat": 39,
  "location": "volume.ts",
  "maintainers": [
    "rkscv"
  ],
  "name": "卷",
  "parameters": {
    "id": "小说 ID，可在小说页 URL 中找到"
  },
  "path": "/volume/:id",
  "radar": [
    {
      "source": [
        "www.linovelib.com/novel/:id/catalog"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "魔法禁书目录 - 哔哩轻小说 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126699050007148544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linovelib.com/novel/824/catalog",
      "title": "魔法禁书目录 - 哔哩轻小说",
      "type": "feed",
      "url": "rsshub://linovelib/volume/824"
    },
    {
      "description": "败北女角太多了！ - 哔哩轻小说 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58014655249591296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linovelib.com/novel/3095/catalog",
      "title": "败北女角太多了！ - 哔哩轻小说",
      "type": "feed",
      "url": "rsshub://linovelib/volume/3095"
    }
  ]
}
```
