# SegmentFault - 博客

## Coverage
`index-only`

## Route
- Namespace: `segmentfault`
- Namespace Name: `SegmentFault`
- Route Path: `/segmentfault/blogs/:tag`
- Route Name: `博客`
- Example: `/segmentfault/blogs/go`
- URL: `segmentfault.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `shiluanzzz`
- Source Location: `blogs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: 标签名称，在 [标签](https://segmentfault.com/tags) 中可以找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `segmentfault.com/t/:tag/blogs`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/segmentfault/blogs/go",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "blogs.ts",
  "maintainers": [
    "shiluanzzz"
  ],
  "name": "博客",
  "parameters": {
    "tag": "标签名称，在 [标签](https://segmentfault.com/tags) 中可以找到"
  },
  "path": "/blogs/:tag",
  "radar": [
    {
      "source": [
        "segmentfault.com/t/:tag/blogs"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "segmentfault-Blogs-java - Powered by RSSHub",
      "errorAt": "2024-10-24T06:06:02.559Z",
      "errorMessage": "[GET] \"https://segmentfault.com/gateway/tag/java/articles?loadMoreType=pagination&initData=true&page=1&sort=newest&pageSize=30\": 403 Forbidden\n",
      "id": "71828492942775296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://segmentfault.com/t/java/blogs",
      "title": "segmentfault-Blogs-java",
      "type": "feed",
      "url": "rsshub://segmentfault/blogs/java"
    }
  ]
}
```
