# ASMR Online - 最新收录

## Coverage
`index-only`

## Route
- Namespace: `asmr-200`
- Namespace Name: `ASMR Online`
- Route Path: `/asmr-200/works/:order?/:subtitle?/:sort?`
- Route Name: `最新收录`
- Example: `/asmr-200/works`
- URL: `asmr-200.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `hualiong`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| 发售日期 | 收录日期     | 销量      | 价格  | 评价               | 随机   | RJ 号 |
| -------- | ------------ | --------- | ----- | ------------------ | ------ | ----- |
| release  | create\_date | dl\_count | price | rate\_average\_2dp | random | id    |

## Parameters
- `order`: 排序字段，默认按照资源的收录日期来排序，详见下表
- `sort`: 排序方式，可选 `asc` 和 `desc` ，默认倒序
- `subtitle`: 筛选带字幕音频，可选 `0` 和 `1` ，默认关闭


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `asmr-200.com`
- `target`: `asmr-200/works`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 发售日期 | 收录日期     | 销量      | 价格  | 评价               | 随机   | RJ 号 |\n| -------- | ------------ | --------- | ----- | ------------------ | ------ | ----- |\n| release  | create\\_date | dl\\_count | price | rate\\_average\\_2dp | random | id    |",
  "example": "/asmr-200/works",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 265,
  "location": "index.tsx",
  "maintainers": [
    "hualiong"
  ],
  "name": "最新收录",
  "parameters": {
    "order": "排序字段，默认按照资源的收录日期来排序，详见下表",
    "sort": "排序方式，可选 `asc` 和 `desc` ，默认倒序",
    "subtitle": "筛选带字幕音频，可选 `0` 和 `1` ，默认关闭"
  },
  "path": "/works/:order?/:subtitle?/:sort?",
  "radar": [
    {
      "source": [
        "asmr-200.com"
      ],
      "target": "asmr-200/works"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新收录 - ASMR Online - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41473375404643328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://asmr-200.com/",
      "title": "最新收录 - ASMR Online",
      "type": "feed",
      "url": "rsshub://asmr-200/works"
    },
    {
      "description": "最新收录 - ASMR Online - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73917319039140864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://asmr-200.com/",
      "title": "最新收录 - ASMR Online",
      "type": "feed",
      "url": "rsshub://asmr-200/works/release/1/desc"
    }
  ],
  "url": "asmr-200.com"
}
```
