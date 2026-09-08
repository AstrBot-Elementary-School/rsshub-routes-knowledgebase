# 其乐 - 论坛

## Coverage
`index-only`

## Route
- Namespace: `keylol`
- Namespace Name: `其乐`
- Route Path: `/keylol/:path`
- Route Name: `论坛`
- Example: `/keylol/f161-1`
- URL: `keylol.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk, kennyfong19931`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [热点聚焦](https://keylol.com/f161-1)，网址为 `https://keylol.com/f161-1`。截取 `https://keylol.com/` 到末尾的部分 `f161-1` 作为参数，此时路由为 [`/keylol/f161-1`](https://rsshub.app/keylol/f161-1)。
若订阅子分类 [试玩免费 - 热点聚焦](https://keylol.com/forum.php?mod=forumdisplay\&fid=161\&filter=typeid\&typeid=459)，网址为 `https://keylol.com/forum.php?mod=forumdisplay&fid=161&filter=typeid&typeid=459`。提取`fid`及`typeid` 作为参数，此时路由为 [`/keylol/fid=161&typeid=459`](https://rsshub.app/keylol/fid=161\&typeid=459)。注意不要包括`filter`，会调用[全局的内容过滤](https://docs.rsshub.app/guide/parameters#filtering)。
:::

## Parameters
- `path`: 路径，默认为热点聚焦


## Features
- `requireConfig`: [{"description": "配置后可抓取具有阅读权限的帖子內容", "name": "KEYLOL_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `keylol.com/:path`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [热点聚焦](https://keylol.com/f161-1)，网址为 `https://keylol.com/f161-1`。截取 `https://keylol.com/` 到末尾的部分 `f161-1` 作为参数，此时路由为 [`/keylol/f161-1`](https://rsshub.app/keylol/f161-1)。\n若订阅子分类 [试玩免费 - 热点聚焦](https://keylol.com/forum.php?mod=forumdisplay\\&fid=161\\&filter=typeid\\&typeid=459)，网址为 `https://keylol.com/forum.php?mod=forumdisplay&fid=161&filter=typeid&typeid=459`。提取`fid`及`typeid` 作为参数，此时路由为 [`/keylol/fid=161&typeid=459`](https://rsshub.app/keylol/fid=161\\&typeid=459)。注意不要包括`filter`，会调用[全局的内容过滤](https://docs.rsshub.app/guide/parameters#filtering)。\n:::",
  "example": "/keylol/f161-1",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "配置后可抓取具有阅读权限的帖子內容",
        "name": "KEYLOL_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 102,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "kennyfong19931"
  ],
  "name": "论坛",
  "parameters": {
    "path": "路径，默认为热点聚焦"
  },
  "path": "/:path",
  "radar": [
    {
      "source": [
        "keylol.com/:path"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "热点聚焦 ,其乐 Keylol - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58758095877738496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://keylol.com/forum.php?fid=161&filter=author&mod=forumdisplay&orderby=dateline",
      "title": "热点聚焦 - 其乐 Keylol",
      "type": "feed",
      "url": "rsshub://keylol/f161-1"
    },
    {
      "description": "购物心得 ,其乐 Keylol - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77664835339807744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://keylol.com/forum.php?fid=234&filter=author&mod=forumdisplay&orderby=dateline&typeid=786",
      "title": "临时工 - 购物心得 - 其乐 Keylol",
      "type": "feed",
      "url": "rsshub://keylol/fid=234&typeid=786"
    }
  ]
}
```
