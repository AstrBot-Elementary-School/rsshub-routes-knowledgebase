# 来漫画 - 漫画列表

## Coverage
`index-only`

## Route
- Namespace: `laimanhua`
- Namespace Name: `来漫画`
- Route Path: `/laimanhua/:id`
- Route Name: `漫画列表`
- Example: `/laimanhua/tiandikangzhanjiVERSUS`
- URL: `www.laimanhua8.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 漫画 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.laimanhua8.com/kanmanhua/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/laimanhua/tiandikangzhanjiVERSUS",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "漫画列表",
  "parameters": {
    "id": "漫画 ID，可在 URL 中找到"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "www.laimanhua8.com/kanmanhua/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "“这是讲述一个少年在亚热带群岛成为大富翁的故事——”JOJO的奇妙冒险第9部TheJOJOLands拉开帷幕！... - Powered by RSSHub",
      "errorAt": "2024-10-24T07:30:38.793Z",
      "errorMessage": "[GET] \"https://www.laimanhua8.com/kanmanhua/JOJOdeqimiaomaoxianPrat9TheJOJOLands/\": <no response> fetch failed\n",
      "id": "69610589133400064",
      "image": "https://p.miyeye.cn/mh160xiaotuku/2023-07/20/202372031631373.jpg@!180x240",
      "ownerUserId": null,
      "siteUrl": "https://www.laimanhua8.com/kanmanhua/JOJOdeqimiaomaoxianPrat9TheJOJOLands/",
      "title": "JOJO的奇妙冒险Prat9 The JOJO Lands - 来漫画",
      "type": "feed",
      "url": "rsshub://laimanhua/JOJOdeqimiaomaoxianPrat9TheJOJOLands"
    },
    {
      "description": "欢迎广大爱漫画者光临漫画160网在线观看【天敌抗战记VERSUS】漫画。 - Powered by RSSHub",
      "errorAt": "2025-02-10T17:19:15.896Z",
      "errorMessage": "[GET] \"https://www.laimanhua8.com/kanmanhua/tiandikangzhanjiVERSUS/\": <no response> fetch failed\n",
      "id": "54911563273819136",
      "image": "https://p.kunyun8.com/mh160xiaotuku/2022-11/27/202211270941902.jpg@!180x240",
      "ownerUserId": null,
      "siteUrl": "https://www.laimanhua8.com/kanmanhua/tiandikangzhanjiVERSUS/",
      "title": "天敌抗战记VERSUS - 来漫画",
      "type": "feed",
      "url": "rsshub://laimanhua/tiandikangzhanjiVERSUS"
    }
  ]
}
```
