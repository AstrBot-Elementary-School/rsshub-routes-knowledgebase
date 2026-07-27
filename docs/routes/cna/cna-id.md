# 中央通讯社 - 分类

## Coverage
`index-only`

## Route
- Namespace: `cna`
- Namespace Name: `中央通讯社`
- Route Path: `/cna/:id?`
- Route Name: `分类`
- Example: `/cna/aall`
- URL: `cna.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 聚焦      | 即時 | 政治 | 國際 | 兩岸 | 產經 | 證券 | 科技 | 生活 | 社會 | 地方 | 文化 | 運動 | 娛樂 |
| --------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| headlines | aall | aipl | aopl | acn  | aie  | asc  | ait  | ahel | asoc | aloc | acul | aspt | amov |

## Parameters
- `id`: 分类 id 或新闻专题 id。分类 id 见下表，新闻专题 id 為 https://www.cna.com.tw/list/newstopic.aspx 中，連結的數字部份。此參數默认为 aall


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
    "traditional-media"
  ],
  "description": "| 聚焦      | 即時 | 政治 | 國際 | 兩岸 | 產經 | 證券 | 科技 | 生活 | 社會 | 地方 | 文化 | 運動 | 娛樂 |\n| --------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| headlines | aall | aipl | aopl | acn  | aie  | asc  | ait  | ahel | asoc | aloc | acul | aspt | amov |",
  "example": "/cna/aall",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 455,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类 id 或新闻专题 id。分类 id 见下表，新闻专题 id 為 https://www.cna.com.tw/list/newstopic.aspx 中，連結的數字部份。此參數默认为 aall"
  },
  "path": "/:id?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中央社即時報導國際、財經、科技、醫藥、生活、運動、教育、政治、影劇、社會、地方即時新聞，提供Facebook、Google+社群討論、分享功能。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61601757267858432",
      "image": "https://imgcdn.cna.com.tw/www/images/pic_fb.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cna.com.tw/list/aall.aspx",
      "title": "即時 | 中央社 CNA",
      "type": "feed",
      "url": "rsshub://cna/aall"
    },
    {
      "description": "想掌握中國大陸、香港、澳門即時消息，兩岸交流現況與習近平政府最新動態，反壟斷與港區國安法等重要議題，鎖定中央社兩岸新聞，掌握兩岸新趨勢。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59799220289372160",
      "image": "https://imgcdn.cna.com.tw/www/images/pic_fb.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cna.com.tw/list/acn.aspx",
      "title": "兩岸 | 中央社 CNA",
      "type": "feed",
      "url": "rsshub://cna/acn"
    }
  ]
}
```
