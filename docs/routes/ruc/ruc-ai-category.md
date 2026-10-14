# Renmin University of China - 高瓴人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `ruc`
- Namespace Name: `Renmin University of China`
- Route Path: `/ruc/ai/:category?`
- Route Name: `高瓴人工智能学院`
- Example: `/ruc/ai`
- URL: `ai.ruc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `yinhanyan`
- Source Location: `ai.ts`
- Source Module: `_None_`

## Description
分类参数填写分类页地址中介于 `https://ai.ruc.edu.cn/` 和 `/index.htm` 之间的路径，并将 `/` 替换为 `-`。

例如 [学院公告](https://ai.ruc.edu.cn/xwgg/xygg/index.htm) 对应 `xwgg-xygg`；[学院新闻](https://ai.ruc.edu.cn/xwgg/xyxw/index.htm) 对应 `xwgg-xyxw`。旧参数 `newslist-notice` 和 `newslist-newsdetail` 分别映射到当前公告和新闻分类。

## Parameters
- `category`: 分类，见下方说明，默认为学院公告（xwgg-xygg）


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
  - `ai.ruc.edu.cn/`
  - `ai.ruc.edu.cn/xwgg/xygg/index.htm`
- `target`: `/ai`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "分类参数填写分类页地址中介于 `https://ai.ruc.edu.cn/` 和 `/index.htm` 之间的路径，并将 `/` 替换为 `-`。\n\n例如 [学院公告](https://ai.ruc.edu.cn/xwgg/xygg/index.htm) 对应 `xwgg-xygg`；[学院新闻](https://ai.ruc.edu.cn/xwgg/xyxw/index.htm) 对应 `xwgg-xyxw`。旧参数 `newslist-notice` 和 `newslist-newsdetail` 分别映射到当前公告和新闻分类。",
  "example": "/ruc/ai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "ai.ts",
  "maintainers": [
    "yinhanyan"
  ],
  "name": "高瓴人工智能学院",
  "parameters": {
    "category": "分类，见下方说明，默认为学院公告（xwgg-xygg）"
  },
  "path": "/ai/:category?",
  "radar": [
    {
      "source": [
        "ai.ruc.edu.cn/",
        "ai.ruc.edu.cn/xwgg/xygg/index.htm"
      ],
      "target": "/ai"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "学院公告_中国人民大学高瓴人工智能学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78796620218548224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://ai.ruc.edu.cn/newslist/notice/index.htm",
      "title": "学院公告_中国人民大学高瓴人工智能学院",
      "type": "feed",
      "url": "rsshub://ruc/ai"
    }
  ],
  "url": "ai.ruc.edu.cn/"
}
```
