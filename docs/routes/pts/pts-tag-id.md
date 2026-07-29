# 公視新聞網 - 標籤

## Coverage
`index-only`

## Route
- Namespace: `pts`
- Namespace Name: `公視新聞網`
- Route Path: `/pts/tag/:id`
- Route Name: `標籤`
- Example: `/pts/tag/230`
- URL: `news.pts.org.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 標籤 id，可在对应標籤页 URL 中找到


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
  - `news.pts.org.tw/tag/:id`
  - `news.pts.org.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/pts/tag/230",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "標籤",
  "parameters": {
    "id": "標籤 id，可在对应標籤页 URL 中找到"
  },
  "path": "/tag/:id",
  "radar": [
    {
      "source": [
        "news.pts.org.tw/tag/:id",
        "news.pts.org.tw/"
      ]
    }
  ],
  "topFeeds": []
}
```
