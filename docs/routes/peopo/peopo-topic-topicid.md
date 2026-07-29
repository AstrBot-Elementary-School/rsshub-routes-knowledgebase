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
| 分類     | ID  |
| -------- | --- |
| 社會關懷 | 159 |
| 生態環保 | 113 |
| 文化古蹟 | 143 |
| 社區改造 | 160 |
| 教育學習 | 161 |
| 農業     | 163 |
| 生活休閒 | 162 |
| 媒體觀察 | 164 |
| 運動科技 | 165 |
| 政治經濟 | 166 |
| 北台灣   | 223 |
| 中台灣   | 224 |
| 南台灣   | 225 |
| 東台灣   | 226 |
| 校園中心 | 167 |
| 原住民族 | 227 |
| 天然災害 | 168 |

## Parameters
- `topicId`: 分類 ID，見下表，默認為社會關懷


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
  "description": "| 分類     | ID  |\n| -------- | --- |\n| 社會關懷 | 159 |\n| 生態環保 | 113 |\n| 文化古蹟 | 143 |\n| 社區改造 | 160 |\n| 教育學習 | 161 |\n| 農業     | 163 |\n| 生活休閒 | 162 |\n| 媒體觀察 | 164 |\n| 運動科技 | 165 |\n| 政治經濟 | 166 |\n| 北台灣   | 223 |\n| 中台灣   | 224 |\n| 南台灣   | 225 |\n| 東台灣   | 226 |\n| 校園中心 | 167 |\n| 原住民族 | 227 |\n| 天然災害 | 168 |",
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
    "topicId": "分類 ID，見下表，默認為社會關懷"
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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
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
