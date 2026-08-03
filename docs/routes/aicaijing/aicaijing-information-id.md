# AI 财经社 - 热点 & 深度

## Coverage
`index-only`

## Route
- Namespace: `aicaijing`
- Namespace Name: `AI 财经社`
- Route Path: `/aicaijing/information/:id?`
- Route Name: `热点 & 深度`
- Example: `/aicaijing/information/14`
- URL: `www.aicaijing.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `information.ts`
- Source Module: `_None_`

## Description
| 栏目 id | 栏目        |
| ------- | ----------- |
| 14      | 热点 - 最新 |
| 5       | 热点 - 科技 |
| 9       | 热点 - 消费 |
| 7       | 热点 - 出行 |
| 13      | 热点 - 文娱 |
| 10      | 热点 - 教育 |
| 25      | 热点 - 地产 |
| 11      | 热点 - 更多 |
| 28      | 深度 - 出行 |
| 29      | 深度 - 科技 |
| 31      | 深度 - 消费 |
| 33      | 深度 - 教育 |
| 34      | 深度 - 更多 |
| 8       | 深度 - 地产 |
| 6       | 深度 - 文娱 |

## Parameters
- `id`: 栏目 id，可在对应栏目页 URL 中找到，默认为 14，即热点最新


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.aicaijing.com/information/:id`
  - `www.aicaijing.com/`
- `target`: `/information/:id?`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 栏目 id | 栏目        |\n| ------- | ----------- |\n| 14      | 热点 - 最新 |\n| 5       | 热点 - 科技 |\n| 9       | 热点 - 消费 |\n| 7       | 热点 - 出行 |\n| 13      | 热点 - 文娱 |\n| 10      | 热点 - 教育 |\n| 25      | 热点 - 地产 |\n| 11      | 热点 - 更多 |\n| 28      | 深度 - 出行 |\n| 29      | 深度 - 科技 |\n| 31      | 深度 - 消费 |\n| 33      | 深度 - 教育 |\n| 34      | 深度 - 更多 |\n| 8       | 深度 - 地产 |\n| 6       | 深度 - 文娱 |",
  "example": "/aicaijing/information/14",
  "heat": 4,
  "location": "information.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "热点 & 深度",
  "parameters": {
    "id": "栏目 id，可在对应栏目页 URL 中找到，默认为 14，即热点最新"
  },
  "path": "/information/:id?",
  "radar": [
    {
      "source": [
        "www.aicaijing.com/information/:id",
        "www.aicaijing.com/"
      ],
      "target": "/information/:id?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-21T04:38:12.931Z",
      "errorMessage": "Cannot read properties of undefined (reading 'items')\n",
      "id": "147826498738685974",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://aicaijing/information/14"
    }
  ]
}
```
