# 中国气象局 - 天气预报频道

## Coverage
`index-only`

## Route
- Namespace: `cma`
- Namespace Name: `中国气象局`
- Route Path: `/cma/channel/:id?`
- Route Name: `天气预报频道`
- Example: `/cma/channel/380`
- URL: `weather.cma.cn`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `nczitzk`
- Source Location: `channel.tsx`
- Source Module: `_None_`

## Description
#### 天气实况

| 频道名称 | 频道 id                          |
| -------- | -------------------------------- |
| 卫星云图 | d3236549863e453aab0ccc4027105bad |
| 单站雷达 | 103                              |
| 降水量   | 18                               |
| 气温     | 32                               |
| 土壤水分 | 45                               |

#### 气象公报

| 频道名称       | 频道 id                          |
| -------------- | -------------------------------- |
| 每日天气提示   | 380                              |
| 重要天气提示   | da5d55817ad5430fb9796a0780178533 |
| 天气公报       | 3780                             |
| 强对流天气预报 | 383                              |
| 交通气象预报   | 423                              |
| 森林火险预报   | 424                              |
| 海洋天气公报   | 452                              |
| 环境气象公报   | 467                              |

::: tip
订阅更多细分频道，请前往对应上级频道页，使用下拉菜单选择项目后跳转到目标频道页，查看其 URL 找到对应频道 id
:::

## Parameters
- `id`: 分类，见下表，可在对应频道页 URL 中找到，默认为 380，即每日天气提示


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
    "forecast"
  ],
  "description": "#### 天气实况\n\n| 频道名称 | 频道 id                          |\n| -------- | -------------------------------- |\n| 卫星云图 | d3236549863e453aab0ccc4027105bad |\n| 单站雷达 | 103                              |\n| 降水量   | 18                               |\n| 气温     | 32                               |\n| 土壤水分 | 45                               |\n\n#### 气象公报\n\n| 频道名称       | 频道 id                          |\n| -------------- | -------------------------------- |\n| 每日天气提示   | 380                              |\n| 重要天气提示   | da5d55817ad5430fb9796a0780178533 |\n| 天气公报       | 3780                             |\n| 强对流天气预报 | 383                              |\n| 交通气象预报   | 423                              |\n| 森林火险预报   | 424                              |\n| 海洋天气公报   | 452                              |\n| 环境气象公报   | 467                              |\n\n::: tip\n订阅更多细分频道，请前往对应上级频道页，使用下拉菜单选择项目后跳转到目标频道页，查看其 URL 找到对应频道 id\n:::",
  "example": "/cma/channel/380",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 321,
  "location": "channel.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "天气预报频道",
  "parameters": {
    "id": "分类，见下表，可在对应频道页 URL 中找到，默认为 380，即每日天气提示"
  },
  "path": "/channel/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国气象局·天气预报 - - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57657957614035968",
      "image": "https://weather.cma.cn/undefined",
      "ownerUserId": null,
      "siteUrl": "https://weather.cma.cn/web/channel-380.html",
      "title": "中国气象局·天气预报 -",
      "type": "feed",
      "url": "rsshub://cma/channel/380"
    },
    {
      "description": "中国气象局·天气预报 - - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62458101978222592",
      "image": "https://weather.cma.cn/undefined",
      "ownerUserId": null,
      "siteUrl": "https://weather.cma.cn/web/channel-da5d55817ad5430fb9796a0780178533.html",
      "title": "中国气象局·天气预报 -",
      "type": "feed",
      "url": "rsshub://cma/channel/da5d55817ad5430fb9796a0780178533"
    }
  ]
}
```
