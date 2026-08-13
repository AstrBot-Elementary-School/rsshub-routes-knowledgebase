# Gelbooru - 标签查询

## Coverage
`index-only`

## Route
- Namespace: `gelbooru`
- Namespace Name: `Gelbooru`
- Route Path: `/gelbooru/post/:tags?/:quality?`
- Route Name: `标签查询`
- Example: `/gelbooru/post/1girl rating:general`
- URL: `gelbooru.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `magicFeirl`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
- 默认查询: `/gelbooru/post` 功能等同查询 Gelbooru 网站最新的投稿
- 单标签查询: `/gelbooru/post/1girl` 查询 `1girl` 的最新投稿
- 多标签查询: `/gelbooru/post/1girl school_uniform rating:general`
- 指定为原图: `/gelbooru/post/1girl school_uniform rating:general/orig`
- 更多例子：请参考 Gelbooru 官方 wiki <https://gelbooru.com/index.php?page=wiki&s=&s=view&id=25921>

**可选的 URL 参数**

- limit 页面返回数据量，默认 40，可选 1 \~ 100

e.g.: `/gelbooru/post?limit=20&`

## Parameters
- `tags`: 要搜索的标签，多个标签用 ` `（空格）隔开
- `quality`: {"default": "sample", "description": "图片质量，可选值为 `sample`（压缩后的图片，推荐值） 或 `orig`（原图），默认为 `sample`"}


## Features
- `requireConfig`: [{"description": "Gelbooru 偶尔会开启 API 认证，需配合 `GELBOORU_USER_ID`，从 `https://gelbooru.com/index.php?page=account&s=options` 获取", "name": "GELBOORU_API_KEY", "optional": true}, {"description": "参见 `GELBOORU_API_KEY`", "name": "GELBOORU_USER_ID", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `gelbooru.com/index.php`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "- 默认查询: `/gelbooru/post` 功能等同查询 Gelbooru 网站最新的投稿\n- 单标签查询: `/gelbooru/post/1girl` 查询 `1girl` 的最新投稿\n- 多标签查询: `/gelbooru/post/1girl school_uniform rating:general`\n- 指定为原图: `/gelbooru/post/1girl school_uniform rating:general/orig`\n- 更多例子：请参考 Gelbooru 官方 wiki <https://gelbooru.com/index.php?page=wiki&s=&s=view&id=25921>\n\n**可选的 URL 参数**\n\n- limit 页面返回数据量，默认 40，可选 1 \\~ 100\n\ne.g.: `/gelbooru/post?limit=20&`",
  "example": "/gelbooru/post/1girl rating:general",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "Gelbooru 偶尔会开启 API 认证，需配合 `GELBOORU_USER_ID`，从 `https://gelbooru.com/index.php?page=account&s=options` 获取",
        "name": "GELBOORU_API_KEY",
        "optional": true
      },
      {
        "description": "参见 `GELBOORU_API_KEY`",
        "name": "GELBOORU_USER_ID",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 21,
  "location": "post.ts",
  "maintainers": [
    "magicFeirl"
  ],
  "name": "标签查询",
  "parameters": {
    "quality": {
      "default": "sample",
      "description": "图片质量，可选值为 `sample`（压缩后的图片，推荐值） 或 `orig`（原图），默认为 `sample`"
    },
    "tags": "要搜索的标签，多个标签用 ` `（空格）隔开"
  },
  "path": "/post/:tags?/:quality?",
  "radar": [
    {
      "source": [
        "gelbooru.com/index.php"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Gelbooru post list - Powered by RSSHub",
      "errorAt": "2025-06-15T17:36:00.154Z",
      "errorMessage": "[GET] \"https://gelbooru.com/index.php?api_key=&json=1&limit=40&page=dapi&q=index&s=post&tags=sex&user_id=\": 401 Unauthorized\n",
      "id": "127398870895944704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gelbooru.com/index.php?page=post&s=list&tags=sex",
      "title": "sex - gelbooru.com",
      "type": "feed",
      "url": "rsshub://gelbooru/post/sex"
    },
    {
      "description": "Gelbooru post list - Powered by RSSHub",
      "errorAt": "2025-06-15T15:32:07.406Z",
      "errorMessage": "[GET] \"https://gelbooru.com/index.php?api_key=&json=1&limit=40&page=dapi&q=index&s=post&tags=1girl+rating%3Ageneral&user_id=\": 401 Unauthorized\n",
      "id": "132064394430128128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gelbooru.com/index.php?page=post&s=list&tags=1girl%20rating:general",
      "title": "1girl rating:general - gelbooru.com",
      "type": "feed",
      "url": "rsshub://gelbooru/post/1girl%20rating:general"
    }
  ],
  "view": 2
}
```
