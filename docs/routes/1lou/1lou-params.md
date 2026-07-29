# BT 之家 1LOU 站 - 通用

## Coverage
`index-only`

## Route
- Namespace: `1lou`
- Namespace Name: `BT 之家 1LOU 站`
- Route Path: `/1lou/:params{.+}?`
- Route Name: `通用`
- Example: `/1lou/forum-2-1`
- URL: `1lou.me`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `falling, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
`1lou.me/` 后的内容填入 params 参数，以下是几个例子：

若订阅 [大陆电视剧](https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0)，网址为 `https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `tagids`，此时路由为 [`/1lou/forum-2-1?tagids=0_97_0_0`](https://rsshub.app/1lou/forum-2-1?tagids=0_97_0_0)。

若订阅 [最新发帖电视剧](https://www.1lou.me/forum-2-1.htm?orderby=tid\&digest=0)，网址为 `https://www.1lou.me/forum-2-1.htm?orderby=tid&digest=0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `orderby`，此时路由为 [`/1lou/forum-2-1?orderby=tid`](https://rsshub.app/1lou/forum-2-1?orderby=tid)。

若订阅 [搜素繁花主题贴](https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm)，网址为 `https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `search-_E7_B9_81_E8_8A_B1-1` 作为参数，此时路由为 [`/1lou/search-_E7_B9_81_E8_8A_B1-1`](https://rsshub.app/1lou/search-_E7_B9_81_E8_8A_B1-1)。
:::

## Parameters
- `params`: 路径参数，可以在对应页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `1lou.me/:params`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n`1lou.me/` 后的内容填入 params 参数，以下是几个例子：\n\n若订阅 [大陆电视剧](https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0)，网址为 `https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `tagids`，此时路由为 [`/1lou/forum-2-1?tagids=0_97_0_0`](https://rsshub.app/1lou/forum-2-1?tagids=0_97_0_0)。\n\n若订阅 [最新发帖电视剧](https://www.1lou.me/forum-2-1.htm?orderby=tid\\&digest=0)，网址为 `https://www.1lou.me/forum-2-1.htm?orderby=tid&digest=0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `orderby`，此时路由为 [`/1lou/forum-2-1?orderby=tid`](https://rsshub.app/1lou/forum-2-1?orderby=tid)。\n\n若订阅 [搜素繁花主题贴](https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm)，网址为 `https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `search-_E7_B9_81_E8_8A_B1-1` 作为参数，此时路由为 [`/1lou/search-_E7_B9_81_E8_8A_B1-1`](https://rsshub.app/1lou/search-_E7_B9_81_E8_8A_B1-1)。\n:::",
  "example": "/1lou/forum-2-1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 508,
  "location": "index.ts",
  "maintainers": [
    "falling",
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "params": "路径参数，可以在对应页面的 URL 中找到"
  },
  "path": "/:params{.+}?",
  "radar": [
    {
      "source": [
        "1lou.me/:params"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "论坛影视区推荐使用纯BT软件：Transmission，qBittorrent，Bitcomet，uTorrent，其他下载软件请自行尝试。不支持吸血迅雷。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62495339293222913",
      "image": "https://www.1lou.me/view/img/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.1lou.me/forum-1.htm?format=json",
      "title": "最新电影 - BT 之家 1LOU 站",
      "type": "feed",
      "url": "rsshub://1lou/forum-1"
    },
    {
      "description": "论坛影视区推荐使用纯BT软件：Transmission，qBittorrent，Bitcomet，uTorrent，其他下载软件请自行尝试。不支持吸血迅雷。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64249408253921283",
      "image": "https://www.1lou.me/view/img/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.1lou.me/forum-2-1.htm?format=json",
      "title": "电视剧集 - BT 之家 1LOU 站",
      "type": "feed",
      "url": "rsshub://1lou/forum-2-1"
    }
  ],
  "url": "1lou.me"
}
```
