# とらのあな - Category

## Coverage
`index-only`

## Route
- Namespace: `toranoana`
- Namespace Name: `とらのあな`
- Route Path: `/toranoana/news/:category?`
- Route Name: `Category`
- Example: `/toranoana/news/toragen`
- URL: `toranoana.jp`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `Tsuyumi25`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: warning TIP
[総合新着記事](https://news.toranoana.jp)→`/toranoana/news`\
[女性向け](https://news.toranoana.jp/joshi)→`/toranoana/news/joshi`\
[イラスト展](https://news.toranoana.jp/exhibitions)→`/toranoana/news/exhibition`\
[`https://news.toranoana.jp/category/media`](https://news.toranoana.jp/category/media)→`/toranoana/news/media`
:::

## Parameters
- `category`: category


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `総合新着記事`
- `source`:
  - `news.toranoana.jp`
- `target`: `/news`
### Rule 2
- `title`: `女性向け`
- `source`:
  - `news.toranoana.jp/joshi`
- `target`: `/news/joshi`
### Rule 3
- `title`: `イラスト展`
- `source`:
  - `news.toranoana.jp/exhibitions`
- `target`: `/news/exhibition`
### Rule 4
- `source`:
  - `news.toranoana.jp/category/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: warning TIP\n[総合新着記事](https://news.toranoana.jp)→`/toranoana/news`\\\n[女性向け](https://news.toranoana.jp/joshi)→`/toranoana/news/joshi`\\\n[イラスト展](https://news.toranoana.jp/exhibitions)→`/toranoana/news/exhibition`\\\n[`https://news.toranoana.jp/category/media`](https://news.toranoana.jp/category/media)→`/toranoana/news/media`\n:::",
  "example": "/toranoana/news/toragen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news.ts",
  "maintainers": [
    "Tsuyumi25"
  ],
  "name": "Category",
  "parameters": {
    "category": "category"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.toranoana.jp"
      ],
      "target": "/news",
      "title": "総合新着記事"
    },
    {
      "source": [
        "news.toranoana.jp/joshi"
      ],
      "target": "/news/joshi",
      "title": "女性向け"
    },
    {
      "source": [
        "news.toranoana.jp/exhibitions"
      ],
      "target": "/news/exhibition",
      "title": "イラスト展"
    },
    {
      "source": [
        "news.toranoana.jp/category/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "とらのあなの最新情報をお届け！同人誌、書籍、コミック、店舗フェア、イラスト展、とらのあな限定版、キャンペーンなど…スペシャルでお得な情報をいち早くチェック！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "120762570317180928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.toranoana.jp/category/toragen",
      "title": "とらのあな総合インフォメーション - toragen",
      "type": "feed",
      "url": "rsshub://toranoana/news/toragen"
    }
  ]
}
```
