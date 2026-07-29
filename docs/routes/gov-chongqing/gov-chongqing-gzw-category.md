# 重庆市人民政府 - 国有资产监督管理委员会

## Coverage
`index-only`

## Route
- Namespace: `gov/chongqing`
- Namespace Name: `重庆市人民政府`
- Route Path: `/gov/chongqing/gzw/:category{.+}?`
- Route Name: `国有资产监督管理委员会`
- Example: `/gov/chongqing/gzw`
- URL: `gzw.cq.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `gzw.ts`
- Source Module: `_None_`

## Description
| 通知公告  | 国企资讯 | 国企简介 | 国企招聘 |
| --------- | -------- | -------- | -------- |
| tzgg\_191 | gqdj     | gqjj     | gqzp     |

## Parameters
- `category`: 分类，见下表，默认为通知公告


## Features
_None_

## Radar
### Rule 1
- `source`: `gzw.cq.gov.cn/*category`
- `target`: `/gzw/*category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告  | 国企资讯 | 国企简介 | 国企招聘 |\n| --------- | -------- | -------- | -------- |\n| tzgg\\_191 | gqdj     | gqjj     | gqzp     |",
  "example": "/gov/chongqing/gzw",
  "heat": 1,
  "location": "gzw.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "国有资产监督管理委员会",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/gzw/:category{.+}?",
  "radar": [
    {
      "source": "gzw.cq.gov.cn/*category",
      "target": "/gzw/*category"
    }
  ],
  "topFeeds": [
    {
      "description": "重庆市国有资产监督管理委员会网站-通知公告栏目,主要展示-通知公告相关的内容,是-通知公告的信息展示窗口 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "144222426224988177",
      "image": "https://gzw.cq.gov.cn/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://gzw.cq.gov.cn/tzgg_191",
      "title": "重庆市国有资产监督管理委员会门户网站 - 通知公告",
      "type": "feed",
      "url": "rsshub://gov/chongqing/gzw"
    }
  ],
  "url": "gzw.cq.gov.cn"
}
```
