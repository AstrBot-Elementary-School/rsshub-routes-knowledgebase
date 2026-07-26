# CBNData - 看点

## Coverage
`index-only`

## Route
- Namespace: `cbndata`
- Namespace Name: `CBNData`
- Route Path: `/cbndata/information/:id?`
- Route Name: `看点`
- Example: `/cbndata/information/all`
- URL: `www.cbndata.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `information.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [美妆个护](https://www.cbndata.com/information?tag_id=1)，其源网址为 `https://www.cbndata.com/information?tag_id=1`，请参考该 URL 指定部分构成参数，此时路由为 [`/cbndata/information/1`](https://rsshub.app/cbndata/information/1)。
:::

| 分类                                                        | ID                                                  |
| ----------------------------------------------------------- | --------------------------------------------------- |
| [全部](https://www.cbndata.com/information?tag_id=all)      | [all](https://rsshub.app/cbndata/information/all)   |
| [美妆个护](https://www.cbndata.com/information?tag_id=1)    | [1](https://rsshub.app/cbndata/information/1)       |
| [服饰鞋包](https://www.cbndata.com/information?tag_id=2559) | [2559](https://rsshub.app/cbndata/information/2559) |
| [宠物](https://www.cbndata.com/information?tag_id=2419)     | [2419](https://rsshub.app/cbndata/information/2419) |
| [营销](https://www.cbndata.com/information?tag_id=2484)     | [2484](https://rsshub.app/cbndata/information/2484) |

## Parameters
- `id`: {"description": "分类，默认为 `all`，即全部，可在对应分类页 URL 中找到", "options": [{"label": "全部", "value": "all"}, {"label": "美妆个护", "value": "1"}, {"label": "服饰鞋包", "value": "2559"}, {"label": "宠物", "value": "2419"}, {"label": "营销", "value": "2484"}]}


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
  - `www.cbndata.com/information`
### Rule 2
- `title`: `全部`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/all`
### Rule 3
- `title`: `美妆个护`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/1`
### Rule 4
- `title`: `服饰鞋包`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/2559`
### Rule 5
- `title`: `宠物`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/2419`
### Rule 6
- `title`: `营销`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/2484`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [美妆个护](https://www.cbndata.com/information?tag_id=1)，其源网址为 `https://www.cbndata.com/information?tag_id=1`，请参考该 URL 指定部分构成参数，此时路由为 [`/cbndata/information/1`](https://rsshub.app/cbndata/information/1)。\n:::\n\n| 分类                                                        | ID                                                  |\n| ----------------------------------------------------------- | --------------------------------------------------- |\n| [全部](https://www.cbndata.com/information?tag_id=all)      | [all](https://rsshub.app/cbndata/information/all)   |\n| [美妆个护](https://www.cbndata.com/information?tag_id=1)    | [1](https://rsshub.app/cbndata/information/1)       |\n| [服饰鞋包](https://www.cbndata.com/information?tag_id=2559) | [2559](https://rsshub.app/cbndata/information/2559) |\n| [宠物](https://www.cbndata.com/information?tag_id=2419)     | [2419](https://rsshub.app/cbndata/information/2419) |\n| [营销](https://www.cbndata.com/information?tag_id=2484)     | [2484](https://rsshub.app/cbndata/information/2484) |",
  "example": "/cbndata/information/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 24,
  "location": "information.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "看点",
  "parameters": {
    "id": {
      "description": "分类，默认为 `all`，即全部，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "美妆个护",
          "value": "1"
        },
        {
          "label": "服饰鞋包",
          "value": "2559"
        },
        {
          "label": "宠物",
          "value": "2419"
        },
        {
          "label": "营销",
          "value": "2484"
        }
      ]
    }
  },
  "path": "/information/:id?",
  "radar": [
    {
      "source": [
        "www.cbndata.com/information"
      ]
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/all",
      "title": "全部"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/1",
      "title": "美妆个护"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/2559",
      "title": "服饰鞋包"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/2419",
      "title": "宠物"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/2484",
      "title": "营销"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "资讯|第一财经商业数据中心（CBNData）隶属于上海文化广播影视集团，是国内领先的消费研究机构及数字化增长服务商。CBNData消费站为消费行业从业者提供前沿、高效、深度的新闻资讯服务，每日提供新零售、电商直播、美妆个护、食品饮料、餐饮、家电、网红达人等行业热点及相关政策新闻，还有行业大咖独家经验分享、消费早报、营销观察、视频课、新品研究、双11和618专题等原创资讯。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "182706374336947200",
      "image": "//assets-oss.cbndata.com/cbndata-refactor-fe/FvLd08nxNlLXw7TRuskoy8oMo5Dt.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cbndata.com/information?tag_id=all",
      "title": "今日新鲜事-热点新闻-消费行业资讯 | CBNData",
      "type": "feed",
      "url": "rsshub://cbndata/information/all"
    },
    {
      "description": "资讯|第一财经商业数据中心（CBNData）隶属于上海文化广播影视集团，是国内领先的消费研究机构及数字化增长服务商。CBNData消费站为消费行业从业者提供前沿、高效、深度的新闻资讯服务，每日提供新零售、电商直播、美妆个护、食品饮料、餐饮、家电、网红达人等行业热点及相关政策新闻，还有行业大咖独家经验分享、消费早报、营销观察、视频课、新品研究、双11和618专题等原创资讯。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "151627344646140930",
      "image": "//assets-oss.cbndata.com/cbndata-refactor-fe/FvLd08nxNlLXw7TRuskoy8oMo5Dt.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cbndata.com/information?tag_id=all",
      "title": "今日新鲜事-热点新闻-消费行业资讯 | CBNData",
      "type": "feed",
      "url": "rsshub://cbndata/information"
    }
  ],
  "url": "www.cbndata.com",
  "view": 0
}
```
