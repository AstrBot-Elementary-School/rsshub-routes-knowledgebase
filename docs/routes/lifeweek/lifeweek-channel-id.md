# 三联生活周刊 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `lifeweek`
- Namespace Name: `三联生活周刊`
- Route Path: `/lifeweek/channel/:id`
- Route Name: `栏目`
- Example: `/lifeweek/channel/9`
- URL: `lifeweek.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `changren-wcr`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
提取文章全文，获得更好的阅读体验。支持所有频道，频道名称见 [杂志栏目](https://www.lifeweek.com.cn/classify?type=2)。例如 [调查栏目](https://www.lifeweek.com.cn/column/9) URL 最后的数字为栏目 ID

| 调查 | 热点 | 人物 | 社会 | 经济 | 文化 |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 9    | 6    | 10   | 2    | 3    | 4    |

## Parameters
- `id`: 栏目 ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lifeweek.com.cn/column/:channel`
- `target`: `/channel/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "提取文章全文，获得更好的阅读体验。支持所有频道，频道名称见 [杂志栏目](https://www.lifeweek.com.cn/classify?type=2)。例如 [调查栏目](https://www.lifeweek.com.cn/column/9) URL 最后的数字为栏目 ID\n\n| 调查 | 热点 | 人物 | 社会 | 经济 | 文化 |\n| ---- | ---- | ---- | ---- | ---- | ---- |\n| 9    | 6    | 10   | 2    | 3    | 4    |",
  "example": "/lifeweek/channel/9",
  "heat": 138,
  "location": "channel.ts",
  "maintainers": [
    "changren-wcr"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 ID"
  },
  "path": "/channel/:id",
  "radar": [
    {
      "source": [
        "lifeweek.com.cn/column/:channel"
      ],
      "target": "/channel/:channel"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "文化 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74705665643397120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/column/4",
      "title": "文化",
      "type": "feed",
      "url": "rsshub://lifeweek/channel/4"
    },
    {
      "description": "经济 - Powered by RSSHub",
      "errorAt": "2026-08-02T07:40:18.219Z",
      "errorMessage": "[GET] \"https://www.lifeweek.com.cn/api/userWebFollow/getFollowTagContentList?type=3&sort=2&tagId=3\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 60.255.154.100:443, 60.255.154.102:443, 60.255.154.103:443, 60.255.154.104:443, 60.255.154.94:443, 60.255.154.95:443, 60.255.154.96:443, 60.255.154.99:443, timeout: 10000ms))\n",
      "id": "77268471866082304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/column/3",
      "title": "经济",
      "type": "feed",
      "url": "rsshub://lifeweek/channel/3"
    }
  ]
}
```
