# 公視新聞網 - 即時新聞

## Coverage
`index-only`

## Route
- Namespace: `pts`
- Namespace Name: `公視新聞網`
- Route Path: `/pts/dailynews`
- Route Name: `即時新聞`
- Example: `/pts/dailynews`
- URL: `news.pts.org.tw/dailynews`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `news.pts.org.tw/dailynews`
  - `news.pts.org.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/pts/dailynews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "即時新聞",
  "parameters": {},
  "path": "/dailynews",
  "radar": [
    {
      "source": [
        "news.pts.org.tw/dailynews",
        "news.pts.org.tw/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "即時 ｜ 公視新聞網 PNN - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67490527781761030",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.pts.org.tw/dailynews",
      "title": "即時 ｜ 公視新聞網 PNN",
      "type": "feed",
      "url": "rsshub://pts/dailynews"
    }
  ],
  "url": "news.pts.org.tw/dailynews"
}
```
