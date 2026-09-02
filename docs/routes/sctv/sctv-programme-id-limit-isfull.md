# 四川广播电视台 - 电视回放

## Coverage
`index-only`

## Route
- Namespace: `sctv`
- Namespace Name: `四川广播电视台`
- Route Path: `/sctv/programme/:id?/:limit?/:isFull?`
- Route Name: `电视回放`
- Example: `/sctv/programme/1`
- URL: `sctv.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `programme.tsx`
- Source Module: `_None_`

## Description
::: tip
参数 **是否仅获取完整视频** 设置为 `true` `yes` `t` `y` 等值后，路由仅返回当期节目的完整视频，而不会返回节目所提供的节选视频。

查看更多电视节目请前往 [电视回放](https://www.sctv.com/column/list)
:::

| 节目                   | id      |
| ---------------------- | ------- |
| 四川新闻联播           | 1       |
| 早安四川               | 2       |
| 今日视点               | 3       |
| 龙门阵摆四川           | 10523   |
| 非常话题               | 1014756 |
| 新闻现场               | 8385    |
| 黄金三十分             | 8386    |
| 全媒直播间             | 8434    |
| 晚报十点半             | 8435    |
| 现场快报               | 8436    |
| 四川乡村新闻           | 3673    |
| 四川文旅报道           | 8174    |
| 乡村会客厅             | 3674    |
| 金字招牌               | 3675    |
| 问您所 “？”            | 3677    |
| 蜀你最能               | 3679    |
| 美丽乡村印象           | 3678    |
| 美丽乡村               | 3676    |
| 乡村大篷车             | 3680    |
| 华西论健               | 3681    |
| 乡村聚乐部             | 3682    |
| 医保近距离             | 6403    |
| 音你而来               | 7263    |
| 吃八方                 | 7343    |
| 世界那么大             | 7344    |
| 风云川商               | 7345    |
| 麻辣烫                 | 7346    |
| 财经快报               | 7473    |
| 医生来了               | 7873    |
| 安逸的旅途             | 8383    |
| 运动 +                 | 8433    |
| 好戏连台               | 9733    |
| 防癌大讲堂             | 1018673 |
| 消费新观察             | 1017153 |
| 天天耍大牌             | 1014753 |
| 廉洁四川               | 1014754 |
| 看世界                 | 1014755 |
| 金熊猫说教育（资讯版） | 1014757 |
| 她说                   | 1014759 |
| 嗨宝贝                 | 1014762 |
| 萌眼看世界             | 1014764 |
| 乡村大讲堂             | 1014765 |
| 四川党建               | 1014766 |
| 健康四川               | 1014767 |
| 技能四川               | 12023   |

## Parameters
- `id`: 节目 id，可在对应节目页中找到，默认为 `1`，即四川新闻联播
- `limit`: 期数，默认为 15，即单次获取最新 15 期
- `isFull`: 是否仅获取完整视频，填写 true/yes 表示是、false/no 表示否，默认是


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
    "traditional-media"
  ],
  "description": "::: tip\n参数 **是否仅获取完整视频** 设置为 `true` `yes` `t` `y` 等值后，路由仅返回当期节目的完整视频，而不会返回节目所提供的节选视频。\n\n查看更多电视节目请前往 [电视回放](https://www.sctv.com/column/list)\n:::\n\n| 节目                   | id      |\n| ---------------------- | ------- |\n| 四川新闻联播           | 1       |\n| 早安四川               | 2       |\n| 今日视点               | 3       |\n| 龙门阵摆四川           | 10523   |\n| 非常话题               | 1014756 |\n| 新闻现场               | 8385    |\n| 黄金三十分             | 8386    |\n| 全媒直播间             | 8434    |\n| 晚报十点半             | 8435    |\n| 现场快报               | 8436    |\n| 四川乡村新闻           | 3673    |\n| 四川文旅报道           | 8174    |\n| 乡村会客厅             | 3674    |\n| 金字招牌               | 3675    |\n| 问您所 “？”            | 3677    |\n| 蜀你最能               | 3679    |\n| 美丽乡村印象           | 3678    |\n| 美丽乡村               | 3676    |\n| 乡村大篷车             | 3680    |\n| 华西论健               | 3681    |\n| 乡村聚乐部             | 3682    |\n| 医保近距离             | 6403    |\n| 音你而来               | 7263    |\n| 吃八方                 | 7343    |\n| 世界那么大             | 7344    |\n| 风云川商               | 7345    |\n| 麻辣烫                 | 7346    |\n| 财经快报               | 7473    |\n| 医生来了               | 7873    |\n| 安逸的旅途             | 8383    |\n| 运动 +                 | 8433    |\n| 好戏连台               | 9733    |\n| 防癌大讲堂             | 1018673 |\n| 消费新观察             | 1017153 |\n| 天天耍大牌             | 1014753 |\n| 廉洁四川               | 1014754 |\n| 看世界                 | 1014755 |\n| 金熊猫说教育（资讯版） | 1014757 |\n| 她说                   | 1014759 |\n| 嗨宝贝                 | 1014762 |\n| 萌眼看世界             | 1014764 |\n| 乡村大讲堂             | 1014765 |\n| 四川党建               | 1014766 |\n| 健康四川               | 1014767 |\n| 技能四川               | 12023   |",
  "example": "/sctv/programme/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "programme.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "电视回放",
  "parameters": {
    "id": "节目 id，可在对应节目页中找到，默认为 `1`，即四川新闻联播",
    "isFull": "是否仅获取完整视频，填写 true/yes 表示是、false/no 表示否，默认是",
    "limit": "期数，默认为 15，即单次获取最新 15 期"
  },
  "path": "/programme/:id?/:limit?/:isFull?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "四川广播电视台 - 四川新闻联播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "178834515500019712",
      "image": "/sctv/1/image/public/202101/20210118094118_abbi6fxq9i.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.sctv.com/column/detail?programmeIndex=/sctv/lookback/1/index.json",
      "title": "四川广播电视台 - 四川新闻联播",
      "type": "feed",
      "url": "rsshub://sctv/programme/1/15/yes"
    },
    {
      "description": "四川广播电视台 - 吃八方 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198402459807542272",
      "image": "/sctv/1/image/public/202010/20201010094714_nrfep8uqvu.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.sctv.com/column/detail?programmeIndex=/sctv/lookback/7343/index.json",
      "title": "四川广播电视台 - 吃八方",
      "type": "feed",
      "url": "rsshub://sctv/programme/7343"
    }
  ]
}
```
