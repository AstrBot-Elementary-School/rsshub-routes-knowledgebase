# 百度 - 精品帖子

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/forum/good/:kw/:cid?/:sortBy?`
- Route Name: `精品帖子`
- Example: `/baidu/tieba/forum/good/女图`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `u3u`
- Source Location: `tieba/forum.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `kw`: 吧名
- `cid`: 精品分类，默认为 `0`（全部分类），如果不传 `cid` 则获取全部分类
- `sortBy`: 排序方式：`created`, `replied`。默认为 `created`


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
    "bbs"
  ],
  "example": "/baidu/tieba/forum/good/女图",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 85,
  "location": "tieba/forum.tsx",
  "maintainers": [
    "u3u"
  ],
  "name": "精品帖子",
  "parameters": {
    "cid": "精品分类，默认为 `0`（全部分类），如果不传 `cid` 则获取全部分类",
    "kw": "吧名",
    "sortBy": "排序方式：`created`, `replied`。默认为 `created`"
  },
  "path": [
    "/tieba/forum/good/:kw/:cid?/:sortBy?",
    "/tieba/forum/:kw/:sortBy?"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "本吧热帖: 1-最忧郁的入 2-今天心情不好想胡说八道 3-好久没联系的高中同桌突然联系我了 4-有没有聊聊天的 直接一点的那种 5-关于我开小号装纯情女高骗班上的??压抑?男这件事 6-《百度贴吧关于整治不良网络生态的公告》 7-鼠鼠我啊终于找到自己的大姐姐了? 8-江西彩礼局 9-我是老资历，按照俺们山东习俗，过年了小资历得给我磕头！ 10-为什么互助板块没有了 11-晚辈对我动手动脚怎么办 - Powered by RSSHub",
      "errorAt": "2026-02-25T03:24:21.114Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/f?kw=%25E5%25AD%2599%25E7%25AC%2591%25E5%25B7%259D&tab=good&cid=0\": 403 Forbidden\n",
      "id": "59474368564173828",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/f?kw=%E5%AD%99%E7%AC%91%E5%B7%9D",
      "title": "孙笑川吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/forum/good/%E5%AD%99%E7%AC%91%E5%B7%9D"
    },
    {
      "description": "本吧热帖: 1-是不是把成人内容里的成人换成儿童不就是不是成人内容了 2-结婚的都是新人，那旧的呢？ 3-鸡蛋加鸡肉算不算母女盖饭 4-没人觉得卖油翁很嘉豪吗 5-撸管算不算把握裆下 6-新水楼，在此外水贴一律90天 7-其实每个人都有时空倒流的能力 8-标题五个字 9-为什么法律事务所只要律师不要法师 - Powered by RSSHub",
      "errorAt": "2026-05-08T19:57:08.036Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/f?kw=%25E5%25BC%25B1%25E6%2599%25BA&tab=good&cid=0\": 403 Forbidden\n",
      "id": "84969943583648768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/f?kw=%E5%BC%B1%E6%99%BA",
      "title": "弱智吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/forum/good/%E5%BC%B1%E6%99%BA"
    }
  ]
}
```
