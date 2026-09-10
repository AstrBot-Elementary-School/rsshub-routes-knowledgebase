# 国家药品监督管理局 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/nmpa`
- Namespace Name: `国家药品监督管理局`
- Route Path: `/gov/nmpa/:path{.+}`
- Route Name: `通用`
- Example: `/gov/nmpa/xxgk/ggtg`
- URL: `www.nmpa.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `generic.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中 `https://www.nmpa.gov.cn/` 与 `/index.html` 之间的字段，下面是一个例子。

若订阅 [公告通告](https://www.nmpa.gov.cn/xxgk/ggtg/index.html) 则将对应页面 URL <https://www.nmpa.gov.cn/xxgk/ggtg/index.html> 中 `https://www.nmpa.gov.cn/` 和 `/index.html` 之间的字段 `xxgk/ggtg` 作为路径填入。此时路由为 [`/gov/nmpa/xxgk/ggtg`](https://rsshub.app/gov/nmpa/xxgk/ggtg)

:::

## Parameters
- `path`: 路径，默认为公告通告


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nmpa.gov.cn/*path/index.html`
  - `www.nmpa.gov.cn/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中 `https://www.nmpa.gov.cn/` 与 `/index.html` 之间的字段，下面是一个例子。\n\n若订阅 [公告通告](https://www.nmpa.gov.cn/xxgk/ggtg/index.html) 则将对应页面 URL <https://www.nmpa.gov.cn/xxgk/ggtg/index.html> 中 `https://www.nmpa.gov.cn/` 和 `/index.html` 之间的字段 `xxgk/ggtg` 作为路径填入。此时路由为 [`/gov/nmpa/xxgk/ggtg`](https://rsshub.app/gov/nmpa/xxgk/ggtg)\n\n:::",
  "example": "/gov/nmpa/xxgk/ggtg",
  "heat": 1,
  "location": "generic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，默认为公告通告"
  },
  "path": "/:path{.+}",
  "radar": [
    {
      "source": [
        "www.nmpa.gov.cn/*path/index.html",
        "www.nmpa.gov.cn/*path"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-12T15:31:54.965Z",
      "errorMessage": "[GET] \"https://www.nmpa.gov.cn/xxgk/ggtg/index.html\": 412 Precondition Failed\n",
      "id": "189349754051776515",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://gov/nmpa/xxgk/ggtg"
    }
  ]
}
```
