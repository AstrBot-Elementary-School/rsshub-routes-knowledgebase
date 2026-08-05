# 北京师范大学 - 经济与工商管理学院

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/bnu/bs/:category?`
- Route Name: `经济与工商管理学院`
- Example: `/bnu/bs`
- URL: `bs.bnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `bs.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 通知公告 | 学术成果 | 学术讲座 | 教师观点 | 人才招聘 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| xw       | zytzyyg  | xzcg     | xzjz     | xz       | bshzs    |

## Parameters
- `category`: 分类，见下表，默认为学院新闻


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
  - `bs.bnu.edu.cn/:category/index.html`
- `target`: `/bs/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 | 学术成果 | 学术讲座 | 教师观点 | 人才招聘 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| xw       | zytzyyg  | xzcg     | xzjz     | xz       | bshzs    |",
  "example": "/bnu/bs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "bs.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "经济与工商管理学院",
  "parameters": {
    "category": "分类，见下表，默认为学院新闻"
  },
  "path": "/bs/:category?",
  "radar": [
    {
      "source": [
        "bs.bnu.edu.cn/:category/index.html"
      ],
      "target": "/bs/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "学术讲座 - 北京师范大学经济与工商管理学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1166224525281329152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://bs.bnu.edu.cn/xzjz/index.html",
      "title": "学术讲座 - 北京师范大学经济与工商管理学院",
      "type": "feed",
      "url": "rsshub://bnu/bs/xzjz"
    },
    {
      "description": "学院新闻 - 北京师范大学经济与工商管理学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1121871309890781184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://bs.bnu.edu.cn/xw/index.html",
      "title": "学院新闻 - 北京师范大学经济与工商管理学院",
      "type": "feed",
      "url": "rsshub://bnu/bs/xw"
    }
  ]
}
```
