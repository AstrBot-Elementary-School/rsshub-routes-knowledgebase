# 留园网 - 新闻栏目

## Coverage
`index-only`

## Route
- Namespace: `6park`
- Namespace Name: `留园网`
- Route Path: `/6park/news/:site?/:id?/:keyword?`
- Route Name: `新闻栏目`
- Example: `/6park/news`
- URL: `club.6parkbbs.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, cscnk52`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
分站

| newspark | local |
| -------- | ----- |

::: tip 提示
若订阅 [时政](https://www.6parknews.com/newspark/index.php?type=1)，其网址为 <https://www.6parknews.com/newspark/index.php?type=1>，其中 `newspark` 为分站，`1` 为栏目 id。
若订阅 [美国](https://local.6parknews.com/index.php?type_id=1)，其网址为 <https://local.6parknews.com/index.php?type_id=1>，其中 `local` 为分站，`1` 为栏目 id。
:::

## Parameters
- `site`: 分站，见下表，默认为 newspark
- `id`: 栏目 id
- `keyword`: 关键字


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `club.6parkbbs.com/:id/index.php`
  - `club.6parkbbs.com/`
- `target`: `/:id?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "分站\n\n| newspark | local |\n| -------- | ----- |\n\n::: tip 提示\n若订阅 [时政](https://www.6parknews.com/newspark/index.php?type=1)，其网址为 <https://www.6parknews.com/newspark/index.php?type=1>，其中 `newspark` 为分站，`1` 为栏目 id。\n若订阅 [美国](https://local.6parknews.com/index.php?type_id=1)，其网址为 <https://local.6parknews.com/index.php?type_id=1>，其中 `local` 为分站，`1` 为栏目 id。\n:::",
  "example": "/6park/news",
  "heat": 5,
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "cscnk52"
  ],
  "name": "新闻栏目",
  "parameters": {
    "id": "栏目 id",
    "keyword": "关键字",
    "site": "分站，见下表，默认为 newspark"
  },
  "path": "/news/:site?/:id?/:keyword?",
  "radar": [
    {
      "source": [
        "club.6parkbbs.com/:id/index.php",
        "club.6parkbbs.com/"
      ],
      "target": "/:id?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "6park.com - Powered by RSSHub",
      "errorAt": "2025-11-04T02:18:39.177Z",
      "errorMessage": "[GET] \"https://www.6parknews.com/newspark/index.php?act=newssearch&app=news&keywords=搜索&submit=查询\": 410 Gone\n",
      "id": "82298733055304704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.6parknews.com/newspark/index.php?act=newssearch&app=news&keywords=%E6%90%9C%E7%B4%A2&submit=%E6%9F%A5%E8%AF%A2",
      "title": "6park.com",
      "type": "feed",
      "url": "rsshub://6park/news/newspark/keywords/%E6%90%9C%E7%B4%A2"
    },
    {
      "description": "6park.com - Powered by RSSHub",
      "errorAt": "2024-11-27T02:54:40.175Z",
      "errorMessage": "[GET] \"https://www.6parknews.com/newspark/index.php?act=newssearch&app=news&keywords=新闻速递&submit=查询\": 410 Gone\n",
      "id": "82300149476718592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.6parknews.com/newspark/index.php?act=newssearch&app=news&keywords=%E6%96%B0%E9%97%BB%E9%80%9F%E9%80%92&submit=%E6%9F%A5%E8%AF%A2",
      "title": "6park.com",
      "type": "feed",
      "url": "rsshub://6park/news/newspark/keywords/%E6%96%B0%E9%97%BB%E9%80%9F%E9%80%92"
    }
  ]
}
```
