# 国家金融与发展实验室 - 研究

## Coverage
`index-only`

## Route
- Namespace: `nifd`
- Namespace Name: `国家金融与发展实验室`
- Route Path: `/nifd/research/:categoryGuid?`
- Route Name: `研究`
- Example: `/nifd/research/3333d2af-91d6-429b-be83-28b92f31b6d7`
- URL: `www.nifd.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Fatpandac`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
资讯类型可以从网址中获取，如：

`http://www.nifd.cn/Research?categoryGuid=7a6a826d-b525-42aa-b550-4236e524227f` 对应 `/nifd/research/7a6a826d-b525-42aa-b550-4236e524227f`

## Parameters
- `categoryGuid`: 资讯类型，默认为周报


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
    "finance"
  ],
  "description": "资讯类型可以从网址中获取，如：\n\n`http://www.nifd.cn/Research?categoryGuid=7a6a826d-b525-42aa-b550-4236e524227f` 对应 `/nifd/research/7a6a826d-b525-42aa-b550-4236e524227f`",
  "example": "/nifd/research/3333d2af-91d6-429b-be83-28b92f31b6d7",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 258,
  "location": "research.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "研究",
  "parameters": {
    "categoryGuid": "资讯类型，默认为周报"
  },
  "path": "/research/:categoryGuid?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "国家金融与发展实验室 - 周报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61390495051089949",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.nifd.cn/Research?categoryGuid=7a6a826d-b525-42aa-b550-4236e524227f",
      "title": "国家金融与发展实验室 - 周报",
      "type": "feed",
      "url": "rsshub://nifd/research"
    },
    {
      "description": "国家金融与发展实验室 - 研究评价 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59463782891658240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.nifd.cn/Research?categoryGuid=3333d2af-91d6-429b-be83-28b92f31b6d7",
      "title": "国家金融与发展实验室 - 研究评价",
      "type": "feed",
      "url": "rsshub://nifd/research/3333d2af-91d6-429b-be83-28b92f31b6d7"
    }
  ]
}
```
