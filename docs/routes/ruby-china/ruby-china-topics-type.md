# Ruby China - 主题

## Coverage
`index-only`

## Route
- Namespace: `ruby-china`
- Namespace Name: `Ruby China`
- Route Path: `/ruby-china/topics/:type?`
- Route Name: `主题`
- Example: `/ruby-china/topics`
- URL: `ruby-china.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `ahonn`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
未登录状态下抓取页面非实时更新

| 主题类型 | type        |
| -------- | ----------- |
| 精华贴   | excellent   |
| 优质帖子 | popular     |
| 无人问津 | no\_reply   |
| 最新回复 | last\_reply |
| 最新发布 | last        |

## Parameters
- `type`: 主题类型，在 URL 可以找到


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "未登录状态下抓取页面非实时更新\n\n| 主题类型 | type        |\n| -------- | ----------- |\n| 精华贴   | excellent   |\n| 优质帖子 | popular     |\n| 无人问津 | no\\_reply   |\n| 最新回复 | last\\_reply |\n| 最新发布 | last        |",
  "example": "/ruby-china/topics",
  "heat": 7,
  "location": "topics.ts",
  "maintainers": [
    "ahonn"
  ],
  "name": "主题",
  "parameters": {
    "type": "主题类型，在 URL 可以找到"
  },
  "path": "/topics/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Ruby China - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "176986240301127682",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ruby-china.org/topics",
      "title": "Ruby China",
      "type": "feed",
      "url": "rsshub://ruby-china/topics"
    },
    {
      "description": "Ruby China - 精华贴 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "145694700490748940",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ruby-china.org/topics/excellent",
      "title": "Ruby China - 精华贴",
      "type": "feed",
      "url": "rsshub://ruby-china/topics/excellent"
    }
  ]
}
```
