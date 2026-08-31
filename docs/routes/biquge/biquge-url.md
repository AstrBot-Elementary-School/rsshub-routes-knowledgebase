# 笔趣阁 - 小说

## Coverage
`index-only`

## Route
- Namespace: `biquge`
- Namespace Name: `笔趣阁`
- Route Path: `/biquge/:url{.+}`
- Route Name: `小说`
- Example: `/biquge/http://www.biqu5200.net/0_7/`
- URL: `xbiquwx.la`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `jjeejj, machsix, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

#### 使用方法

如订阅 [《大主宰》](http://www.biqu5200.net/0_7/)，此时在 [biqu5200.net](http://www.biqu5200.net) 中查询得到对应小说详情页 URL 为 `http://www.biqu5200.net/0_7/`。此时，路由为 [`/biquge/http://www.biqu5200.net/0_7/`](https://rsshub.app/biquge/http://www.biqu5200.net/0_7/)

又如同样订阅 [《大主宰》](https://www.shuquge.com/txt/70/index.html)，此时在 [shuquge.com](https://www.shuquge.com) 中查询得到对应小说详情页 URL 为 `https://www.shuquge.com/txt/70/index.html`。此时，把末尾的 `index.html` 去掉，路由为 [`/biquge/https://www.shuquge.com/txt/70/`](https://rsshub.app/biquge/https://www.shuquge.com/txt/70/)

#### 关于章节数

路由默认返回最新 **1** 个章节，如有需要一次性获取多个章节，可在路由后指定 `limit` 参数。如上面的例子：订阅 [《大主宰》](http://www.biqu5200.net/0_7/) 并获取最新的 **10** 个章节。此时，路由为 [`/biquge/http://www.biqu5200.net/0_7/?limit=10`](https://rsshub.app/biquge/http://www.biqu5200.net/0_7/?limit=10)

需要注意的是，单次获取的所有章节更新时间统一设定为最新章节的更新时间。也就是说，获取最新的 **10** 个章节时，除了最新 **1** 个章节的更新时间是准确的（和网站一致的），其他 **9** 个章节的更新时间是不准确的。

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
  "description": "::: tip\n\n#### 使用方法\n\n如订阅 [《大主宰》](http://www.biqu5200.net/0_7/)，此时在 [biqu5200.net](http://www.biqu5200.net) 中查询得到对应小说详情页 URL 为 `http://www.biqu5200.net/0_7/`。此时，路由为 [`/biquge/http://www.biqu5200.net/0_7/`](https://rsshub.app/biquge/http://www.biqu5200.net/0_7/)\n\n又如同样订阅 [《大主宰》](https://www.shuquge.com/txt/70/index.html)，此时在 [shuquge.com](https://www.shuquge.com) 中查询得到对应小说详情页 URL 为 `https://www.shuquge.com/txt/70/index.html`。此时，把末尾的 `index.html` 去掉，路由为 [`/biquge/https://www.shuquge.com/txt/70/`](https://rsshub.app/biquge/https://www.shuquge.com/txt/70/)\n\n#### 关于章节数\n\n路由默认返回最新 **1** 个章节，如有需要一次性获取多个章节，可在路由后指定 `limit` 参数。如上面的例子：订阅 [《大主宰》](http://www.biqu5200.net/0_7/) 并获取最新的 **10** 个章节。此时，路由为 [`/biquge/http://www.biqu5200.net/0_7/?limit=10`](https://rsshub.app/biquge/http://www.biqu5200.net/0_7/?limit=10)\n\n需要注意的是，单次获取的所有章节更新时间统一设定为最新章节的更新时间。也就是说，获取最新的 **10** 个章节时，除了最新 **1** 个章节的更新时间是准确的（和网站一致的），其他 **9** 个章节的更新时间是不准确的。\n\n另外，若设置获取章节数目过多，可能会触发网站反爬，导致路由不可用。\n:::\n\n::: warning\n上方列举的网址可能部分不可用，这取决于该网站的维护者是否持续运营网站。请选择可以正常访问的网址，获取更新的前提是该网站可以正常访问。\n:::",
  "example": "/biquge/http://www.biqu5200.net/0_7/",
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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
