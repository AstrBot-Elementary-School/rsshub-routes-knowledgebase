# 南京理工大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/njust/gs/:type?`
- Route Name: `研究生院`
- Example: `/njust/gs/sytzgg_4568`
- URL: `jwc.njust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `MilkShakeYoung, jasongzy`
- Source Location: `gs.ts`
- Source Module: `_None_`

## Description
| 首页通知公告 | 首页新闻动态 | 最新通知 | 招生信息 | 培养信息 | 学术活动 |
| ------------ | ------------ | -------- | -------- | -------- | -------- |
| sytzgg\_4568 | sytzgg       | 14686    | 14687    | 14688    | xshdggl  |

## Parameters
- `type`: 分类 ID，部分示例参数见下表，默认为首页通知公告，其他分类 ID 可以从网站 URL Path 中找到，如国际交流为 `gjjl`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gs.njust.edu.cn/:type/list.htm`
- `target`: `/gs/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 首页通知公告 | 首页新闻动态 | 最新通知 | 招生信息 | 培养信息 | 学术活动 |\n| ------------ | ------------ | -------- | -------- | -------- | -------- |\n| sytzgg\\_4568 | sytzgg       | 14686    | 14687    | 14688    | xshdggl  |",
  "example": "/njust/gs/sytzgg_4568",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "gs.ts",
  "maintainers": [
    "MilkShakeYoung",
    "jasongzy"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "分类 ID，部分示例参数见下表，默认为首页通知公告，其他分类 ID 可以从网站 URL Path 中找到，如国际交流为 `gjjl`"
  },
  "path": "/gs/:type?",
  "radar": [
    {
      "source": [
        "gs.njust.edu.cn/:type/list.htm"
      ],
      "target": "/gs/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "南京理工大学研究生院 -- 首页通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62889514707509248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gs.njust.edu.cn/sytzgg_4568/list.htm",
      "title": "南京理工大学研究生院 -- 首页通知公告",
      "type": "feed",
      "url": "rsshub://njust/gs/sytzgg_4568"
    },
    {
      "description": "南京理工大学研究生院 -- 招生信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80790559068210176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gs.njust.edu.cn/14687/list.htm",
      "title": "南京理工大学研究生院 -- 招生信息",
      "type": "feed",
      "url": "rsshub://njust/gs/14687"
    }
  ]
}
```
