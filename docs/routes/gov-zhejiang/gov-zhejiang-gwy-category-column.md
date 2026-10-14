# 浙江公务员考试录用 - 通知

## Coverage
`index-only`

## Route
- Namespace: `gov/zhejiang`
- Namespace Name: `浙江公务员考试录用`
- Route Path: `/gov/zhejiang/gwy/:category?/:column?`
- Route Name: `通知`
- Example: `/gov/zhejiang/gwy/1`
- URL: `gwy.zjks.gov.cn/zjgwy/website/init.htm`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `gwy.ts`
- Source Module: `_None_`

## Description
| 分类         | id |
| ------------ | -- |
| 重要通知     | 1  |
| 招考公告     | 2  |
| 招考政策     | 3  |
| 面试体检考察 | 4  |
| 录用公示专栏 | 5  |

| 地市         | id    |
| ------------ | ----- |
| 浙江省       | 133   |
| 浙江省杭州市 | 13301 |
| 浙江省宁波市 | 13302 |
| 浙江省温州市 | 13303 |
| 浙江省嘉兴市 | 13304 |
| 浙江省湖州市 | 13305 |
| 浙江省绍兴市 | 13306 |
| 浙江省金华市 | 13307 |
| 浙江省衢州市 | 13308 |
| 浙江省舟山市 | 13309 |
| 浙江省台州市 | 13310 |
| 浙江省丽水市 | 13311 |
| 省级单位     | 13317 |

## Parameters
- `category`: 分类，见下表，默认为全部
- `column`: 地市专栏，见下表，默认为全部


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
  - `gwy.zjks.gov.cn/zjgwy/website/init.htm`
  - `gwy.zjks.gov.cn/zjgwy/website/queryDetail.htm`
  - `gwy.zjks.gov.cn/zjgwy/website/queryMore.htm`
- `target`: `/gwy`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 分类         | id |\n| ------------ | -- |\n| 重要通知     | 1  |\n| 招考公告     | 2  |\n| 招考政策     | 3  |\n| 面试体检考察 | 4  |\n| 录用公示专栏 | 5  |\n\n| 地市         | id    |\n| ------------ | ----- |\n| 浙江省       | 133   |\n| 浙江省杭州市 | 13301 |\n| 浙江省宁波市 | 13302 |\n| 浙江省温州市 | 13303 |\n| 浙江省嘉兴市 | 13304 |\n| 浙江省湖州市 | 13305 |\n| 浙江省绍兴市 | 13306 |\n| 浙江省金华市 | 13307 |\n| 浙江省衢州市 | 13308 |\n| 浙江省舟山市 | 13309 |\n| 浙江省台州市 | 13310 |\n| 浙江省丽水市 | 13311 |\n| 省级单位     | 13317 |",
  "example": "/gov/zhejiang/gwy/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gwy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通知",
  "parameters": {
    "category": "分类，见下表，默认为全部",
    "column": "地市专栏，见下表，默认为全部"
  },
  "path": "/gwy/:category?/:column?",
  "radar": [
    {
      "source": [
        "gwy.zjks.gov.cn/zjgwy/website/init.htm",
        "gwy.zjks.gov.cn/zjgwy/website/queryDetail.htm",
        "gwy.zjks.gov.cn/zjgwy/website/queryMore.htm"
      ],
      "target": "/gwy"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "gwy.zjks.gov.cn/zjgwy/website/init.htm"
}
```
