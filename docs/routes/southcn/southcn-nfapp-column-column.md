# 南方网 - 南方 +（按栏目 ID）

## Coverage
`index-only`

## Route
- Namespace: `southcn`
- Namespace Name: `南方网`
- Route Path: `/southcn/nfapp/column/:column?`
- Route Name: `南方 +（按栏目 ID）`
- Example: `/southcn/nfapp/column/38`
- URL: `nfapp.southcn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `nfapp/column.ts`
- Source Module: `_None_`

## Description
::: tip
若此处输入的是栏目 ID（而非南方号 ID），则该接口会返回与输入栏目相关联栏目的文章。例如，输入栏目 ID `38`（广州），则返回的结果还会包含 ID 为 `3547`（市长报道集）的文章。
:::

1. `pc.nfapp.southcn.com` 下的文章页面，可通过 url 查看，例：`http://pc.nfapp.southcn.com/13707/7491109.html` 的栏目 ID 为 `13707`。
2. `static.nfapp.southcn.com` 下的文章页面，可查看网页源代码，搜索 `columnid`。
3. <https://m.nfapp.southcn.com/column/all> 列出了部分栏目，`id` 即为栏目 ID。

## Parameters
- `column`: 栏目或南方号 ID


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
    "traditional-media"
  ],
  "description": "::: tip\n若此处输入的是栏目 ID（而非南方号 ID），则该接口会返回与输入栏目相关联栏目的文章。例如，输入栏目 ID `38`（广州），则返回的结果还会包含 ID 为 `3547`（市长报道集）的文章。\n:::\n\n1. `pc.nfapp.southcn.com` 下的文章页面，可通过 url 查看，例：`http://pc.nfapp.southcn.com/13707/7491109.html` 的栏目 ID 为 `13707`。\n2. `static.nfapp.southcn.com` 下的文章页面，可查看网页源代码，搜索 `columnid`。\n3. <https://m.nfapp.southcn.com/column/all> 列出了部分栏目，`id` 即为栏目 ID。",
  "example": "/southcn/nfapp/column/38",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "nfapp/column.ts",
  "maintainers": [
    "TimWu007"
  ],
  "name": "南方 +（按栏目 ID）",
  "parameters": {
    "column": "栏目或南方号 ID"
  },
  "path": "/nfapp/column/:column?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "南方+ - 广州 - Powered by RSSHub",
      "errorAt": "2025-08-15T07:02:38.916Z",
      "errorMessage": "[GET] \"https://api.nfapp.southcn.com/nanfang_if/getColumn?columnId=38\": 405 Not Allowed\n",
      "id": "158878918138745856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.nfapp.southcn.com/38",
      "title": "南方+ - 广州",
      "type": "feed",
      "url": "rsshub://southcn/nfapp/column"
    },
    {
      "description": "南方+ - 汕尾 - Powered by RSSHub",
      "errorAt": "2025-08-15T07:03:37.676Z",
      "errorMessage": "[GET] \"https://api.nfapp.southcn.com/nanfang_if/getColumn?columnId=74\": 405 Not Allowed\n",
      "id": "177651896288583690",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.nfapp.southcn.com/74",
      "title": "南方+ - 汕尾",
      "type": "feed",
      "url": "rsshub://southcn/nfapp/column/74"
    }
  ]
}
```
