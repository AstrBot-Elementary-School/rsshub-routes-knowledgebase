# 巴卡漫画 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `bakamh`
- Namespace Name: `巴卡漫画`
- Route Path: `/bakamh/manga/:name`
- Route Name: `漫画更新`
- Example: `/bakamh/manga/最强家丁`
- URL: `bakamh.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `yoyobase`
- Source Location: `manga.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 漫画名称，漫画主页的地址栏中


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bakamh.com/manga/:name/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bakamh/manga/最强家丁",
  "heat": 4,
  "location": "manga.ts",
  "maintainers": [
    "yoyobase"
  ],
  "name": "漫画更新",
  "parameters": {
    "name": "漫画名称，漫画主页的地址栏中"
  },
  "path": "/manga/:name",
  "radar": [
    {
      "source": [
        "bakamh.com/manga/:name/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "年轻健壮，对主人家忠心耿耿的仆役-强石，某夜意外目睹大监夫人饥渴「自我安慰」的画面。明知眼前是个火坑，却义无反顾地跳了下去!「夫人，小的乐意填补妳空虚寂寞的心灵…」 - Powered by RSSHub",
      "errorAt": "2025-06-07T05:39:16.431Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "147664027379048448",
      "image": "https://bakamh.com/wp-content/uploads/2024/11/cover-5.jpg",
      "ownerUserId": null,
      "siteUrl": "https://bakamh.com/manga/%E6%9C%80%E5%BC%BA%E5%AE%B6%E4%B8%81/",
      "title": "最强家丁 – bakamh巴卡漫画",
      "type": "feed",
      "url": "rsshub://bakamh/manga/%E6%9C%80%E5%BC%BA%E5%AE%B6%E4%B8%81"
    }
  ],
  "url": "bakamh.com"
}
```
