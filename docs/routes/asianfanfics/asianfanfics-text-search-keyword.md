# Asianfanfics - 关键词

## Coverage
`index-only`

## Route
- Namespace: `asianfanfics`
- Namespace Name: `Asianfanfics`
- Route Path: `/asianfanfics/text-search/:keyword`
- Route Name: `关键词`
- Example: `/asianfanfics/text-search/milklove`
- URL: `asianfanfics.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `KazooTTT`
- Source Location: `text-search.ts`
- Source Module: `_None_`

## Description
匹配 asianfanfics 搜索关键词

## Parameters
- `keyword`: 关键词


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.asianfanfics.com/browse/text_search?q=:keyword`
- `target`: `/text-search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "匹配 asianfanfics 搜索关键词",
  "example": "/asianfanfics/text-search/milklove",
  "heat": 1,
  "location": "text-search.ts",
  "maintainers": [
    "KazooTTT"
  ],
  "name": "关键词",
  "parameters": {
    "keyword": "关键词"
  },
  "path": "/text-search/:keyword",
  "radar": [
    {
      "source": [
        "www.asianfanfics.com/browse/text_search?q=:keyword"
      ],
      "target": "/text-search/:keyword"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Asianfanfics - 关键词：milklove - Powered by RSSHub",
      "errorAt": "2025-11-26T13:33:18.742Z",
      "errorMessage": "[GET] \"https://www.asianfanfics.com/browse/text_search?q=milklove+\": 403 Forbidden\n",
      "id": "119960066992003072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.asianfanfics.com/browse/text_search?q=milklove+",
      "title": "Asianfanfics - 关键词：milklove",
      "type": "feed",
      "url": "rsshub://asianfanfics/text-search/milklove"
    }
  ]
}
```
