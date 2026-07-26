# 南开大学 - 计算机学院

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/cc/:type?`
- Route Name: `计算机学院`
- Example: `/nankai/cc/13291`
- URL: `cc.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `vicguo0724`
- Source Location: `cc-notice.ts`
- Source Module: `_None_`

## Description
| 最新动态 | 学院公告 | 学生工作通知 | 科研信息 | 本科生教学 | 党团园地 | 研究生招生 | 研究生教学 | 境外交流 |
| -------- | -------- | ------------ | -------- | ---------- | -------- | ---------- | ---------- | -------- |
| 13291    | 13292    | 13293        | 13294    | 13295      | 13296    | 13297      | 13298      | 13299    |

## Parameters
- `type`: 栏目编号（若为空则默认为"最新动态"）


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
  - `cc.nankai.edu.cn`
  - `cc.nankai.edu.cn/:type/list.htm`
- `target`: `/cc/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 最新动态 | 学院公告 | 学生工作通知 | 科研信息 | 本科生教学 | 党团园地 | 研究生招生 | 研究生教学 | 境外交流 |\n| -------- | -------- | ------------ | -------- | ---------- | -------- | ---------- | ---------- | -------- |\n| 13291    | 13292    | 13293        | 13294    | 13295      | 13296    | 13297      | 13298      | 13299    |",
  "example": "/nankai/cc/13291",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "cc-notice.ts",
  "maintainers": [
    "vicguo0724"
  ],
  "name": "计算机学院",
  "parameters": {
    "type": "栏目编号（若为空则默认为\"最新动态\"）"
  },
  "path": "/cc/:type?",
  "radar": [
    {
      "source": [
        "cc.nankai.edu.cn",
        "cc.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/cc/:type?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "南开大学计算机学院-学院公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168824709558666240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cc.nankai.edu.cn/13292/list.htm",
      "title": "南开大学计算机学院-学院公告",
      "type": "feed",
      "url": "rsshub://nankai/cc/13292"
    },
    {
      "description": "南开大学计算机学院-科研信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168826180092668928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cc.nankai.edu.cn/13294/list.htm",
      "title": "南开大学计算机学院-科研信息",
      "type": "feed",
      "url": "rsshub://nankai/cc/13294"
    }
  ],
  "url": "cc.nankai.edu.cn"
}
```
