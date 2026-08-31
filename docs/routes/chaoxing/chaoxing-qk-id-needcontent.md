# 超星 - 期刊

## Coverage
`index-only`

## Route
- Namespace: `chaoxing`
- Namespace Name: `超星`
- Route Path: `/chaoxing/qk/:id/:needContent?`
- Route Name: `期刊`
- Example: `/chaoxing/qk/6b5c39b3dd84352be512e29df0297437`
- URL: `chaoxing.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `qk.tsx`
- Source Module: `_None_`

## Description
::: tip
全部期刊可以在 [这里](http://qk.chaoxing.com/space/index) 找到，你也可以从 [学科分类](https://qikan.chaoxing.com/jourclassify) 和 [期刊导航](https://qikan.chaoxing.com/search/openmag) 中发现更多期刊。

如订阅 [**上海文艺**](http://m.chaoxing.com/mqk/list?sw=\&mags=6b5c39b3dd84352be512e29df0297437\&isort=20\&from=space)，其 URL 为 `http://m.chaoxing.com/mqk/list?mags=6b5c39b3dd84352be512e29df0297437`。`6b5c39b3dd84352be512e29df0297437` 即为期刊 id，所得路由为 [`/chaoxing/qk/6b5c39b3dd84352be512e29df0297437`](https://rsshub.app/chaoxing/qk/6b5c39b3dd84352be512e29df0297437)
:::

::: warning
你可以设置参数 **需要获取文章全文** 为 `true` `yes` `t` `y` 等值（或者忽略这个参数），RSS 的条目会携带期刊中的 **文章全文**，而不仅仅是 **文章概要**。但因为发起访问请求过多会被该网站屏蔽，你可以将其关闭（设置该参数为 `false` `no` `f` `n` 等值），这将会大大减少请求次数从而更难触发网站的反爬机制。

路由默认会获取 **30** 个条目。在路由后指定 `?limit=<条目数量>` 减少或增加单次获取条目数量，同样可以减少请求次数，如设置为一次获取 **10** 个条目，路由可以更改为 [`/chaoxing/qk/6b5c39b3dd84352be512e29df0297437?limit=10`](https://rsshub.app/chaoxing/qk/6b5c39b3dd84352be512e29df0297437?limit=10)

在根据上文设置 **需要获取文章全文** 为不需要时，你可以将 `limit` 值增大，从而获取更多的条目，此时因为不获取全文也不会触发反爬机制，如 [`/chaoxing/qk/6b5c39b3dd84352be512e29df0297437/false?limit=100`](https://rsshub.app/chaoxing/qk/6b5c39b3dd84352be512e29df0297437/false?limit=100)
:::

## Parameters
- `id`: 期刊 id，可在期刊页 URL 中找到
- `needContent`: 需要获取文章全文，填写 true/yes 表示需要，默认需要


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "::: tip\n全部期刊可以在 [这里](http://qk.chaoxing.com/space/index) 找到，你也可以从 [学科分类](https://qikan.chaoxing.com/jourclassify) 和 [期刊导航](https://qikan.chaoxing.com/search/openmag) 中发现更多期刊。\n\n如订阅 [**上海文艺**](http://m.chaoxing.com/mqk/list?sw=\\&mags=6b5c39b3dd84352be512e29df0297437\\&isort=20\\&from=space)，其 URL 为 `http://m.chaoxing.com/mqk/list?mags=6b5c39b3dd84352be512e29df0297437`。`6b5c39b3dd84352be512e29df0297437` 即为期刊 id，所得路由为 [`/chaoxing/qk/6b5c39b3dd84352be512e29df0297437`](https://rsshub.app/chaoxing/qk/6b5c39b3dd84352be512e29df0297437)\n:::\n\n::: warning\n你可以设置参数 **需要获取文章全文** 为 `true` `yes` `t` `y` 等值（或者忽略这个参数），RSS 的条目会携带期刊中的 **文章全文**，而不仅仅是 **文章概要**。但因为发起访问请求过多会被该网站屏蔽，你可以将其关闭（设置该参数为 `false` `no` `f` `n` 等值），这将会大大减少请求次数从而更难触发网站的反爬机制。\n\n路由默认会获取 **30** 个条目。在路由后指定 `?limit=<条目数量>` 减少或增加单次获取条目数量，同样可以减少请求次数，如设置为一次获取 **10** 个条目，路由可以更改为 [`/chaoxing/qk/6b5c39b3dd84352be512e29df0297437?limit=10`](https://rsshub.app/chaoxing/qk/6b5c39b3dd84352be512e29df0297437?limit=10)\n\n在根据上文设置 **需要获取文章全文** 为不需要时，你可以将 `limit` 值增大，从而获取更多的条目，此时因为不获取全文也不会触发反爬机制，如 [`/chaoxing/qk/6b5c39b3dd84352be512e29df0297437/false?limit=100`](https://rsshub.app/chaoxing/qk/6b5c39b3dd84352be512e29df0297437/false?limit=100)\n:::",
  "example": "/chaoxing/qk/6b5c39b3dd84352be512e29df0297437",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "qk.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "期刊",
  "parameters": {
    "id": "期刊 id，可在期刊页 URL 中找到",
    "needContent": "需要获取文章全文，填写 true/yes 表示需要，默认需要"
  },
  "path": "/qk/:id/:needContent?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
