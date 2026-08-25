# 拉勾网 - 职位招聘

## Coverage
`index-only`

## Route
- Namespace: `lagou`
- Namespace Name: `拉勾网`
- Route Path: `/lagou/jobs/:position/:city`
- Route Name: `职位招聘`
- Example: `/lagou/jobs/JavaScript/上海`
- URL: `www.lagou.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `hoilc`
- Source Location: `jobs.ts`
- Source Module: `_None_`

## Description
::: tip
拉勾网官方提供职位的[邮件订阅](https://www.lagou.com/s/subscribe.html)，请根据自身需要选择使用。
:::

## Parameters
- `position`: 职位名，可以参考[拉勾网首页](https://www.lagou.com)的职位列表
- `city`: 城市名，请参考[拉勾网支持的全部城市](https://www.lagou.com/jobs/allCity.html)


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\n拉勾网官方提供职位的[邮件订阅](https://www.lagou.com/s/subscribe.html)，请根据自身需要选择使用。\n:::",
  "example": "/lagou/jobs/JavaScript/上海",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "jobs.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "职位招聘",
  "parameters": {
    "city": "城市名，请参考[拉勾网支持的全部城市](https://www.lagou.com/jobs/allCity.html)",
    "position": "职位名，可以参考[拉勾网首页](https://www.lagou.com)的职位列表"
  },
  "path": "/jobs/:position/:city",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
