# 拷贝漫画 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `copymanga`
- Namespace Name: `拷贝漫画`
- Route Path: `/copymanga/comic/:id/:chapterCnt?`
- Route Name: `漫画更新`
- Example: `/copymanga/comic/dianjuren/5`
- URL: `copymanga.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `btdwv, marvolo666`
- Source Location: `comic.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 漫画ID
- `chapterCnt`: 返回章节的数量，默认为 `10`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/copymanga/comic/dianjuren/5",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 156,
  "location": "comic.tsx",
  "maintainers": [
    "btdwv",
    "marvolo666"
  ],
  "name": "漫画更新",
  "parameters": {
    "chapterCnt": "返回章节的数量，默认为 `10`",
    "id": "漫画ID"
  },
  "path": "/comic/:id/:chapterCnt?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "拥有财富、名声、权力，这世界上的一切的男人 “海贼王”哥尔·D·罗杰，在被行刑受死之前说了一句话，让全世界的人都涌向了大海。“想要我的宝藏吗？如果想要的话，那就到海上去找吧，我全部都放在那里。”，世界开始迎接“大海贼时代”的来临 。 时值“大海贼时代”，为了寻找传说中海贼王罗杰所留下的大秘宝“ONE PIECE”，无数海贼扬起旗帜，互相争斗。有一个梦想成为海盗的少年叫路飞，他因误食“恶魔果实”而成为了橡皮人，在获得超人能力的同时付出了一辈子无法游泳的代价。十年后，路飞为实现与因救他而断臂的香克斯的约定而出海，他在旅途中不断寻找志同道合的伙伴，开始了以成为海贼王为目标的伟大的冒险旅程。 - Powered by RSSHub",
      "errorAt": "2025-06-19T08:22:17.816Z",
      "errorMessage": "[GET] \"https://www.mangacopy.com/api/v3/comic/haizeiwang/group/default/chapters?limit=500&offset=0\": 404 Not Found\n",
      "id": "60347822042442752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mangacopy.com/comic/haizeiwang",
      "title": "拷贝漫画 - 海贼王",
      "type": "feed",
      "url": "rsshub://copymanga/comic/haizeiwang"
    },
    {
      "description": "炎拳作者登陸周刊少年JUMP，震蕩世界的黑暗英雄物語。 被騙得負債累累、過著貧窮生活的少年電次， 與電鋸惡魔啵奇塔一起做惡魔獵人，勉強活了下來， 但是有一天卻被殘暴的惡魔盯上了……？！ - Powered by RSSHub",
      "errorAt": "2025-06-19T07:09:50.996Z",
      "errorMessage": "[GET] \"https://www.mangacopy.com/api/v3/comic/dianjuren/group/default/chapters?limit=500&offset=0\": 404 Not Found\n",
      "id": "71910097657797632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mangacopy.com/comic/dianjuren",
      "title": "拷贝漫画 - 電鋸人",
      "type": "feed",
      "url": "rsshub://copymanga/comic/dianjuren"
    }
  ]
}
```
