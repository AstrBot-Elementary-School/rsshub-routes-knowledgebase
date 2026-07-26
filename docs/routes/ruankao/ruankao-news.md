# 中国计算机职业技术资格考试 - 软考动态

## Coverage
`index-only`

## Route
- Namespace: `ruankao`
- Namespace Name: `中国计算机职业技术资格考试`
- Route Path: `/ruankao/news`
- Route Name: `软考动态`
- Example: `/ruankao/news`
- URL: `www.ruankao.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `PrinOrange`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
**注意：** 官方网站限制了国外网络请求，可能需要通过部署在中国大陆内的 RSSHub 实例访问。

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `title`: `计算机职业技术资格考试（软考）动态`
- `source`:
  - `www.ruankao.org.cn/index/work`
  - `www.ruankao.org.cn`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "**注意：** 官方网站限制了国外网络请求，可能需要通过部署在中国大陆内的 RSSHub 实例访问。",
  "example": "/ruankao/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 31,
  "location": "news.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "软考动态",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.ruankao.org.cn/index/work",
        "www.ruankao.org.cn"
      ],
      "target": "/news",
      "title": "计算机职业技术资格考试（软考）动态"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "计算机职业技术资格考试（软考）消息推送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "97983929811275776",
      "image": "https://bm.ruankao.org.cn/asset/image/public/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.ruankao.org.cn/index/work.html",
      "title": "计算机职业技术资格考试（软考）动态",
      "type": "feed",
      "url": "rsshub://ruankao/news"
    }
  ]
}
```
