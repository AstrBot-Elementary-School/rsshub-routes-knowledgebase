# JapanGov - PDF

## Coverage
`index-only`

## Route
- Namespace: `go`
- Namespace Name: `JapanGov`
- Route Path: `/go/mhlw/pdf/:category{.+}?`
- Route Name: `PDF`
- Example: `/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii`
- URL: `www.mhlw.go.jp`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `mhlw/pdf.ts`
- Source Module: `_None_`

## Description
::: tip
Subscribing to this route will give you access to all PDF files on this page.

If you subscribe to [新型コロナウイルス感染症の定点当たり報告数の推移](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html)，where the URL is `https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html`, Use the path `stf/seisakunitsuite/bunya/houkokusuunosuii` as the category parameter. The resulting route is [`/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii`](https://rsshub.app/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii).
:::

## Parameters
- `category`: Category, `stf/seisakunitsuite/bunya/houkokusuunosuii` as 新型コロナウイルス感染症の定点当たり報告数の推移 by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.mhlw.go.jp/*category`
- `target`: `/mhlw/pdf/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\nSubscribing to this route will give you access to all PDF files on this page.\n\nIf you subscribe to [新型コロナウイルス感染症の定点当たり報告数の推移](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html)，where the URL is `https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html`, Use the path `stf/seisakunitsuite/bunya/houkokusuunosuii` as the category parameter. The resulting route is [`/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii`](https://rsshub.app/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii).\n:::",
  "example": "/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "mhlw/pdf.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "PDF",
  "parameters": {
    "category": "Category, `stf/seisakunitsuite/bunya/houkokusuunosuii` as 新型コロナウイルス感染症の定点当たり報告数の推移 by default"
  },
  "path": "/mhlw/pdf/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.mhlw.go.jp/*category"
      ],
      "target": "/mhlw/pdf/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "新型コロナウイルス感染症の定点当たり報告数の推移を掲載しています。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60617622962418688",
      "image": "https://www.mhlw.go.jp/content/000269503.png",
      "ownerUserId": null,
      "siteUrl": "https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html",
      "title": "新型コロナウイルス感染症の定点当たり報告数の推移｜厚生労働省",
      "type": "feed",
      "url": "rsshub://go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii"
    }
  ],
  "url": "www.mhlw.go.jp"
}
```
