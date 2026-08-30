# 央视新闻 - 专题

## Coverage
`index-only`

## Route
- Namespace: `cctv`
- Namespace Name: `央视新闻`
- Route Path: `/cctv/:category`
- Route Name: `专题`
- Example: `/cctv/world`
- URL: `news.cctv.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `idealclover, xyqfer`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 新闻 | 国内  | 国际  | 社会    | 法治 | 文娱 | 科技 | 生活 | 教育 | 每周质量报告 | 新闻 1+1  |
| ---- | ----- | ----- | ------- | ---- | ---- | ---- | ---- | ---- | ------------ | --------- |
| news | china | world | society | law  | ent  | tech | life | edu  | mzzlbg       | xinwen1j1 |

## Parameters
- `category`: 分类名


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
  - `news.cctv.com/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 新闻 | 国内  | 国际  | 社会    | 法治 | 文娱 | 科技 | 生活 | 教育 | 每周质量报告 | 新闻 1+1  |\n| ---- | ----- | ----- | ------- | ---- | ---- | ---- | ---- | ---- | ------------ | --------- |\n| news | china | world | society | law  | ent  | tech | life | edu  | mzzlbg       | xinwen1j1 |",
  "example": "/cctv/world",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 845,
  "location": "category.ts",
  "maintainers": [
    "idealclover",
    "xyqfer"
  ],
  "name": "专题",
  "parameters": {
    "category": "分类名"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "news.cctv.com/:category"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "央视新闻 world - Powered by RSSHub",
      "errorAt": "2026-08-25T08:26:58.537Z",
      "errorMessage": "200 ",
      "id": "41965184796581988",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.cctv.com/world",
      "title": "央视新闻 world",
      "type": "feed",
      "url": "rsshub://cctv/world"
    },
    {
      "description": "央视新闻 china - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41965184796581989",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.cctv.com/china",
      "title": "央视新闻 china",
      "type": "feed",
      "url": "rsshub://cctv/china"
    }
  ]
}
```
