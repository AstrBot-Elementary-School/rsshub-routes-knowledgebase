# 广东工业大学 - 通知公文网

## Coverage
`index-only`

## Route
- Namespace: `gdut`
- Namespace Name: `广东工业大学`
- Route Path: `/gdut/oa_news/:type?`
- Route Name: `通知公文网`
- Example: `/gdut/oa_news/notice`
- URL: `oas.gdut.edu.cn/seeyon`
- Language: `_None_`
- Categories: `university`
- Maintainers: `jim-kirisame, GamerNoTitle, Richard-Zheng`
- Source Location: `oa-news.ts`
- Source Module: `_None_`

## Description
学校可能会因为 IP 来源非学校而做出一定的限制，建议在校内网络环境下使用 RSS 阅读器订阅。

| 类型     | 参数           | 可能需要校内访问 |
| -------- | -------------- | ---------------- |
| 部处简讯 | department     | 是               |
| 学院简讯 | academy        | 是               |
| 校内通知 | notice         | 是               |
| 公示公告 | announcement   | 是               |
| 招标结果 | tender\_result | 否               |
| 招标公告 | tender\_invite | 否               |

## Parameters
- `type`: 通知类型，留空则获取所有分类


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
  - `oas.gdut.edu.cn/seeyon`
- `target`: `/oa_news/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "学校可能会因为 IP 来源非学校而做出一定的限制，建议在校内网络环境下使用 RSS 阅读器订阅。\n\n| 类型     | 参数           | 可能需要校内访问 |\n| -------- | -------------- | ---------------- |\n| 部处简讯 | department     | 是               |\n| 学院简讯 | academy        | 是               |\n| 校内通知 | notice         | 是               |\n| 公示公告 | announcement   | 是               |\n| 招标结果 | tender\\_result | 否               |\n| 招标公告 | tender\\_invite | 否               |",
  "example": "/gdut/oa_news/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "oa-news.ts",
  "maintainers": [
    "jim-kirisame",
    "GamerNoTitle",
    "Richard-Zheng"
  ],
  "name": "通知公文网",
  "parameters": {
    "type": "通知类型，留空则获取所有分类"
  },
  "path": "/oa_news/:type?",
  "radar": [
    {
      "source": [
        "oas.gdut.edu.cn/seeyon"
      ],
      "target": "/oa_news/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "oas.gdut.edu.cn/seeyon"
}
```
