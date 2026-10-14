# Beijing Jiaotong University - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `bjtu`
- Namespace Name: `Beijing Jiaotong University`
- Route Path: `/bjtu/gs/:type?`
- Route Name: `研究生院`
- Example: `/bjtu/gs/noti`
- URL: `bjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `E1nzbern`
- Source Location: `gs.ts`
- Source Module: `_None_`

## Description
| 文章来源            | 参数       |
| ------------------- | ---------- |
| 通知公告\_招生      | noti\_zs   |
| 通知公告            | noti       |
| 新闻动态            | news       |
| 培养                | py         |
| 学位                | xw         |
| 博士招生 - 招生专题 | bszs\_zszt |
| 硕士招生 - 招生专题 | sszs\_zszt |
| 招生简章 - 招生专题 | zsjz\_zszt |

::: tip
文章来源的命名均来自研究生院网站标题。官网改版后，当前支持 noti\_zs、noti、news、py、xw、bszs\_zszt、sszs\_zszt 和 zsjz\_zszt；其余旧栏目没有可验证的对应列表。
最常用的几项有 “通知公告\_招生”、“通知公告”、“博士招生 - 招生专题”、“硕士招生 - 招生专题”。
:::

## Parameters
- `type`: Article type


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gs.bjtu.edu.cn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 文章来源            | 参数       |\n| ------------------- | ---------- |\n| 通知公告\\_招生      | noti\\_zs   |\n| 通知公告            | noti       |\n| 新闻动态            | news       |\n| 培养                | py         |\n| 学位                | xw         |\n| 博士招生 - 招生专题 | bszs\\_zszt |\n| 硕士招生 - 招生专题 | sszs\\_zszt |\n| 招生简章 - 招生专题 | zsjz\\_zszt |\n\n::: tip\n文章来源的命名均来自研究生院网站标题。官网改版后，当前支持 noti\\_zs、noti、news、py、xw、bszs\\_zszt、sszs\\_zszt 和 zsjz\\_zszt；其余旧栏目没有可验证的对应列表。\n最常用的几项有 “通知公告\\_招生”、“通知公告”、“博士招生 - 招生专题”、“硕士招生 - 招生专题”。\n:::",
  "example": "/bjtu/gs/noti",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "gs.ts",
  "maintainers": [
    "E1nzbern"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "Article type"
  },
  "path": "/gs/:type?",
  "radar": [
    {
      "source": [
        "gs.bjtu.edu.cn"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "通知公告 - 北京交通大学研究生院 - Powered by RSSHub",
      "errorAt": "2025-02-21T00:28:06.292Z",
      "errorMessage": "[GET] \"https://gs.bjtu.edu.cn/cms/item/?tag=2\": 404 Not Found\n",
      "id": "72292031448715264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gs.bjtu.edu.cn/cms/item/?tag=2",
      "title": "通知公告 - 北京交通大学研究生院",
      "type": "feed",
      "url": "rsshub://bjtu/gs/noti"
    }
  ]
}
```
