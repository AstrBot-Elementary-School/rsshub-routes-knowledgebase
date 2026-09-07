# 哔哩哔哩 bilibili - 会员购票务

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/platform/:area?/:p_type?/:uid?`
- Route Name: `会员购票务`
- Example: `/bilibili/platform/-1`
- URL: `show.bilibili.com/platform`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `nightmare-mio`
- Source Location: `platform.ts`
- Source Module: `_None_`

## Description
| 类型     |
| -------- |
| 演出     |
| 展览     |
| 本地生活 |

## Parameters
- `area`: 省市-国标码,默认为-1即全国
- `p_type`: 类型：见下表，默认为全部类型
- `uid`: 用户id，可以不填，不过不填不设置cookie，搜索结果与登入账号后搜索结果不一样。可以在url中找到，需要配置cookie值，只需要SESSDATA的值即可


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
  - `show.bilibili.com/platform`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 类型     |\n| -------- |\n| 演出     |\n| 展览     |\n| 本地生活 |",
  "example": "/bilibili/platform/-1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "platform.ts",
  "maintainers": [
    "nightmare-mio"
  ],
  "name": "会员购票务",
  "parameters": {
    "area": "省市-国标码,默认为-1即全国",
    "p_type": "类型：见下表，默认为全部类型",
    "uid": "用户id，可以不填，不过不填不设置cookie，搜索结果与登入账号后搜索结果不一样。可以在url中找到，需要配置cookie值，只需要SESSDATA的值即可"
  },
  "path": "/platform/:area?/:p_type?/:uid?",
  "radar": [
    {
      "source": [
        "show.bilibili.com/platform"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bilibili会员购票务-230100 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "93830841296676864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://show.bilibili.com/api/ticket/project/listV2",
      "title": "bilibili会员购票务-230100",
      "type": "feed",
      "url": "rsshub://bilibili/platform/230100"
    },
    {
      "description": "bilibili会员购票务--1 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "184995883214968832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://show.bilibili.com/api/ticket/project/listV2",
      "title": "bilibili会员购票务--1",
      "type": "feed",
      "url": "rsshub://bilibili/platform"
    }
  ],
  "url": "show.bilibili.com/platform"
}
```
