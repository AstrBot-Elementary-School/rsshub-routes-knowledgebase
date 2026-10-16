# Kmoe - 首頁

## Coverage
`index-only`

## Route
- Namespace: `mox`
- Namespace Name: `Kmoe`
- Route Path: `/mox/:category?`
- Route Name: `首頁`
- Example: `/mox`
- URL: `kxx.moe`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
在首页将分类参数选择确定后跳转到的分类页面 URL 中，`/l/` 后的字段即为分类参数。

如 [科幻 + 日語 + 日本 + 長篇 + 完結 + 最近更新](https://kxx.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL) 的 URL 为 [https://kxx.moe/l/CAT%2A 科幻，日本，完結，lastupdate,jpn,l,BL](https://kxx.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)，此时 `/l/` 后的字段为 `CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`。最终获得路由为 [`/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`](https://rsshub.app/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)
:::

::: warning
原 mox.moe 现跳转至 kxx.moe。未配置 `MOX_COOKIE` 时只获取首页漫画标题和封面，不请求详情；部分分类需要登录。配置该站有效登录 Cookie 后才获取详情，Cookie 不会随跳转发送到其他站点。
:::

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到


## Features
- `requireConfig`: [{"description": "Kmoe（kxx.moe）登录后的 Cookie，可从该站浏览器开发者工具的 Network 请求中获取。原 mox.moe 现跳转至该站；Cookie 仅发送到 kxx.moe。", "name": "MOX_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `kxx.moe/l/:category`
  - `kxx.moe/`
  - `mox.moe/l/:category`
  - `mox.moe/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n在首页将分类参数选择确定后跳转到的分类页面 URL 中，`/l/` 后的字段即为分类参数。\n\n如 [科幻 + 日語 + 日本 + 長篇 + 完結 + 最近更新](https://kxx.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL) 的 URL 为 [https://kxx.moe/l/CAT%2A 科幻，日本，完結，lastupdate,jpn,l,BL](https://kxx.moe/l/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)，此时 `/l/` 后的字段为 `CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`。最终获得路由为 [`/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL`](https://rsshub.app/mox/CAT%2A科幻,日本,完結,lastupdate,jpn,l,BL)\n:::\n\n::: warning\n原 mox.moe 现跳转至 kxx.moe。未配置 `MOX_COOKIE` 时只获取首页漫画标题和封面，不请求详情；部分分类需要登录。配置该站有效登录 Cookie 后才获取详情，Cookie 不会随跳转发送到其他站点。\n:::",
  "example": "/mox",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "Kmoe（kxx.moe）登录后的 Cookie，可从该站浏览器开发者工具的 Network 请求中获取。原 mox.moe 现跳转至该站；Cookie 仅发送到 kxx.moe。",
        "name": "MOX_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 20,
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
        "kxx.moe/l/:category",
        "kxx.moe/",
        "mox.moe/l/:category",
        "mox.moe/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
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
    },
    {
      "description": "Kmoe - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41865613055386624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://kxx.moe/",
      "title": "Kmoe",
      "type": "feed",
      "url": "rsshub://mox"
    }
  ]
}
```
