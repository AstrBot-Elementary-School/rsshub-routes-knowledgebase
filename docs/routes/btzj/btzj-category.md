# BT 之家 - 分类

## Coverage
`index-only`

## Route
- Namespace: `btzj`
- Namespace Name: `BT 之家`
- Route Path: `/btzj/:category?`
- Route Name: `分类`
- Example: `/btzj`
- URL: `btbtt20.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
分类页中域名末尾到 `.htm` 前的字段即为对应分类，如 [电影](https://www.btbtt20.com/forum-index-fid-951.htm) `https://www.btbtt20.com/forum-index-fid-951.htm` 中域名末尾到 `.htm` 前的字段为 `forum-index-fid-951`，所以路由应为 [`/btzj/forum-index-fid-951`](https://rsshub.app/btzj/forum-index-fid-951)

部分分类页，如 [电影](https://www.btbtt20.com/forum-index-fid-951.htm)、[剧集](https://www.btbtt20.com/forum-index-fid-950.htm) 等，提供了更复杂的分类筛选。你可以将选项选中后，获得结果分类页 URL 中分类参数，构成路由。如选中分类 [高清电影 - 年份：2021 - 地区：欧美](https://www.btbtt20.com/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0.htm) `https://www.btbtt20.com/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0.htm` 中域名末尾到 `.htm` 前的字段为 `forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0`，所以路由应为 [`/btzj/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0`](https://rsshub.app/btzj/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0)
:::

基础分类如下：

| 交流                | 电影                | 剧集                | 高清电影             |
| ------------------- | ------------------- | ------------------- | -------------------- |
| forum-index-fid-975 | forum-index-fid-951 | forum-index-fid-950 | forum-index-fid-1183 |

| 音乐                | 动漫                | 游戏                | 综艺                 |
| ------------------- | ------------------- | ------------------- | -------------------- |
| forum-index-fid-953 | forum-index-fid-981 | forum-index-fid-955 | forum-index-fid-1106 |

| 图书                 | 美图                | 站务              | 科技                |
| -------------------- | ------------------- | ----------------- | ------------------- |
| forum-index-fid-1151 | forum-index-fid-957 | forum-index-fid-2 | forum-index-fid-952 |

| 求助                 | 音轨字幕             |
| -------------------- | -------------------- |
| forum-index-fid-1187 | forum-index-fid-1191 |

::: tip
BT 之家的域名会变更，本路由以 `https://www.btbtt20.com` 为默认域名，若该域名无法访问，可以通过在路由后方加上 `?domain=<域名>` 指定路由访问的域名。如指定域名为 `https://www.btbtt15.com`，则在 `/btzj` 后加上 `?domain=btbtt15.com` 即可，此时路由为 [`/btzj?domain=btbtt15.com`](https://rsshub.app/btzj?domain=btbtt15.com)

如果加入了分类参数，直接在分类参数后加入 `?domain=<域名>` 即可。如指定分类 [剧集](https://www.btbtt20.com/forum-index-fid-950.htm) `https://www.btbtt20.com/forum-index-fid-950.htm` 并指定域名为 `https://www.btbtt15.com`，即在 `/btzj/forum-index-fid-950` 后加上 `?domain=btbtt15.com`，此时路由为 [`/btzj/forum-index-fid-950?domain=btbtt15.com`](https://rsshub.app/btzj/forum-index-fid-950?domain=btbtt15.com)

目前，你可以选择的域名有 `btbtt10-20.com` 共 10 个，或 `88btbbt.com`，该站也提供了专用网址查询工具。详见 [此贴](https://www.btbtt20.com/thread-index-fid-2-tid-4550191.htm)
:::

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，默认为首页


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `btbtt20.com/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n分类页中域名末尾到 `.htm` 前的字段即为对应分类，如 [电影](https://www.btbtt20.com/forum-index-fid-951.htm) `https://www.btbtt20.com/forum-index-fid-951.htm` 中域名末尾到 `.htm` 前的字段为 `forum-index-fid-951`，所以路由应为 [`/btzj/forum-index-fid-951`](https://rsshub.app/btzj/forum-index-fid-951)\n\n部分分类页，如 [电影](https://www.btbtt20.com/forum-index-fid-951.htm)、[剧集](https://www.btbtt20.com/forum-index-fid-950.htm) 等，提供了更复杂的分类筛选。你可以将选项选中后，获得结果分类页 URL 中分类参数，构成路由。如选中分类 [高清电影 - 年份：2021 - 地区：欧美](https://www.btbtt20.com/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0.htm) `https://www.btbtt20.com/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0.htm` 中域名末尾到 `.htm` 前的字段为 `forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0`，所以路由应为 [`/btzj/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0`](https://rsshub.app/btzj/forum-index-fid-1183-typeid1-0-typeid2-738-typeid3-10086-typeid4-0)\n:::\n\n基础分类如下：\n\n| 交流                | 电影                | 剧集                | 高清电影             |\n| ------------------- | ------------------- | ------------------- | -------------------- |\n| forum-index-fid-975 | forum-index-fid-951 | forum-index-fid-950 | forum-index-fid-1183 |\n\n| 音乐                | 动漫                | 游戏                | 综艺                 |\n| ------------------- | ------------------- | ------------------- | -------------------- |\n| forum-index-fid-953 | forum-index-fid-981 | forum-index-fid-955 | forum-index-fid-1106 |\n\n| 图书                 | 美图                | 站务              | 科技                |\n| -------------------- | ------------------- | ----------------- | ------------------- |\n| forum-index-fid-1151 | forum-index-fid-957 | forum-index-fid-2 | forum-index-fid-952 |\n\n| 求助                 | 音轨字幕             |\n| -------------------- | -------------------- |\n| forum-index-fid-1187 | forum-index-fid-1191 |\n\n::: tip\nBT 之家的域名会变更，本路由以 `https://www.btbtt20.com` 为默认域名，若该域名无法访问，可以通过在路由后方加上 `?domain=<域名>` 指定路由访问的域名。如指定域名为 `https://www.btbtt15.com`，则在 `/btzj` 后加上 `?domain=btbtt15.com` 即可，此时路由为 [`/btzj?domain=btbtt15.com`](https://rsshub.app/btzj?domain=btbtt15.com)\n\n如果加入了分类参数，直接在分类参数后加入 `?domain=<域名>` 即可。如指定分类 [剧集](https://www.btbtt20.com/forum-index-fid-950.htm) `https://www.btbtt20.com/forum-index-fid-950.htm` 并指定域名为 `https://www.btbtt15.com`，即在 `/btzj/forum-index-fid-950` 后加上 `?domain=btbtt15.com`，此时路由为 [`/btzj/forum-index-fid-950?domain=btbtt15.com`](https://rsshub.app/btzj/forum-index-fid-950?domain=btbtt15.com)\n\n目前，你可以选择的域名有 `btbtt10-20.com` 共 10 个，或 `88btbbt.com`，该站也提供了专用网址查询工具。详见 [此贴](https://www.btbtt20.com/thread-index-fid-2-tid-4550191.htm)\n:::",
  "example": "/btzj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 36,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，默认为首页"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "btbtt20.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-12T12:09:22.478Z",
      "errorMessage": "[GET] \"https://www.btbtt15.com\": <no response> fetch failed (unable to get local issuer certificate)\n",
      "id": "155957211745995779",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://btzj"
    },
    {
      "description": null,
      "errorAt": "2025-05-23T18:45:47.942Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.88btbtt.com\": <no response> fetch failed (getaddrinfo ENOTFOUND www.88btbtt.com)\n",
      "id": "148757739569766405",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://btzj/base"
    }
  ],
  "url": "btbtt20.com/"
}
```
