# 上海大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/shu/gs/:type?`
- Route Name: `研究生院`
- Example: `/shu/gs/zhxw`
- URL: `gs.shu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `GhhG123`
- Source Location: `gs.ts`
- Source Module: `_None_`

## Description
| 综合新闻 | 培养管理 | 国际交流 |
| -------- | -------- | -------- |
| zhxw     | pygl     | gjjl     |

## Parameters
- `type`: 分类，默认为学术公告


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
  - `gs.shu.edu.cn/`
- `target`: `/gs`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 综合新闻 | 培养管理 | 国际交流 |\n| -------- | -------- | -------- |\n| zhxw     | pygl     | gjjl     |",
  "example": "/shu/gs/zhxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "gs.ts",
  "maintainers": [
    "GhhG123"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "分类，默认为学术公告"
  },
  "path": "/gs/:type?",
  "radar": [
    {
      "source": [
        "gs.shu.edu.cn/"
      ],
      "target": "/gs"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海大学研究生院-培养管理 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84822123215592448",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://gs.shu.edu.cn/xwlb/py.htm",
      "title": "上海大学研究生院-培养管理",
      "type": "feed",
      "url": "rsshub://shu/gs/pygl"
    },
    {
      "description": "上海大学研究生院-国际交流 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84824362495888384",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://gs.shu.edu.cn/xwlb/gjjl.htm",
      "title": "上海大学研究生院-国际交流",
      "type": "feed",
      "url": "rsshub://shu/gs/gjjl"
    }
  ],
  "url": "gs.shu.edu.cn/"
}
```
