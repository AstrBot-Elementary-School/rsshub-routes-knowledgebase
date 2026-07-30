# 全球主机监控 - CloudFlareYes

## Coverage
`index-only`

## Route
- Namespace: `hostmonit`
- Namespace Name: `全球主机监控`
- Route Path: `/hostmonit/cloudflareyes/:type?`
- Route Name: `CloudFlareYes`
- Example: `/hostmonit/cloudflareyes`
- URL: `stock.hostmonit.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `cloudflareyes.tsx`
- Source Module: `_None_`

## Description
| v4 | v6 |
| -- | -- |
|    | v6 |

## Parameters
- `type`: 类型，见下表，默认为 v4


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| v4 | v6 |\n| -- | -- |\n|    | v6 |",
  "example": "/hostmonit/cloudflareyes",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "cloudflareyes.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "CloudFlareYes",
  "parameters": {
    "type": "类型，见下表，默认为 v4"
  },
  "path": "/cloudflareyes/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(6) ] to not include 'hostmonit.com-CloudFlareYes-198.41.20…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "全球主机VPS库存监控补货通知 Stock Monitor 绿云GreenCloudVPS库存监控 搬瓦工BandwagonHost库存监控 斯巴达SpartanHost库存监控 CloudCone库存监控 AlphaVps库存监控 BuyVm 库存监控 Dmit库存监控 xTom/V.PS库存监控 RackNerd库存监控 国外VPS 云服务器 虚拟主机 便宜VPS VPS测评 VPS使用教程 资源分享 - Powered by RSSHub",
      "errorAt": "2025-10-29T13:51:17.390Z",
      "errorMessage": "[GET] \"https://stock.hostmonit.com/CloudFlareYes\": 403 Forbidden\n",
      "id": "67509716866914307",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://stock.hostmonit.com/CloudFlareYes",
      "title": "全球主机监控 - CloudFlareYes",
      "type": "feed",
      "url": "rsshub://hostmonit/cloudflareyes"
    }
  ]
}
```
