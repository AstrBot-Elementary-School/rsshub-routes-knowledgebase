# AcFun - 番剧

## Coverage
`index-only`

## Route
- Namespace: `acfun`
- Namespace Name: `AcFun`
- Route Path: `/acfun/bangumi/:id/:embed?`
- Route Name: `番剧`
- Example: `/acfun/bangumi/6000617`
- URL: `www.acfun.cn`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `xyqfer`
- Source Location: `bangumi.ts`
- Source Module: `_None_`

## Description
::: tip
番剧 id 不包含开头的 aa。
例如：`https://www.acfun.cn/bangumi/aa6000617` 的番剧 id 是 6000617，不包括开头的 aa。
:::

## Parameters
- `id`: 番剧 id
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
    "anime"
  ],
  "description": "::: tip\n番剧 id 不包含开头的 aa。\n例如：`https://www.acfun.cn/bangumi/aa6000617` 的番剧 id 是 6000617，不包括开头的 aa。\n:::",
  "example": "/acfun/bangumi/6000617",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59,
  "location": "bangumi.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "番剧",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "id": "番剧 id"
  },
  "path": "/bangumi/:id/:embed?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "AcFun番剧相关信息请关注微博@AcFun新番 2018年的某一天，少女们和另一个世界的“自己”相遇了——。 高中生土宫明日架与朋友们隶属“矿石电台研究会”，在一次游戏中，她们效仿都市传说举行了“某个仪式”。不料仪式打开了平行世界，她们踏入了与日常截然不同的领域，新世界的大门就此打开。 - Powered by RSSHub",
      "errorAt": "2025-01-14T11:12:16.725Z",
      "errorMessage": "[GET] \"https://www.acfun.cn/bangumi/aa5022158\": 404 Not Found\n",
      "id": "58871334458500096",
      "image": "http://imgs.aixifan.com/cms/2019_01_17/1547693206599.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.acfun.cn/bangumi/aa5022158",
      "title": "茜色少女",
      "type": "feed",
      "url": "rsshub://acfun/bangumi/5022158"
    },
    {
      "description": "下滑进入番剧话题，获取更多优质内容推荐。 20岁的废柴大学生——木之下和也，和初恋女友只接吻了一次，却仅过了一个月就被甩了。自暴自弃的他，也通过“某种方法”，和女孩子约会，由此遇见美少女水原千鹤。在仅有一次的租借中，闪耀着“真实”的光芒！恋爱×心动 MAX，莽莽撞撞的爱情故事，就此揭幕！ - Powered by RSSHub",
      "errorAt": "2025-06-30T03:34:55.076Z",
      "errorMessage": "[GET] \"https://www.acfun.cn/bangumi/aa6002917\": 404 Not Found\n",
      "id": "78322824199989248",
      "image": "https://imgs.aixifan.com/W4fWvhjFvL-FjMrUv-au2Mjm-R7j2qq-au677j.png",
      "ownerUserId": null,
      "siteUrl": "https://www.acfun.cn/bangumi/aa6002917",
      "title": "租借女友",
      "type": "feed",
      "url": "rsshub://acfun/bangumi/6002917"
    }
  ],
  "view": 3
}
```
