# 中国食品药品检定研究院 - 国家药品监督管理局医疗器械标准管理中心 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/nifdc`
- Namespace Name: `中国食品药品检定研究院`
- Route Path: `/gov/nifdc/:path{.+}?`
- Route Name: `国家药品监督管理局医疗器械标准管理中心 - 通用`
- Example: `/gov/nifdc/bshff/ylqxbzhgl/qxggtzh`
- URL: `www.nifdc.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中 `https://www.nifdc.org.cn/nifdc/` 与 `/index.html` 之间的字段，下面是一个例子。

若订阅 [公告通告](https://www.nifdc.org.cn/nifdc/bshff/ylqxbzhgl/qxggtzh/index.html) 则将对应页面 URL <https://www.nifdc.org.cn/nifdc/bshff/ylqxbzhgl/qxggtzh/index.html> 中 `https://www.nifdc.org.cn/nifdc/` 和 `/index.html` 之间的字段 `bshff/ylqxbzhgl/qxggtzh` 作为路径填入。此时路由为 [`/gov/nifdc/bshff/ylqxbzhgl/qxggtzh`](https://rsshub.app/gov/nifdc/bshff/ylqxbzhgl/qxggtzh)

:::

## Parameters
- `path`: 路径，默认为公告通告


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nifdc.org.cn/nifdc/*path/index.html`
  - `www.nifdc.org.cn/nifdc/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中 `https://www.nifdc.org.cn/nifdc/` 与 `/index.html` 之间的字段，下面是一个例子。\n\n若订阅 [公告通告](https://www.nifdc.org.cn/nifdc/bshff/ylqxbzhgl/qxggtzh/index.html) 则将对应页面 URL <https://www.nifdc.org.cn/nifdc/bshff/ylqxbzhgl/qxggtzh/index.html> 中 `https://www.nifdc.org.cn/nifdc/` 和 `/index.html` 之间的字段 `bshff/ylqxbzhgl/qxggtzh` 作为路径填入。此时路由为 [`/gov/nifdc/bshff/ylqxbzhgl/qxggtzh`](https://rsshub.app/gov/nifdc/bshff/ylqxbzhgl/qxggtzh)\n\n:::",
  "example": "/gov/nifdc/bshff/ylqxbzhgl/qxggtzh",
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "国家药品监督管理局医疗器械标准管理中心 - 通用",
  "parameters": {
    "path": "路径，默认为公告通告"
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "www.nifdc.org.cn/nifdc/*path/index.html",
        "www.nifdc.org.cn/nifdc/*path"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中国药品检定研究院公告通知相关信息 - Powered by RSSHub",
      "errorAt": "2026-09-11T14:20:53.099Z",
      "errorMessage": "[GET] \"https://www.nifdc.org.cn/nifdc/bshff/ylqxbzhgl/qxggtzh/\": 526 <none>\n",
      "id": "1280244517156290560",
      "image": "https://www.nifdc.org.cn/nifdc/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.nifdc.org.cn/nifdc/bshff/ylqxbzhgl/qxggtzh/",
      "title": "公告通知",
      "type": "feed",
      "url": "rsshub://gov/nifdc/bshff/ylqxbzhgl/qxggtzh"
    }
  ]
}
```
