# Mox.moe - 首頁

## Coverage
`index-only`

## Route
- Namespace: `mox`
- Namespace Name: `Mox.moe`
- Route Path: `/mox/:category?`
- Route Name: `首頁`
- Example: `/mox`
- URL: `mox.moe`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
在首页将分类参数选择确定后跳转到的分类页面 URL 中，`/l/` 后的字段即为分类参数。

如 [科幻 + 日語 + 日本 + 長篇 + 完結 + 最近更新](https://mox.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL) 的 URL 为 [https://mox.moe/l/CAT%2A 科幻，日本，完結，lastupdate,jpn,l,BL](https://mox.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)，此时 `/l/` 后的字段为 `CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`。最终获得路由为 [`/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`](https://rsshub.app/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)
:::

::: warning
由于 mox.moe 对非登录用户屏蔽了部分漫画详情内容的获取，且极易触发反爬机制，导致访问 ip 被重定向至 google.com，因此在未配置`MOX_COOKIE`参数的情况下路由只会返回漫画标题和封面，不会对详情内容进行抓取。
:::

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到


## Features
- `requireConfig`: [{"description": "注册用户登录后的 Cookie, 可以从浏览器开发者工具Network面板中的mox页面请求获取，Cookie内容形如VOLSKEY=xxxxxx; VLIBSID=xxxxxx; VOLSESS=xxxxxx", "name": "MOX_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `mox.moe/l/:category`
  - `mox.moe/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n在首页将分类参数选择确定后跳转到的分类页面 URL 中，`/l/` 后的字段即为分类参数。\n\n如 [科幻 + 日語 + 日本 + 長篇 + 完結 + 最近更新](https://mox.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL) 的 URL 为 [https://mox.moe/l/CAT%2A 科幻，日本，完結，lastupdate,jpn,l,BL](https://mox.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)，此时 `/l/` 后的字段为 `CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`。最终获得路由为 [`/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`](https://rsshub.app/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)\n:::\n\n::: warning\n由于 mox.moe 对非登录用户屏蔽了部分漫画详情内容的获取，且极易触发反爬机制，导致访问 ip 被重定向至 google.com，因此在未配置`MOX_COOKIE`参数的情况下路由只会返回漫画标题和封面，不会对详情内容进行抓取。\n:::",
  "example": "/mox",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "注册用户登录后的 Cookie, 可以从浏览器开发者工具Network面板中的mox页面请求获取，Cookie内容形如VOLSKEY=xxxxxx; VLIBSID=xxxxxx; VOLSESS=xxxxxx",
        "name": "MOX_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 21,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "首頁",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "mox.moe/l/:category",
        "mox.moe/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Mox.moe - Powered by RSSHub",
      "errorAt": "2025-02-09T11:32:24.615Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "41865613055386624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mox.moe/",
      "title": "Mox.moe",
      "type": "feed",
      "url": "rsshub://mox"
    },
    {
      "description": "Mox.moe - Powered by RSSHub",
      "errorAt": "2025-02-08T19:06:47.664Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "81628050555910144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mox.moe/l/all,all,%E5%AE%8C%E7%B5%90,lastupdate,cht,all,BL,0,0",
      "title": "Mox.moe",
      "type": "feed",
      "url": "rsshub://mox/all,all,%E5%AE%8C%E7%B5%90,lastupdate,cht,all,BL,0,0"
    }
  ]
}
```
