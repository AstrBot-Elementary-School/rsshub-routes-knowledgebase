# 通用影视采集站视频采集接口路由 - 最新资源

## Coverage
`index-only`

## Route
- Namespace: `maccms`
- Namespace Name: `通用影视采集站视频采集接口路由`
- Route Path: `/maccms/:domain/:type?/:size?`
- Route Name: `最新资源`
- Example: `/maccms/moduzy.net/2`
- URL: `_None_`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `hualiong`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
每个采集站提供的影视类别 ID 是不同的，即参数中的 `type` 是不同的。**可以先访问一次站点提供的采集接口，然后从返回结果中的 `class` 字段中的 `type_id`获取相应的类别 ID**
:::

| 站名                | 域名                                             | 站名             | 域名                                               | 站名           | 域名                                            |
| ------------------- | ------------------------------------------------ | ---------------- | -------------------------------------------------- | -------------- | ----------------------------------------------- |
| 魔都资源网          | [moduzy.net](https://moduzy.net)                 | 华为吧影视资源站 | [hw8.live](https://hw8.live)                       | 360 资源站     | [360zy.com](https://360zy.com)                  |
| jkun 爱坤联盟资源网 | [ikunzyapi.com](https://ikunzyapi.com)           | 奥斯卡资源站     | [aosikazy.com](https://aosikazy.com)               | 飞速资源采集网 | [www.feisuzyapi.com](http://www.feisuzyapi.com) |
| 森林资源网          | [slapibf.com](https://slapibf.com)               | 天空资源采集网   | [api.tiankongapi.com](https://api.tiankongapi.com) | 百度云资源     | [api.apibdzy.com](https://api.apibdzy.com)      |
| 红牛资源站          | [www.hongniuzy2.com](https://www.hongniuzy2.com) | 乐视资源网       | [leshiapi.com](https://leshiapi.com)               | 暴风资源       | [bfzyapi.com](https://bfzyapi.com)              |

## Parameters
- `domain`: 采集站域名，可选值如下表
- `type`: 类别ID，不同采集站点有不同的类别规则和ID，默认为 0，代表全部类别
- `size`: 每次获取的数据条数，上限 100 条，默认 30 条


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
    "multimedia"
  ],
  "description": "::: tip\n每个采集站提供的影视类别 ID 是不同的，即参数中的 `type` 是不同的。**可以先访问一次站点提供的采集接口，然后从返回结果中的 `class` 字段中的 `type_id`获取相应的类别 ID**\n:::\n\n| 站名                | 域名                                             | 站名             | 域名                                               | 站名           | 域名                                            |\n| ------------------- | ------------------------------------------------ | ---------------- | -------------------------------------------------- | -------------- | ----------------------------------------------- |\n| 魔都资源网          | [moduzy.net](https://moduzy.net)                 | 华为吧影视资源站 | [hw8.live](https://hw8.live)                       | 360 资源站     | [360zy.com](https://360zy.com)                  |\n| jkun 爱坤联盟资源网 | [ikunzyapi.com](https://ikunzyapi.com)           | 奥斯卡资源站     | [aosikazy.com](https://aosikazy.com)               | 飞速资源采集网 | [www.feisuzyapi.com](http://www.feisuzyapi.com) |\n| 森林资源网          | [slapibf.com](https://slapibf.com)               | 天空资源采集网   | [api.tiankongapi.com](https://api.tiankongapi.com) | 百度云资源     | [api.apibdzy.com](https://api.apibdzy.com)      |\n| 红牛资源站          | [www.hongniuzy2.com](https://www.hongniuzy2.com) | 乐视资源网       | [leshiapi.com](https://leshiapi.com)               | 暴风资源       | [bfzyapi.com](https://bfzyapi.com)              |",
  "example": "/maccms/moduzy.net/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 218,
  "location": "index.tsx",
  "maintainers": [
    "hualiong"
  ],
  "name": "最新资源",
  "parameters": {
    "domain": "采集站域名，可选值如下表",
    "size": "每次获取的数据条数，上限 100 条，默认 30 条",
    "type": "类别ID，不同采集站点有不同的类别规则和ID，默认为 0，代表全部类别"
  },
  "path": "/:domain/:type?/:size?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新里番动漫 - moduzy.net - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142620753499722752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://moduzy.net/",
      "title": "最新里番动漫 - moduzy.net",
      "type": "feed",
      "url": "rsshub://maccms/moduzy.net/6"
    },
    {
      "description": "最新日韩动漫 - moduzy.net - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63376654120875008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://moduzy.net/",
      "title": "最新日韩动漫 - moduzy.net",
      "type": "feed",
      "url": "rsshub://maccms/moduzy.net/2"
    }
  ]
}
```
