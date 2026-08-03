# 证券时报网 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `stcn`
- Namespace Name: `证券时报网`
- Route Path: `/stcn/article/list/kx`
- Route Name: `快讯`
- Example: `/stcn/article/list/kx`
- URL: `www.stcn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `kx.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.stcn.com/article/list/kx.html`
- `target`: `/article/list/kx`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/stcn/article/list/kx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 85,
  "location": "kx.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "path": "/article/list/kx",
  "radar": [
    {
      "source": [
        "www.stcn.com/article/list/kx.html"
      ],
      "target": "/article/list/kx"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "人民财讯是由人民日报主管主办的全国性财经类日报《证券时报》倾力打造的快讯内容平台，专注于宏观要闻、股市动态、公司新闻、数据解读以及海外财经资讯等全方位财经信息。依托人民日报的权威平台支持与《证券时报》的专业深耕，“人民财讯”致力于为广大投资者提供权威、专业、及时且实用、有用、好用的财经资讯，满足用户对高质量财经信息的需求，成为数字化时代下高品质的财经信息平台。作为金融监管部门、上市公司，以及银行、保险、券商、基金等金融机构高度关注的核心媒体，“人民财讯”凭借精准的信息传递与深度的内容解读，赢得了机构投资者与个人投资者的广泛信赖。无论是政策解读、市场趋势分析，还是投资决策支持，“人民财讯”始终以高质量内容服务于财经领域的各方需求，彰显其不可替代的权威性与实用价值。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "121721328805569536",
      "image": "https://static-web.stcn.com/static/images/stcn.png",
      "ownerUserId": null,
      "siteUrl": "https://www.stcn.com/article/list/kx.html",
      "title": "7*24小时快讯，每日股市快讯，股市新闻播报-人民财讯快讯栏目",
      "type": "feed",
      "url": "rsshub://stcn/article/list/kx"
    }
  ],
  "url": "www.stcn.com",
  "view": 0
}
```
