# 太原市人民政府 - 人力资源和社会保障局政府公开信息

## Coverage
`index-only`

## Route
- Namespace: `gov/taiyuan`
- Namespace Name: `太原市人民政府`
- Route Path: `/gov/taiyuan/rsj/:caty/:page?`
- Route Name: `人力资源和社会保障局政府公开信息`
- Example: `/gov/taiyuan/rsj/gggs`
- URL: `rsj.taiyuan.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `2PoL`
- Source Location: `rsj.ts`
- Source Module: `_None_`

## Description
| 工作动态 | 太原新闻 | 通知公告 | 县区动态 | 国内动态 | 图片新闻 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| gzdt     | tyxw     | gggs     | xqdt     | gndt     | tpxw     |

## Parameters
- `caty`: 信息类别
- `page`: 历史兼容参数，所有值均返回第 1 页，不翻页


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
  - `rsj.taiyuan.gov.cn/zfxxgk/:caty/index.shtml`
- `target`: `/rsj/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 工作动态 | 太原新闻 | 通知公告 | 县区动态 | 国内动态 | 图片新闻 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| gzdt     | tyxw     | gggs     | xqdt     | gndt     | tpxw     |",
  "example": "/gov/taiyuan/rsj/gggs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rsj.ts",
  "maintainers": [
    "2PoL"
  ],
  "name": "人力资源和社会保障局政府公开信息",
  "parameters": {
    "caty": "信息类别",
    "page": "历史兼容参数，所有值均返回第 1 页，不翻页"
  },
  "path": "/rsj/:caty/:page?",
  "radar": [
    {
      "source": [
        "rsj.taiyuan.gov.cn/zfxxgk/:caty/index.shtml"
      ],
      "target": "/rsj/:caty"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "rsj.taiyuan.gov.cn/*"
}
```
