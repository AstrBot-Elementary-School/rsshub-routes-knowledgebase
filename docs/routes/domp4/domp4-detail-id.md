# DoMP4 影视 - 剧集订阅

## Coverage
`index-only`

## Route
- Namespace: `domp4`
- Namespace Name: `DoMP4 影视`
- Route Path: `/domp4/detail/:id`
- Route Name: `剧集订阅`
- Example: `/domp4/detail/LBTANI22222I`
- URL: `www.xlmp4.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `savokiss, pseudoyu`
- Source Location: `detail.ts`
- Source Module: `_None_`

## Description
::: tip
由于大部分详情页是 `/html/xxx.html`，还有部分是 `/detail/123.html`，所以此处做了兼容，id 取 `xxx` 或者 `123` 都可以。

新增 `second` 参数，用于选择下载地址二（地址二不可用或者不填都默认地址一），用法: `/domp4/detail/LBTANI22222I?second=1`。

域名频繁更换，目前使用 [www.xlmp4.com](http://www.xlmp4.com)
:::

## Parameters
- `id`: 从剧集详情页 URL 处获取，如：`https://www.xlmp4.com/html/LBTANI22222I.html`，取 `.html` 前面部分


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.xlmp4.com/detail/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n由于大部分详情页是 `/html/xxx.html`，还有部分是 `/detail/123.html`，所以此处做了兼容，id 取 `xxx` 或者 `123` 都可以。\n\n新增 `second` 参数，用于选择下载地址二（地址二不可用或者不填都默认地址一），用法: `/domp4/detail/LBTANI22222I?second=1`。\n\n域名频繁更换，目前使用 [www.xlmp4.com](http://www.xlmp4.com)\n:::",
  "example": "/domp4/detail/LBTANI22222I",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 26,
  "location": "detail.ts",
  "maintainers": [
    "savokiss",
    "pseudoyu"
  ],
  "name": "剧集订阅",
  "parameters": {
    "id": "从剧集详情页 URL 处获取，如：`https://www.xlmp4.com/html/LBTANI22222I.html`，取 `.html` 前面部分"
  },
  "path": "/detail/:id",
  "radar": [
    {
      "source": [
        "www.xlmp4.com/detail/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "平凡少年韩立出生贫困，为了让家人过上更好的生活，自愿前去七玄门参加入门考核，最终被墨大夫收入门下。 墨大夫一开始对韩立悉心培养、传授医术，让韩立对他非常感激，但随着一同入门的弟子张铁失踪，韩立才发现了墨大夫的真面目。 墨大夫试图夺舍韩立，最终却被韩立反杀。通过墨大夫的遗书韩立得知了一个全新世界：修仙界的存在。 在帮助七玄门抵御外敌之后，韩立离开了七玄门，前去墨大夫的家中寻找暖阳宝玉解毒，并帮助墨家人打败了敌人。 通过墨大夫之女墨彩环的口中得知太南小会地址，韩立为追寻修仙人的足迹决定前往太南小会，拜别家人后…… - Powered by RSSHub",
      "errorAt": "2025-05-15T15:21:43.457Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "64907131788397568",
      "image": "https://img.xlmp4.cc/vod/7/619086a42fed7.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.xlmp4.com/html/9DvTT8bbbbb8.html",
      "title": "凡人修仙传",
      "type": "feed",
      "url": "rsshub://domp4/detail/9DvTT8bbbbb8"
    },
    {
      "description": "三年之约后，萧炎终于在迦南学院见到了薰儿，此后他广交挚友并成立磐门；为继续提升实力以三上云岚宗为父复仇，他以身犯险深入天焚炼气塔吞噬陨落心炎…… - Powered by RSSHub",
      "errorAt": "2025-05-15T17:19:35.693Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "112346789614543872",
      "image": "https://img.xlmp4.cc/vod/d/62e5e8f6a1697.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.xlmp4.com/html/CVnfK5000005.html",
      "title": "斗破苍穹年番",
      "type": "feed",
      "url": "rsshub://domp4/detail/CVnfK5000005"
    }
  ]
}
```
