# 湖南日报 - 电子刊物

## Coverage
`index-only`

## Route
- Namespace: `hnrb`
- Namespace Name: `湖南日报`
- Route Path: `/hnrb/:id?`
- Route Name: `电子刊物`
- Example: `/hnrb`
- URL: `voc.com.cn/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 版                   | 编号 |
| -------------------- | ---- |
| 全部                 |      |
| 第 01 版：头版       | 1    |
| 第 02 版：要闻       | 2    |
| 第 03 版：要闻       | 3    |
| 第 04 版：深度       | 4    |
| 第 05 版：市州       | 5    |
| 第 06 版：理论・学习 | 6    |
| 第 07 版：观察       | 7    |
| 第 08 版：时事       | 8    |
| 第 09 版：中缝       | 9    |

## Parameters
- `id`: 编号，见下表，默认为全部


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
  - `voc.com.cn/`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 版                   | 编号 |\n| -------------------- | ---- |\n| 全部                 |      |\n| 第 01 版：头版       | 1    |\n| 第 02 版：要闻       | 2    |\n| 第 03 版：要闻       | 3    |\n| 第 04 版：深度       | 4    |\n| 第 05 版：市州       | 5    |\n| 第 06 版：理论・学习 | 6    |\n| 第 07 版：观察       | 7    |\n| 第 08 版：时事       | 8    |\n| 第 09 版：中缝       | 9    |",
  "example": "/hnrb",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "电子刊物",
  "parameters": {
    "id": "编号，见下表，默认为全部"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "voc.com.cn/"
      ],
      "target": "/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "湖南日报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75409322850391040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hnrb.voc.com.cn/hnrb_epaper",
      "title": "湖南日报",
      "type": "feed",
      "url": "rsshub://hnrb"
    },
    {
      "description": "湖南日报 - 第01版：头版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81619059516564480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hnrb.voc.com.cn/hnrb_epaper",
      "title": "湖南日报 - 第01版：头版",
      "type": "feed",
      "url": "rsshub://hnrb/1"
    }
  ],
  "url": "voc.com.cn/"
}
```
