# InfoQ 中文 - 话题

## Coverage
`index-only`

## Route
- Namespace: `infoq`
- Namespace Name: `InfoQ 中文`
- Route Path: `/infoq/topic/:id`
- Route Name: `话题`
- Example: `/infoq/topic/1`
- URL: `infoq.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `brilon`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 话题id，可在 [InfoQ全部话题](https://www.infoq.cn/topics) 页面找到URL里的话题id


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
  - `infoq.cn/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/infoq/topic/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 474,
  "location": "topic.ts",
  "maintainers": [
    "brilon"
  ],
  "name": "话题",
  "parameters": {
    "id": "话题id，可在 [InfoQ全部话题](https://www.infoq.cn/topics) 页面找到URL里的话题id"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "infoq.cn/topic/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "关注后端工程师全栈技术演进、实践经验 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72893695848375296",
      "image": "https://static001.infoq.cn/resource/image/fc/ce/fc07f0699b9ef34258ffdb8ce33d13ce.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.infoq.cn/topic/1174",
      "title": "InfoQ 话题 - 后端",
      "type": "feed",
      "url": "rsshub://infoq/topic/1174"
    },
    {
      "description": "溯源架构发展的脉络，关注科技企业的架构实践，帮助传统行业、中小型企业找到可供参考的架构 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69942815303624704",
      "image": "https://static001.infoq.cn/resource/image/67/ea/67e54c399fce17be50ed2bd524c29aea.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.infoq.cn/topic/architecture",
      "title": "InfoQ 话题 - 架构",
      "type": "feed",
      "url": "rsshub://infoq/topic/architecture"
    }
  ]
}
```
