# PeoPo 公民新聞 - 新聞分類

## Coverage
`index-only`

## Route
- Namespace: `peopo`
- Namespace Name: `PeoPo 公民新聞`
- Route Path: `/peopo/topic/:topicId?`
- Route Name: `新聞分類`
- Example: `/peopo/topic/159`
- URL: `peopo.org`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
預設值及範例保留為 `159`，目前對應坪林區。網站現行新聞分類如下：

| 分類     | ID |
| -------- | -- |
| 社會關懷 | 2  |
| 生態環保 | 3  |
| 文化古蹟 | 4  |
| 社區改造 | 5  |
| 教育學習 | 6  |
| 農漁畜牧 | 7  |
| 生活休閒 | 8  |
| 媒體觀察 | 9  |
| 運動科技 | 10 |
| 政治經濟 | 11 |

## Parameters
- `topicId`: 分類 ID，見下表；保留既有預設值 159，目前對應坪林區


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
  - `peopo.org/topic/:topicId`
- `target`: `/topic/:topicId`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "預設值及範例保留為 `159`，目前對應坪林區。網站現行新聞分類如下：\n\n| 分類     | ID |\n| -------- | -- |\n| 社會關懷 | 2  |\n| 生態環保 | 3  |\n| 文化古蹟 | 4  |\n| 社區改造 | 5  |\n| 教育學習 | 6  |\n| 農漁畜牧 | 7  |\n| 生活休閒 | 8  |\n| 媒體觀察 | 9  |\n| 運動科技 | 10 |\n| 政治經濟 | 11 |",
  "example": "/peopo/topic/159",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新聞分類",
  "parameters": {
    "topicId": "分類 ID，見下表；保留既有預設值 159，目前對應坪林區"
  },
  "path": "/topic/:topicId?",
  "radar": [
    {
      "source": [
        "peopo.org/topic/:topicId"
      ],
      "target": "/topic/:topicId"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "社會關懷 | PeoPo 公民新聞 - Powered by RSSHub",
      "errorAt": "2025-03-19T13:18:02.303Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "59770047912643584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.peopo.org/topic/159",
      "title": "社會關懷 | PeoPo 公民新聞",
      "type": "feed",
      "url": "rsshub://peopo/topic/159"
    }
  ]
}
```
