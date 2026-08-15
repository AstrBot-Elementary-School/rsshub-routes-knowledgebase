# LA UOSC社区 - 最热 / 最新帖子

## Coverage
`index-only`

## Route
- Namespace: `loongarch`
- Namespace Name: `LA UOSC社区`
- Route Path: `/loongarch/post/:type?`
- Route Name: `最热 / 最新帖子`
- Example: `/loongarch/post/newest`
- URL: `bbs.loongarch.org/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `ladeng07, 3401797899`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: top 或 newest


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.loongarch.org`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/loongarch/post/newest",
  "heat": 20,
  "location": "post.ts",
  "maintainers": [
    "ladeng07",
    "3401797899"
  ],
  "name": "最热 / 最新帖子",
  "parameters": {
    "type": "top 或 newest"
  },
  "path": "/post/:type?",
  "radar": [
    {
      "source": [
        "bbs.loongarch.org"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "LA UOSC-最新帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69988054872006656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.loongarch.org/api/discussions",
      "title": "LA UOSC-最新帖子",
      "type": "feed",
      "url": "rsshub://loongarch/post/newest"
    },
    {
      "description": "LA UOSC-最新帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92079131400677376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.loongarch.org/api/discussions",
      "title": "LA UOSC-最新帖子",
      "type": "feed",
      "url": "rsshub://loongarch/post"
    }
  ],
  "url": "bbs.loongarch.org/"
}
```
