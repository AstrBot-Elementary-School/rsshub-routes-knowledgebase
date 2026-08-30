# DN.com - News

## Coverage
`index-only`

## Route
- Namespace: `dn`
- Namespace Name: `DN.com`
- Route Path: `/dn/:language/news/:category?`
- Route Name: `News`
- Example: `/dn/en-us/news`
- URL: `dn.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
#### Language

| English | 中文  |
| ------- | ----- |
| en-us   | zh-cn |

#### Category

| English Category     | 中文分类 | Category id |
| -------------------- | -------- | ----------- |
| The Latest           | 最新     |             |
| Industry Information | 行业资讯 | category-1  |
| Knowledge            | 域名知识 | category-2  |
| Investment           | 域名投资 | category-3  |

## Parameters
- `language`: Language, see below
- `category`: Category, see below, The Latest by default


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
    "new-media"
  ],
  "description": "#### Language\n\n| English | 中文  |\n| ------- | ----- |\n| en-us   | zh-cn |\n\n#### Category\n\n| English Category     | 中文分类 | Category id |\n| -------------------- | -------- | ----------- |\n| The Latest           | 最新     |             |\n| Industry Information | 行业资讯 | category-1  |\n| Knowledge            | 域名知识 | category-2  |\n| Investment           | 域名投资 | category-3  |",
  "example": "/dn/en-us/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 76,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, see below, The Latest by default",
    "language": "Language, see below"
  },
  "path": "/:language/news/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Dn域名资讯频道汇集最新的域名新闻资讯信息平台，为用户提供域名行业相关知识点、时下热门的域名信息，普及多方面的域名知识，了解域名行业最全面最专业的信息，全球优质域名出售购买管理就上Dn.com。 - Powered by RSSHub",
      "errorAt": "2025-07-22T01:56:22.467Z",
      "errorMessage": "502 \nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "65716150150661120",
      "image": "https://dn.com/assets/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://dn.com/zh-cn/news/",
      "title": "dn.com - 最新",
      "type": "feed",
      "url": "rsshub://dn/zh-cn/news"
    },
    {
      "description": "Dn domain name information channel brings together the latest domain name news and information platform to provide users with domain name industry-related knowledge points, the current popularity of domain name information, popularise a variety of domain name knowledge, to understand the domain name industry's most comprehensive and most professional information, the world's high-quality domain names for sale to buy management on Dn.com. - Powered by RSSHub",
      "errorAt": "2025-07-22T03:03:10.997Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "84170929169044480",
      "image": "https://dn.com/assets/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://dn.com/en-us/news/",
      "title": "dn.com - The Latest",
      "type": "feed",
      "url": "rsshub://dn/en-us/news"
    }
  ]
}
```
