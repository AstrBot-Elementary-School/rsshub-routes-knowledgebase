# 快递 100 - 快递订单追踪

## Coverage
`index-only`

## Route
- Namespace: `kuaidi100`
- Namespace Name: `快递 100`
- Route Path: `/kuaidi100/track/:number/:id/:phone?`
- Route Name: `快递订单追踪`
- Example: `/kuaidi100/track/shunfeng/SF1007896781640/0383`
- URL: `kuaidi100.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `NeverBehave`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
快递公司代号如果不能确定，可通过下方快递列表获得。

::: warning

1. 构造链接前请确认所有参数正确：错误`快递公司 - 订单号`组合将会缓存信息一小段时间防止产生无用查询
2. 正常查询的订单在未签收状态下不会被缓存：请控制查询频率
3. 订单完成后请尽快取消订阅，避免资源浪费

:::

## Parameters
- `number`: 快递公司代号
- `id`: 订单号
- `phone`: 手机号后四位（仅顺丰）


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
    "other"
  ],
  "description": "快递公司代号如果不能确定，可通过下方快递列表获得。\n\n::: warning\n\n1. 构造链接前请确认所有参数正确：错误`快递公司 - 订单号`组合将会缓存信息一小段时间防止产生无用查询\n2. 正常查询的订单在未签收状态下不会被缓存：请控制查询频率\n3. 订单完成后请尽快取消订阅，避免资源浪费\n\n:::",
  "example": "/kuaidi100/track/shunfeng/SF1007896781640/0383",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "NeverBehave"
  ],
  "name": "快递订单追踪",
  "parameters": {
    "id": "订单号",
    "number": "快递公司代号",
    "phone": "手机号后四位（仅顺丰）"
  },
  "path": "/track/:number/:id/:phone?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
