# 公視新聞網 - 分類

## Coverage
`index-only`

## Route
- Namespace: `pts`
- Namespace Name: `公視新聞網`
- Route Path: `/pts/category/:id`
- Route Name: `分類`
- Example: `/pts/category/9`
- URL: `news.pts.org.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 名称     | 编号 |
| -------- | ---- |
| 政治     | 1    |
| 社會     | 7    |
| 全球     | 4    |
| 生活     | 5    |
| 兩岸     | 9    |
| 地方     | 11   |
| 產經     | 10   |
| 文教科技 | 6    |
| 環境     | 3    |
| 社福人權 | 12   |

## Parameters
- `id`: 分類 id，见下表，可在对应分類页 URL 中找到


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
  - `news.pts.org.tw/category/:id`
  - `news.pts.org.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 名称     | 编号 |\n| -------- | ---- |\n| 政治     | 1    |\n| 社會     | 7    |\n| 全球     | 4    |\n| 生活     | 5    |\n| 兩岸     | 9    |\n| 地方     | 11   |\n| 產經     | 10   |\n| 文教科技 | 6    |\n| 環境     | 3    |\n| 社福人權 | 12   |",
  "example": "/pts/category/9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分類",
  "parameters": {
    "id": "分類 id，见下表，可在对应分類页 URL 中找到"
  },
  "path": "/category/:id",
  "radar": [
    {
      "source": [
        "news.pts.org.tw/category/:id",
        "news.pts.org.tw/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "全球 ｜ 公視新聞網 PNN - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69916583666985995",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.pts.org.tw/category/4",
      "title": "全球 ｜ 公視新聞網 PNN",
      "type": "feed",
      "url": "rsshub://pts/category/4"
    }
  ]
}
```
