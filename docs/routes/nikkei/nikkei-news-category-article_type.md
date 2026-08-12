# The Nikkei 日本経済新聞 - News

## Coverage
`index-only`

## Route
- Namespace: `nikkei`
- Namespace Name: `The Nikkei 日本経済新聞`
- Route Path: `/nikkei/news/:category/:article_type?`
- Route Name: `News`
- Example: `/nikkei/news/news`
- URL: `nikkei.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Arracc, ladeng07`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
| 総合 | オピニオン | 経済    | 政治     | 金融      | マーケット | ビジネス | マネーのまなび | テック     | 国際          | スポーツ | 社会・調査 | 地域  | 文化    | ライフスタイル |
| ---- | ---------- | ------- | -------- | --------- | ---------- | -------- | -------------- | ---------- | ------------- | -------- | ---------- | ----- | ------- | -------------- |
| news | opinion    | economy | politics | financial | business   | 不支持   | 不支持         | technology | international | sports   | society    | local | culture | lifestyle      |

## Parameters
- `category`: Category, see table below
- `article_type`: Only includes free articles, set `free` to enable, disabled by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nikkei.com/:category/archive`
  - `www.nikkei.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 総合 | オピニオン | 経済    | 政治     | 金融      | マーケット | ビジネス | マネーのまなび | テック     | 国際          | スポーツ | 社会・調査 | 地域  | 文化    | ライフスタイル |\n| ---- | ---------- | ------- | -------- | --------- | ---------- | -------- | -------------- | ---------- | ------------- | -------- | ---------- | ----- | ------- | -------------- |\n| news | opinion    | economy | politics | financial | business   | 不支持   | 不支持         | technology | international | sports   | society    | local | culture | lifestyle      |",
  "example": "/nikkei/news/news",
  "heat": 66,
  "location": "news.tsx",
  "maintainers": [
    "Arracc",
    "ladeng07"
  ],
  "name": "News",
  "parameters": {
    "article_type": "Only includes free articles, set `free` to enable, disabled by default",
    "category": "Category, see table below"
  },
  "path": "/news/:category/:article_type?",
  "radar": [
    {
      "source": [
        "www.nikkei.com/:category/archive",
        "www.nikkei.com/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "【日経】ニュース速報、企業・経済の最新情報をお届けします。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64311587559952384",
      "image": "https://www.nikkei.com/.resources/k-components/rectangle.rev-d54ea30.png",
      "ownerUserId": null,
      "siteUrl": "https://www.nikkei.com/news/category/",
      "title": "日本経済新聞 - 総合",
      "type": "feed",
      "url": "rsshub://nikkei/news/news"
    },
    {
      "description": "日本経済新聞の電子版。「テック」に関する最新のニュースをお届けします。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "91684852842104832",
      "image": "https://www.nikkei.com/.resources/k-components/rectangle.rev-d54ea30.png",
      "ownerUserId": null,
      "siteUrl": "https://www.nikkei.com/technology/archive/",
      "title": "日本経済新聞 -",
      "type": "feed",
      "url": "rsshub://nikkei/news/technology"
    }
  ]
}
```
