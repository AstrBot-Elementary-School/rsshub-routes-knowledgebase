# 中国科学学与科技政策研究会 - 研究会动态

## Coverage
`index-only`

## Route
- Namespace: `casssp`
- Namespace Name: `中国科学学与科技政策研究会`
- Route Path: `/casssp/news/:category?`
- Route Name: `研究会动态`
- Example: `/casssp/news/3`
- URL: `casssp.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻动态 | 信息公开 | 时政要闻 |
| -------- | -------- | -------- | -------- |
| 3        | 2        | 92       | 93       |

## Parameters
- `category`: 分类，见下表，默认为通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 | 新闻动态 | 信息公开 | 时政要闻 |\n| -------- | -------- | -------- | -------- |\n| 3        | 2        | 92       | 93       |",
  "example": "/casssp/news/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "研究会动态",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/news/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "研究会动态_中国科学学与科技政策研究会-中国科技智库论坛-全球科技论坛研究-Innovation and Development Policy - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72252117071751168",
      "image": "https://omo-oss-image.thefastimg.com/portal-saas/new2023070812263819729/cms/image/edee1b0f-7d7b-495f-aa52-8e58f483d35b.png",
      "ownerUserId": null,
      "siteUrl": "http://www.casssp.org.cn/news/3/",
      "title": "通知公告_中国科学学与科技政策研究会-中国科技智库论坛-全球科技论坛研究-Innovation and Development Policy",
      "type": "feed",
      "url": "rsshub://casssp/news/3"
    }
  ]
}
```
