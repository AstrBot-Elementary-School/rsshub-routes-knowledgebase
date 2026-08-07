# 山东省教育招生考试院 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `sdzk`
- Namespace Name: `山东省教育招生考试院`
- Route Path: `/sdzk/:bcid?/:cid?`
- Route Name: `新闻`
- Example: `/sdzk`
- URL: `sdzk.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [信息与政策](https://www.sdzk.cn/NewsList.aspx?BCID=1)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1`。截取 `BCID=1` 作为参数，此时路由为 [`/sdzk/1`](https://rsshub.app/sdzk/1)。

若订阅 [通知公告](https://www.sdzk.cn/NewsList.aspx?BCID=1\&CID=16)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1&CID=16`。截取 `BCID=1` 与 `CID=16` 作为参数，此时路由为 [`/sdzk/1/16`](https://rsshub.app/sdzk/1/16)。
:::

## Parameters
- `bcid`: 板块 id，可在对应板块页 URL 中找到，默认为 `1`，即信息与政策
- `cid`: 栏目 id，可在对应板块页 URL 中找到，默认为 `16`，即通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "::: tip\n若订阅 [信息与政策](https://www.sdzk.cn/NewsList.aspx?BCID=1)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1`。截取 `BCID=1` 作为参数，此时路由为 [`/sdzk/1`](https://rsshub.app/sdzk/1)。\n\n若订阅 [通知公告](https://www.sdzk.cn/NewsList.aspx?BCID=1\\&CID=16)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1&CID=16`。截取 `BCID=1` 与 `CID=16` 作为参数，此时路由为 [`/sdzk/1/16`](https://rsshub.app/sdzk/1/16)。\n:::",
  "example": "/sdzk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "bcid": "板块 id，可在对应板块页 URL 中找到，默认为 `1`，即信息与政策",
    "cid": "栏目 id，可在对应板块页 URL 中找到，默认为 `16`，即通知公告"
  },
  "path": "/:bcid?/:cid?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "工作动态_山东省教育招生考试院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66769930499978240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sdzk.cn/NewsList.aspx?BCID=1&CID=16",
      "title": "工作动态_山东省教育招生考试院",
      "type": "feed",
      "url": "rsshub://sdzk/1/16"
    },
    {
      "description": "山东省教育招生考试院官网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84436097402035200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sdzk.cn/NewsList.aspx?BCID=:bcid&CID=16",
      "title": "山东省教育招生考试院官网",
      "type": "feed",
      "url": "rsshub://sdzk/:bcid"
    }
  ]
}
```
