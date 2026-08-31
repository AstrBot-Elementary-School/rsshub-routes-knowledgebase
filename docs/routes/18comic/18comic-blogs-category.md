# 禁漫天堂 - 文庫

## Coverage
`index-only`

## Route
- Namespace: `18comic`
- Namespace Name: `禁漫天堂`
- Route Path: `/18comic/blogs/:category?`
- Route Name: `文庫`
- Example: `/18comic/blogs`
- URL: `jmcomic.group/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `blogs.ts`
- Source Module: `_None_`

## Description
分类

| 全部 | 紳夜食堂 | 遊戲文庫 | JG GAMES | 模型山下 |
| ---- | -------- | -------- | -------- | -------- |
|      | dinner   | raiders  | jg       | figure   |

## Parameters
- `category`: 分类，见下表，默认为空即全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jmcomic.group/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "分类\n\n| 全部 | 紳夜食堂 | 遊戲文庫 | JG GAMES | 模型山下 |\n| ---- | -------- | -------- | -------- | -------- |\n|      | dinner   | raiders  | jg       | figure   |",
  "example": "/18comic/blogs",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 22,
  "location": "blogs.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "文庫",
  "parameters": {
    "category": "分类，见下表，默认为空即全部"
  },
  "path": "/blogs/:category?",
  "radar": [
    {
      "source": [
        "jmcomic.group/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "最新的 Blogs - 免費成人H漫線上看 - Powered by RSSHub",
      "errorAt": "2026-08-26T05:01:41.246Z",
      "errorMessage": "[GET] \"https://jmcomic1.me/blogs\": 403 Forbidden\n",
      "id": "181721376290441216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jmcomic1.me/blogs",
      "title": "主頁 Blogs - 禁漫天堂",
      "type": "feed",
      "url": "rsshub://18comic/blogs"
    }
  ],
  "url": "jmcomic.group/"
}
```
