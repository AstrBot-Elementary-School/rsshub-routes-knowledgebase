# 第一财经 - 视听

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/yicai/video/:id?`
- Route Name: `视听`
- Example: `/yicai/video`
- URL: `yicai.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
| Id                   | 名称                         |
| -------------------- | ---------------------------- |
| youliao              | 有料                         |
| appshipin            | 此刻                         |
| yicaisudi            | 速递                         |
| caishang             | 财商                         |
| shiji                | 史记                         |
| jinrigushi           | 今日股市                     |
| tangulunjin          | 谈股论金                     |
| gongsiyuhangye       | 公司与行业                   |
| cjyxx                | 财经夜行线                   |
| 6thtradingday        | 第六交易日                   |
| cjfw                 | 财经风味                     |
| chuangshidai         | 创时代                       |
| weilaiyaoqinghan     | 未来邀请函                   |
| tounaofengbao        | 头脑风暴                     |
| zhongguojingyingzhe  | 中国经营者                   |
| shichanglingjuli     | 市场零距离                   |
| huanqiucaijing       | 环球财经视界                 |
| zgjcqyjglsxftl       | 中国杰出企业家管理思想访谈录 |
| jiemacaishang        | 解码财商                     |
| sxpl                 | 首席评论                     |
| zhongguojingjiluntan | 中国经济论坛                 |
| opinionleader        | 意见领袖                     |
| xinjinrong           | 解码新金融                   |
| diyidichan           | 第一地产                     |
| zhichedaren          | 智车达人                     |
| chuangtoufengyun     | 创投风云                     |
| chunxiangrensheng    | 醇享人生                     |
| diyishengyin         | 第一声音                     |
| sanliangboqianjin    | 财智双全                     |
| weilaiyaoqinghan     | 未来邀请函                   |
| zjdy                 | 主角 ▪ 大医                  |
| leye                 | 乐业之城                     |
| sanrenxing           | 价值三人行                   |
| yuandongli           | 中国源动力                   |
| pioneerzone          | 直击引领区                   |

## Parameters
- `id`: 分类 id，见下表，可在对应分类页中找到，默认为视听


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yicai.com/video/:id`
  - `yicai.com/video`
- `target`: `/video/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Id                   | 名称                         |\n| -------------------- | ---------------------------- |\n| youliao              | 有料                         |\n| appshipin            | 此刻                         |\n| yicaisudi            | 速递                         |\n| caishang             | 财商                         |\n| shiji                | 史记                         |\n| jinrigushi           | 今日股市                     |\n| tangulunjin          | 谈股论金                     |\n| gongsiyuhangye       | 公司与行业                   |\n| cjyxx                | 财经夜行线                   |\n| 6thtradingday        | 第六交易日                   |\n| cjfw                 | 财经风味                     |\n| chuangshidai         | 创时代                       |\n| weilaiyaoqinghan     | 未来邀请函                   |\n| tounaofengbao        | 头脑风暴                     |\n| zhongguojingyingzhe  | 中国经营者                   |\n| shichanglingjuli     | 市场零距离                   |\n| huanqiucaijing       | 环球财经视界                 |\n| zgjcqyjglsxftl       | 中国杰出企业家管理思想访谈录 |\n| jiemacaishang        | 解码财商                     |\n| sxpl                 | 首席评论                     |\n| zhongguojingjiluntan | 中国经济论坛                 |\n| opinionleader        | 意见领袖                     |\n| xinjinrong           | 解码新金融                   |\n| diyidichan           | 第一地产                     |\n| zhichedaren          | 智车达人                     |\n| chuangtoufengyun     | 创投风云                     |\n| chunxiangrensheng    | 醇享人生                     |\n| diyishengyin         | 第一声音                     |\n| sanliangboqianjin    | 财智双全                     |\n| weilaiyaoqinghan     | 未来邀请函                   |\n| zjdy                 | 主角 ▪ 大医                  |\n| leye                 | 乐业之城                     |\n| sanrenxing           | 价值三人行                   |\n| yuandongli           | 中国源动力                   |\n| pioneerzone          | 直击引领区                   |",
  "example": "/yicai/video",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "video.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "视听",
  "parameters": {
    "id": "分类 id，见下表，可在对应分类页中找到，默认为视听"
  },
  "path": "/video/:id?",
  "radar": [
    {
      "source": [
        "yicai.com/video/:id",
        "yicai.com/video"
      ],
      "target": "/video/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "第一财经 - 谈股论金 - Powered by RSSHub",
      "errorAt": "2025-11-04T09:04:03.275Z",
      "errorMessage": "Failed to fetch\n",
      "id": "134860047181050880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/video/tangulunjin",
      "title": "第一财经 - 谈股论金",
      "type": "feed",
      "url": "rsshub://yicai/video/tangulunjin"
    },
    {
      "description": "第一财经 - 公司与行业 - Powered by RSSHub",
      "errorAt": "2025-11-04T10:01:05.385Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slug')\n",
      "id": "134861031617215488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/video/gongsiyuhangye",
      "title": "第一财经 - 公司与行业",
      "type": "feed",
      "url": "rsshub://yicai/video/gongsiyuhangye"
    }
  ]
}
```
