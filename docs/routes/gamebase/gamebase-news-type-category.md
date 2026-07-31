# 遊戲基地 Gamebase - 新聞

## Coverage
`index-only`

## Route
- Namespace: `gamebase`
- Namespace Name: `遊戲基地 Gamebase`
- Route Path: `/gamebase/news/:type?/:category?`
- Route Name: `新聞`
- Example: `/gamebase/news`
- URL: `news.gamebase.com.tw`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
::: tip
若訂閱 [手機遊戲新聞](https://news.gamebase.com.tw/news/newslist?type=mobile)，網址為 `https://news.gamebase.com.tw/news/newslist?type=mobile`，請截取 `https://news.gamebase.com.tw/news/` 到末尾的部分 `newslist` 作為 `type` 參數填入，`mobile` 作為 `category` 參數填入，此時目標路由為 [`/gamebase/news/newslist/mobile`](https://rsshub.app/gamebase/news/newslist/mobile)。
:::

| newslist | r18list |
| -------- | ------- |

## Parameters
- `type`: 類型，見下表，預設為 newslist
- `category`: 分類，預設為 `all`，即全部，可在對應分類頁 URL 中找到


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
  - `news.gamebase.com.tw/news`
  - `news.gamebase.com.tw/news/:type`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若訂閱 [手機遊戲新聞](https://news.gamebase.com.tw/news/newslist?type=mobile)，網址為 `https://news.gamebase.com.tw/news/newslist?type=mobile`，請截取 `https://news.gamebase.com.tw/news/` 到末尾的部分 `newslist` 作為 `type` 參數填入，`mobile` 作為 `category` 參數填入，此時目標路由為 [`/gamebase/news/newslist/mobile`](https://rsshub.app/gamebase/news/newslist/mobile)。\n:::\n\n| newslist | r18list |\n| -------- | ------- |",
  "example": "/gamebase/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 52,
  "location": "news.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新聞",
  "parameters": {
    "category": "分類，預設為 `all`，即全部，可在對應分類頁 URL 中找到",
    "type": "類型，見下表，預設為 newslist"
  },
  "path": "/news/:type?/:category?",
  "radar": [
    {
      "source": [
        "news.gamebase.com.tw/news",
        "news.gamebase.com.tw/news/:type"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at runNextTicks (node:internal/process/task_queues:65:5)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "精選基地編輯每日為你帶來的電玩、動漫、娛樂遊戲最新新聞 - Powered by RSSHub",
      "errorAt": "2026-06-23T05:39:10.805Z",
      "errorMessage": "[GET] \"undefined\": <no response> Failed to parse URL from undefined (Invalid URL)\n[GET] \"undefined\": <no response> Failed to parse URL from undefined\n[GET] \"undefined\": <no response> Failed to parse URL from undefined (Invalid URL)\n",
      "id": "62600104047803392",
      "image": "https://image.gamebase.com.tw/gb_tw/static/logo_01.png",
      "ownerUserId": null,
      "siteUrl": "https://news.gamebase.com.tw/news",
      "title": "新聞 | 遊戲基地 Gamebase",
      "type": "feed",
      "url": "rsshub://gamebase/news"
    },
    {
      "description": "精選基地編輯每日為你帶來的電玩、動漫、娛樂遊戲最新新聞 - Powered by RSSHub",
      "errorAt": "2026-06-25T13:36:56.554Z",
      "errorMessage": "502 \n[GET] \"undefined\": <no response> Failed to parse URL from undefined (Invalid URL)\n",
      "id": "67001925811204096",
      "image": "https://image.gamebase.com.tw/gb_tw/static/logo_01.png",
      "ownerUserId": null,
      "siteUrl": "https://news.gamebase.com.tw/news",
      "title": "新聞 | 遊戲基地 Gamebase",
      "type": "feed",
      "url": "rsshub://gamebase/news/r18list"
    }
  ],
  "url": "news.gamebase.com.tw",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [手机游戏新闻](https://news.gamebase.com.tw/news/newslist?type=mobile)，网址为 `https://news.gamebase.com.tw/news/newslist?type=mobile`，请截取 `https://news.gamebase.com.tw/news/` 到末尾的部分 `newslist` 作为 `type` 参数填入，`mobile` 作为 `category` 参数填入，此时目标路由为 [`/gamebase/news/newslist/mobile`](https://rsshub.app/gamebase/news/newslist/mobile)。\n:::\n\n| newslist | r18list |\n| -------- | ------- |",
    "name": "新闻",
    "parameters": {
      "category": "分类，默认为 `all`，即全部，可在对应分类页 URL 中找到",
      "type": "类型，见下表，默认为 newslist"
    }
  }
}
```
