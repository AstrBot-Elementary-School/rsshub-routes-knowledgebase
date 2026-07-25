# 技术头条 - 最新文章

## Coverage
`index-only`

## Route
- Namespace: `blogread`
- Namespace Name: `技术头条`
- Route Path: `/blogread/newest`
- Route Name: `最新文章`
- Example: `/blogread/newest`
- URL: `blogread.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `fashioncj`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `blogread.cn/news/newest.php`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/blogread/newest",
  "heat": 347,
  "location": "index.ts",
  "maintainers": [
    "fashioncj"
  ],
  "name": "最新文章",
  "path": "/newest",
  "radar": [
    {
      "source": [
        "blogread.cn/news/newest.php"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "技术头条 - Powered by RSSHub",
      "errorAt": "2026-01-13T07:18:16.148Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "56599674652552192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blogread.cn/news/newest.php",
      "title": "技术头条",
      "type": "feed",
      "url": "rsshub://blogread/newest"
    }
  ]
}
```
