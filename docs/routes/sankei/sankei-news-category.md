# Sankei Shimbun 産経新聞 - News

## Coverage
`index-only`

## Route
- Namespace: `sankei`
- Namespace Name: `Sankei Shimbun 産経新聞`
- Route Path: `/sankei/news/:category`
- Route Name: `News`
- Example: `/sankei/news/flash`
- URL: `sankei.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `yuikisaito`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category name (as it will appear in URLs). For example, for "Breaking News" https://www.sankei.com/flash/, the category name would be "flash".


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sankei.com/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/sankei/news/flash",
  "heat": 28,
  "location": "news.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "name": "News",
  "parameters": {
    "category": "Category name (as it will appear in URLs). For example, for \"Breaking News\" https://www.sankei.com/flash/, the category name would be \"flash\"."
  },
  "path": "/news/:category",
  "radar": [
    {
      "source": [
        "www.sankei.com/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "産経新聞社のニュースサイト。政治、経済、国際、社会、スポーツ、エンタメ、生活、健康、災害情報などの速報記事と解説記事を新着順に一覧できます。 - Powered by RSSHub",
      "errorAt": "2026-08-27T11:50:16.203Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.sankei.comhttps://www.sankei.com/article/20260902-EBSSJBDTORMNNOJR2V5VOFNFVM/\": <no response> fetch failed (getaddrinfo ENOTFOUND www.sankei.comhttps)\n",
      "id": "157150339579158528",
      "image": "https://www.sankei.com/common/images/ogp_default.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.sankei.com/flash/",
      "title": "産経ニュース - 速報",
      "type": "feed",
      "url": "rsshub://sankei/news/flash"
    },
    {
      "description": "産経新聞社のニュースサイト。国際ニュースの一覧ページです。中国・台湾、朝鮮半島、アジア、米州・アメリカ、欧州・ヨーロッパ、ロシア、中東・アフリカ、国際機関、国際問題などに関する速報記事と解説記事を掲載しています。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "223581287673683968",
      "image": "https://www.sankei.com/common/images/ogp_default.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.sankei.com/world/",
      "title": "産経ニュース - 国際",
      "type": "feed",
      "url": "rsshub://sankei/news/world"
    }
  ]
}
```
