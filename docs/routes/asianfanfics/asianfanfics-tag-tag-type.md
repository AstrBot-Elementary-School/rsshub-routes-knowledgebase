# Asianfanfics - 标签

## Coverage
`index-only`

## Route
- Namespace: `asianfanfics`
- Namespace Name: `Asianfanfics`
- Route Path: `/asianfanfics/tag/:tag/:type`
- Route Name: `标签`
- Example: `/asianfanfics/tag/milklove/N`
- URL: `asianfanfics.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `KazooTTT`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
匹配 asianfanfics 标签，支持排序类型：

- L: Latest 最近更新
- N: Newest 最近发布
- O: Oldest 最早发布
- C: Completed 已完成
- OS: One Shots 短篇

## Parameters
- `tag`: 标签
- `type`: 排序类型


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.asianfanfics.com/browse/tag/:tag/:type`
- `target`: `/tag/:tag/:type`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "匹配 asianfanfics 标签，支持排序类型：\n\n- L: Latest 最近更新\n- N: Newest 最近发布\n- O: Oldest 最早发布\n- C: Completed 已完成\n- OS: One Shots 短篇",
  "example": "/asianfanfics/tag/milklove/N",
  "heat": 6,
  "location": "tag.ts",
  "maintainers": [
    "KazooTTT"
  ],
  "name": "标签",
  "parameters": {
    "tag": "标签",
    "type": "排序类型"
  },
  "path": "/tag/:tag/:type",
  "radar": [
    {
      "source": [
        "www.asianfanfics.com/browse/tag/:tag/:type"
      ],
      "target": "/tag/:tag/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Asianfanfics - 标签：milklove - 最近发布 - Powered by RSSHub",
      "errorAt": "2025-11-26T14:54:57.893Z",
      "errorMessage": "[GET] \"https://www.asianfanfics.com/browse/tag/milklove/N\": 403 Forbidden\n",
      "id": "119960006927534080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.asianfanfics.com/browse/tag/milklove/N",
      "title": "Asianfanfics - 标签：milklove - 最近发布",
      "type": "feed",
      "url": "rsshub://asianfanfics/tag/milklove/N"
    },
    {
      "description": "Asianfanfics - 标签：milklove - 最近更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "166623961063498752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.asianfanfics.com/browse/tag/milklove/L",
      "title": "Asianfanfics - 标签：milklove - 最近更新",
      "type": "feed",
      "url": "rsshub://asianfanfics/tag/milklove/L"
    }
  ]
}
```
