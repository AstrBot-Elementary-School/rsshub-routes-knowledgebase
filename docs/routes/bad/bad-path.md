# Bad.news - 通用

## Coverage
`index-only`

## Route
- Namespace: `bad`
- Namespace Name: `Bad.news`
- Route Path: `/bad/:path{.+}?`
- Route Name: `通用`
- Example: `/bad`
- URL: `bad.news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
若订阅 [每日热点 - 最新](https://bad.news/tag/每日热点/sort-new)，网址为 `https://bad.news/tag/每日热点/sort-new`。截取 `https://bad.news` 到末尾的部分 `/tag/每日热点/sort-new` 作为参数，此时路由为 [`/bad/tag/每日热点/sort-new`](https://rsshub.app/bad/tag/每日热点/sort-new)。

若订阅子分类 [大陆资讯 - 热门](https://bad.news/tag/大陆资讯/sort-hot)，网址为 `https://bad.news/tag/大陆资讯/sort-hot`。截取 `https://bad.news` 到末尾的部分 `/tag/大陆资讯/sort-hot` 作为参数，路由为 [`/bad/tag/大陆资讯/sort-hot`](https://rsshub.app/bad/tag/大陆资讯/sort-hot)。

## Parameters
- `path`: 路径，默认为首页热门


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "若订阅 [每日热点 - 最新](https://bad.news/tag/每日热点/sort-new)，网址为 `https://bad.news/tag/每日热点/sort-new`。截取 `https://bad.news` 到末尾的部分 `/tag/每日热点/sort-new` 作为参数，此时路由为 [`/bad/tag/每日热点/sort-new`](https://rsshub.app/bad/tag/每日热点/sort-new)。\n\n若订阅子分类 [大陆资讯 - 热门](https://bad.news/tag/大陆资讯/sort-hot)，网址为 `https://bad.news/tag/大陆资讯/sort-hot`。截取 `https://bad.news` 到末尾的部分 `/tag/大陆资讯/sort-hot` 作为参数，路由为 [`/bad/tag/大陆资讯/sort-hot`](https://rsshub.app/bad/tag/大陆资讯/sort-hot)。",
  "example": "/bad",
  "heat": 53,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，默认为首页热门"
  },
  "path": "/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(2) ] to not include 'https://bad.news/search/t-all/q-user:…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Bad.news - 热门 - Powered by RSSHub",
      "errorAt": "2026-09-01T04:32:01.337Z",
      "errorMessage": "[GET] \"https://bad.news\": 451 Unavailable For Legal Reasons\n",
      "id": "66153135747790848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bad.news/",
      "title": "Bad.news - 热门",
      "type": "feed",
      "url": "rsshub://bad"
    },
    {
      "description": "Bad.news - 短视频 热门 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76857388995210240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bad.news/tag/porn",
      "title": "Bad.news - 短视频 热门",
      "type": "feed",
      "url": "rsshub://bad/tag/porn"
    }
  ]
}
```
