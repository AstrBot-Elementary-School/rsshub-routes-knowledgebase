# zyw - 今日热榜

## Coverage
`index-only`

## Route
- Namespace: `zyw`
- Namespace Name: `zyw`
- Route Path: `/zyw/hot/:site?`
- Route Name: `今日热榜`
- Example: `/zyw/hot`
- URL: `hot.zyw.asia`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
::: tip
全部站点请见 [此处](https://hot.zyw.asia/#/list)
:::

| 哔哩哔哩 | 微博 | 知乎 | 36 氪 | 百度 | 少数派 | IT 之家 | 澎湃新闻 | 今日头条 | 百度贴吧 | 稀土掘金 | 腾讯新闻 |
| -------- | ---- | ---- | ----- | ---- | ------ | ------- | -------- | -------- | -------- | -------- | -------- |

## Parameters
- `site`: 站点，见下表，默认为空，即全部


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
  "description": "::: tip\n全部站点请见 [此处](https://hot.zyw.asia/#/list)\n:::\n\n| 哔哩哔哩 | 微博 | 知乎 | 36 氪 | 百度 | 少数派 | IT 之家 | 澎湃新闻 | 今日头条 | 百度贴吧 | 稀土掘金 | 腾讯新闻 |\n| -------- | ---- | ---- | ----- | ---- | ------ | ------- | -------- | -------- | -------- | -------- | -------- |",
  "example": "/zyw/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "hot.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "今日热榜",
  "parameters": {
    "site": "站点，见下表，默认为空，即全部"
  },
  "path": "/hot/:site?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-19T04:04:28.638Z",
      "errorMessage": "[GET] \"https://hot.zyw.asia\": <no response> fetch failed (getaddrinfo ENOTFOUND hot.zyw.asia)\n",
      "id": "158366990849381377",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://zyw/hot"
    }
  ]
}
```
