# 大麦网 - 票务更新

## Coverage
`index-only`

## Route
- Namespace: `damai`
- Namespace Name: `大麦网`
- Route Path: `/damai/activity/:city/:category/:subcategory/:keyword?`
- Route Name: `票务更新`
- Example: `/damai/activity/上海/音乐会/全部/柴可夫斯基`
- URL: `search.damai.cn`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `hoilc, Konano`
- Source Location: `activity.tsx`
- Source Module: `_None_`

## Description
城市、分类名、子分类名，请参见[大麦网搜索页面](https://search.damai.cn/search.htm)

## Parameters
- `city`: 城市，如果不需要限制，请填入`全部`
- `category`: 分类，如果不需要限制，请填入`全部`
- `subcategory`: 子分类，如果不需要限制，请填入`全部`
- `keyword`: 搜索关键字，置空为不限制


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
    "shopping"
  ],
  "description": "城市、分类名、子分类名，请参见[大麦网搜索页面](https://search.damai.cn/search.htm)",
  "example": "/damai/activity/上海/音乐会/全部/柴可夫斯基",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 459,
  "location": "activity.tsx",
  "maintainers": [
    "hoilc",
    "Konano"
  ],
  "name": "票务更新",
  "parameters": {
    "category": "分类，如果不需要限制，请填入`全部`",
    "city": "城市，如果不需要限制，请填入`全部`",
    "keyword": "搜索关键字，置空为不限制",
    "subcategory": "子分类，如果不需要限制，请填入`全部`"
  },
  "path": "/activity/:city/:category/:subcategory/:keyword?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "大麦网票务 - 上海 - 全部分类 - Powered by RSSHub",
      "errorAt": "2025-11-12T11:47:58.974Z",
      "errorMessage": "Cannot read properties of undefined (reading 'resultData')\n",
      "id": "41467081627747335",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.damai.cn/search.htm",
      "title": "大麦网票务 - 上海 - 全部分类",
      "type": "feed",
      "url": "rsshub://damai/activity/%E4%B8%8A%E6%B5%B7/%E5%85%A8%E9%83%A8/%E5%85%A8%E9%83%A8"
    },
    {
      "description": "大麦网票务 - 杭州 - 全部分类 - Powered by RSSHub",
      "errorAt": "2025-11-12T12:09:44.623Z",
      "errorMessage": "Cannot read properties of undefined (reading 'resultData')\n",
      "id": "68567136601187328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.damai.cn/search.htm",
      "title": "大麦网票务 - 杭州 - 全部分类",
      "type": "feed",
      "url": "rsshub://damai/activity/%E6%9D%AD%E5%B7%9E/%E5%85%A8%E9%83%A8/%E5%85%A8%E9%83%A8"
    }
  ]
}
```
