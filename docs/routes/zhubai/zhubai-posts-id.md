# 竹白 - 文章

## Coverage
`index-only`

## Route
- Namespace: `zhubai`
- Namespace Name: `竹白`
- Route Path: `/zhubai/posts/:id`
- Route Name: `文章`
- Example: `/zhubai/posts/via`
- URL: `zhubai.love`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `naixy28`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，默认值为`20`
:::

## Parameters
- `id`: `id` 为竹白主页 url 中的三级域名，如 via.zhubai.love 的 `id` 为 `via`


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
    "blog"
  ],
  "description": "::: tip\n在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，默认值为`20`\n:::",
  "example": "/zhubai/posts/via",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 952,
  "location": "index.ts",
  "maintainers": [
    "naixy28"
  ],
  "name": "文章",
  "parameters": {
    "id": "`id` 为竹白主页 url 中的三级域名，如 via.zhubai.love 的 `id` 为 `via`"
  },
  "path": "/posts/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "偷懒爱好者周刊，分享产品、工具、新鲜事，每周三在微信公众号“偷懒爱好者”首发，RSS: https://echosoar.github.io/weekly/atom.xml - Powered by RSSHub",
      "errorAt": "2025-04-25T07:06:41.675Z",
      "errorMessage": "[GET] \"https://toolight.zhubai.love/api/publications/toolight/posts?publication_id_type=token&limit=20\": 530 <none>\n[GET] \"https://toolight.zhubai.love/api/publications/toolight/posts?publication_id_type=token&limit=20\": 530 <none>\n[GET] \"https://toolight.zhubai.love/api/publications/toolight/posts?publication_id_type=token&limit=20\": 530 <none>\n",
      "id": "56207859813625856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://toolight.zhubai.love/",
      "title": "偷懒爱好者周刊",
      "type": "feed",
      "url": "rsshub://zhubai/posts/toolight"
    },
    {
      "description": "为独立创造者提供独立见解，帮助你发现新产品方向，启动和完善你的项目。 内容包含：新闻洞察、行业分析、文章推荐、工具分享、下饭视频。内容涉及：产品运营、市场分析、软件设计、技术开发、生活方式 每周更新 - Powered by RSSHub",
      "errorAt": "2025-04-25T06:33:14.128Z",
      "errorMessage": "[GET] \"https://decohack.zhubai.love/api/publications/decohack/posts?publication_id_type=token&limit=20\": 530 \n[GET] \"https://decohack.zhubai.love/api/publications/decohack/posts?publication_id_type=token&limit=20\": 530 <none>\n[GET] \"https://decohack.zhubai.love/api/publications/decohack/posts?publication_id_type=token&limit=20\": 530 <none>\n",
      "id": "56257976719318016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://decohack.zhubai.love/",
      "title": "DecoHack周刊",
      "type": "feed",
      "url": "rsshub://zhubai/posts/decohack"
    }
  ]
}
```
