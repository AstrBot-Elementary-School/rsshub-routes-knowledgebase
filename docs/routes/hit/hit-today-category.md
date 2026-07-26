# 哈尔滨工业大学 - 今日哈工大

## Coverage
`index-only`

## Route
- Namespace: `hit`
- Namespace Name: `哈尔滨工业大学`
- Route Path: `/hit/today/:category`
- Route Name: `今日哈工大`
- Example: `/hit/today/10`
- URL: `www.hit.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ranpox`
- Source Location: `today.ts`
- Source Module: `_None_`

## Description
::: tip
今日哈工大的文章分为公告公示和新闻快讯，每个页面右侧列出了更详细的分类，其编号为每个 URL 路径的最后一个数字。
例如会议讲座的路径为`/taxonomy/term/10/25`，则可以通过 [`/hit/today/25`](https://rsshub.app/hit/today/25) 订阅该详细类别。
:::

::: warning
部分文章需要经过统一身份认证后才能阅读全文。
:::

## Parameters
- `category`: 分类编号，`10`为公告公示，`11`为新闻快讯，同时支持详细分类，使用方法见下


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
  - `today.hit.edu.cn/category/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n今日哈工大的文章分为公告公示和新闻快讯，每个页面右侧列出了更详细的分类，其编号为每个 URL 路径的最后一个数字。\n例如会议讲座的路径为`/taxonomy/term/10/25`，则可以通过 [`/hit/today/25`](https://rsshub.app/hit/today/25) 订阅该详细类别。\n:::\n\n::: warning\n部分文章需要经过统一身份认证后才能阅读全文。\n:::",
  "example": "/hit/today/10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "today.ts",
  "maintainers": [
    "ranpox"
  ],
  "name": "今日哈工大",
  "parameters": {
    "category": "分类编号，`10`为公告公示，`11`为新闻快讯，同时支持详细分类，使用方法见下"
  },
  "path": "/today/:category",
  "radar": [
    {
      "source": [
        "today.hit.edu.cn/category/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "公告公示（预告公布） | 今日哈工大 ： 哈尔滨工业大学校内综合信息网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64568770572881945",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://today.hit.edu.cn/category/10",
      "title": "公告公示（预告公布） | 今日哈工大 ： 哈尔滨工业大学校内综合信息网",
      "type": "feed",
      "url": "rsshub://hit/today/10"
    },
    {
      "description": "新闻快讯（图文报道） | 今日哈工大 ： 哈尔滨工业大学校内综合信息网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148752145105795072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://today.hit.edu.cn/category/11",
      "title": "新闻快讯（图文报道） | 今日哈工大 ： 哈尔滨工业大学校内综合信息网",
      "type": "feed",
      "url": "rsshub://hit/today/11"
    }
  ]
}
```
