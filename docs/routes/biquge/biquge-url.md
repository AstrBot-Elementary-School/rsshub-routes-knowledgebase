# 笔趣阁 - 小说

## Coverage
`index-only`

## Route
- Namespace: `biquge`
- Namespace Name: `笔趣阁`
- Route Path: `/biquge/:url{.+}`
- Route Name: `小说`
- Example: `/biquge/https://www.b520.cc/0_7/`
- URL: `www.b520.cc`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `jjeejj, machsix, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

#### 使用方法

如订阅 [《大主宰》](https://www.b520.cc/0_7/)，此时在 [b520.cc](https://www.b520.cc) 中查询得到对应小说详情页 URL 为 `https://www.b520.cc/0_7/`。此时，路由为 [`/biquge/https://www.b520.cc/0_7/`](https://rsshub.app/biquge/https://www.b520.cc/0_7/)

#### 关于章节数

路由默认返回最新 **1** 个章节，如有需要一次性获取多个章节，可在路由后指定 `limit` 参数。如上面的例子：订阅 [《大主宰》](https://www.b520.cc/0_7/) 并指定最多获取最新的 **10** 个章节。此时，路由为 [`/biquge/https://www.b520.cc/0_7/?limit=10`](https://rsshub.app/biquge/https://www.b520.cc/0_7/?limit=10)

源站仅提供最新章节的更新时间，因此只有与源站最新章节信息匹配的条目包含更新时间，其他章节不提供时间。

另外，若设置获取章节数目过多，可能会触发网站反爬，导致路由不可用。
:::

::: warning
上方列举的网址可能部分不可用，这取决于该网站的维护者是否持续运营网站。请选择可以正常访问的网址，获取更新的前提是该网站可以正常访问。
:::

## Parameters
- `url`: 小说 Url，即对应小说详情页的 Url，可在地址栏中找到


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "::: tip\n\n#### 使用方法\n\n如订阅 [《大主宰》](https://www.b520.cc/0_7/)，此时在 [b520.cc](https://www.b520.cc) 中查询得到对应小说详情页 URL 为 `https://www.b520.cc/0_7/`。此时，路由为 [`/biquge/https://www.b520.cc/0_7/`](https://rsshub.app/biquge/https://www.b520.cc/0_7/)\n\n#### 关于章节数\n\n路由默认返回最新 **1** 个章节，如有需要一次性获取多个章节，可在路由后指定 `limit` 参数。如上面的例子：订阅 [《大主宰》](https://www.b520.cc/0_7/) 并指定最多获取最新的 **10** 个章节。此时，路由为 [`/biquge/https://www.b520.cc/0_7/?limit=10`](https://rsshub.app/biquge/https://www.b520.cc/0_7/?limit=10)\n\n源站仅提供最新章节的更新时间，因此只有与源站最新章节信息匹配的条目包含更新时间，其他章节不提供时间。\n\n另外，若设置获取章节数目过多，可能会触发网站反爬，导致路由不可用。\n:::\n\n::: warning\n上方列举的网址可能部分不可用，这取决于该网站的维护者是否持续运营网站。请选择可以正常访问的网址，获取更新的前提是该网站可以正常访问。\n:::",
  "example": "/biquge/https://www.b520.cc/0_7/",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "jjeejj",
    "machsix",
    "nczitzk"
  ],
  "name": "小说",
  "parameters": {
    "url": "小说 Url，即对应小说详情页的 Url，可在地址栏中找到"
  },
  "path": "/:url{.+}",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
