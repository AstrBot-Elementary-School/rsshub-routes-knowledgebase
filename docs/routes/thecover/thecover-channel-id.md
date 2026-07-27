# 封面新闻 - 频道

## Coverage
`index-only`

## Route
- Namespace: `thecover`
- Namespace Name: `封面新闻`
- Route Path: `/thecover/channel/:id?`
- Route Name: `频道`
- Example: `/thecover/channel/3560`
- URL: `thecover.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `yuxinliu-alex`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
| 天下 | 四川 | 辟谣 | 国际 | 云招考 | 30 秒 | 拍客 | 体育 | 国内 | 帮扶铁军 | 文娱 | 宽窄 | 商业 | 千面 | 封面号 |
| ---- | ---- | ---- | ---- | ------ | ----- | ---- | ---- | ---- | -------- | ---- | ---- | ---- | ---- | ------ |
| 3892 | 3560 | 3909 | 3686 | 11     | 3902  | 3889 | 3689 | 1    | 4002     | 12   | 46   | 4    | 21   | 17     |

## Parameters
- `id`: 对应id,可在频道链接中获取，默认为3892


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
  "description": "| 天下 | 四川 | 辟谣 | 国际 | 云招考 | 30 秒 | 拍客 | 体育 | 国内 | 帮扶铁军 | 文娱 | 宽窄 | 商业 | 千面 | 封面号 |\n| ---- | ---- | ---- | ---- | ------ | ----- | ---- | ---- | ---- | -------- | ---- | ---- | ---- | ---- | ------ |\n| 3892 | 3560 | 3909 | 3686 | 11     | 3902  | 3889 | 3689 | 1    | 4002     | 12   | 46   | 4    | 21   | 17     |",
  "example": "/thecover/channel/3560",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 369,
  "location": "channel.ts",
  "maintainers": [
    "yuxinliu-alex"
  ],
  "name": "频道",
  "parameters": {
    "id": "对应id,可在频道链接中获取，默认为3892"
  },
  "path": "/channel/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "封面新闻作为华西都市报深度融合转型和打造新型主流媒体的载体，牢固确立移动优先战略，创新移动新闻产品，打造移动传播矩阵，封面新闻的传播力、引导力、影响力和公信力不断得到各方肯定。封面新闻突破千万的用户下载量，呈现出以四川为主阵地的全国分布态势，用户年龄构成以20-35岁为主，“亿万年轻人的生活方式”的定位初步得到体现。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66376390508402688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.thecover.cn/channel_3686",
      "title": "国际-封面新闻",
      "type": "feed",
      "url": "rsshub://thecover/channel/3686"
    },
    {
      "description": "封面新闻作为华西都市报深度融合转型和打造新型主流媒体的载体，牢固确立移动优先战略，创新移动新闻产品，打造移动传播矩阵，封面新闻的传播力、引导力、影响力和公信力不断得到各方肯定。封面新闻突破千万的用户下载量，呈现出以四川为主阵地的全国分布态势，用户年龄构成以20-35岁为主，“亿万年轻人的生活方式”的定位初步得到体现。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61227956309027840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.thecover.cn/channel_3560",
      "title": "四川-封面新闻",
      "type": "feed",
      "url": "rsshub://thecover/channel/3560"
    }
  ]
}
```
