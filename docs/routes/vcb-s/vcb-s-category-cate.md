# VCB-Studio - 分类文章

## Coverage
`index-only`

## Route
- Namespace: `vcb-s`
- Namespace Name: `VCB-Studio`
- Route Path: `/vcb-s/category/:cate`
- Route Name: `分类文章`
- Example: `/vcb-s/category/works`
- URL: `vcb-s.com/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `cxfksword`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 作品项目 | 科普系列 | 计划与日志 |
| -------- | -------- | ---------- |
| works    | kb       | planlog    |

## Parameters
- `cate`: 分类


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
  - `vcb-s.com/archives/category/:cate`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 作品项目 | 科普系列 | 计划与日志 |\n| -------- | -------- | ---------- |\n| works    | kb       | planlog    |",
  "example": "/vcb-s/category/works",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 72,
  "location": "category.ts",
  "maintainers": [
    "cxfksword"
  ],
  "name": "分类文章",
  "parameters": {
    "cate": "分类"
  },
  "path": "/category/:cate",
  "radar": [
    {
      "source": [
        "vcb-s.com/archives/category/:cate"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "作品项目 | VCB-Studio - Powered by RSSHub",
      "errorAt": "2025-10-22T23:44:19.894Z",
      "errorMessage": "[GET] \"https://vcb-s.com/wp-json/wp/v2/categories?slug=works\": 403 Forbidden\n[GET] \"https://vcb-s.com/wp-json/wp/v2/categories?slug=works\": 403 Forbidden\n",
      "id": "58936907408117760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vcb-s.com/archives/category/works",
      "title": "作品项目 | VCB-Studio",
      "type": "feed",
      "url": "rsshub://vcb-s/category/works"
    }
  ],
  "url": "vcb-s.com/"
}
```
