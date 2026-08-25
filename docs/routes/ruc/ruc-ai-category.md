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
::: tip
分类字段处填写的是对应中国人民大学高瓴人工智能学院分类页网址中介于 **`http://ai.ruc.edu.cn/`** 和 **/index.htm** 中间的一段，并将其中的 `/` 修改为 `-`。

如 [中国人民大学高瓴人工智能学院 - 新闻公告 - 学院新闻](http://ai.ruc.edu.cn/newslist/newsdetail/index.htm) 的网址为 `http://ai.ruc.edu.cn/newslist/newsdetail/index.htm` 其中介于 **`http://ai.ruc.edu.cn/`** 和 **/index.htm** 中间的一段为 `newslist/newsdetail`。随后，并将其中的 `/` 修改为 `-`，可以得到 `newslist-newsdetail`。所以最终我们的路由为 [`/ruc/ai/newslist-newsdetail`](https://rsshub.app/ruc/ai/newslist-newsdetail)
:::

## Parameters
- `category`: 分类，见下方说明，默认为首页公告


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

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n分类字段处填写的是对应中国人民大学高瓴人工智能学院分类页网址中介于 **`http://ai.ruc.edu.cn/`** 和 **/index.htm** 中间的一段，并将其中的 `/` 修改为 `-`。\n\n如 [中国人民大学高瓴人工智能学院 - 新闻公告 - 学院新闻](http://ai.ruc.edu.cn/newslist/newsdetail/index.htm) 的网址为 `http://ai.ruc.edu.cn/newslist/newsdetail/index.htm` 其中介于 **`http://ai.ruc.edu.cn/`** 和 **/index.htm** 中间的一段为 `newslist/newsdetail`。随后，并将其中的 `/` 修改为 `-`，可以得到 `newslist-newsdetail`。所以最终我们的路由为 [`/ruc/ai/newslist-newsdetail`](https://rsshub.app/ruc/ai/newslist-newsdetail)\n:::",
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
    "category": "分类，见下方说明，默认为首页公告"
  },
  "path": "/ai/:category?",
  "radar": [
    {
      "source": [
        "ai.ruc.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
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
