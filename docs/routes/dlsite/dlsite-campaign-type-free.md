# DLsite - Discounted Works

## Coverage
`index-only`

## Route
- Namespace: `dlsite`
- Namespace Name: `DLsite`
- Route Path: `/dlsite/campaign/:type/:free?`
- Route Name: `Discounted Works`
- Example: `/dlsite/campaign/home`
- URL: `dlsite.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `cssxsh`
- Source Location: `campaign.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "类型", "options": [{"label": "「DLsite 同人」", "value": "home"}, {"label": "「DLsite コミック」", "value": "comic"}, {"label": "「DLsite PCソフト」", "value": "soft"}, {"label": "「DLsite 同人 - R18」", "value": "maniax"}, {"label": "「DLsite 成年コミック - R18」", "value": "books"}, {"label": "「DLsite 美少女ゲーム」", "value": "pro"}, {"label": "「DLsite 乙女」", "value": "girls"}, {"label": "「DLsite BL」", "value": "bl"}]}
- `free`: {"description": "免费", "options": [{"label": "是", "value": "1"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/dlsite/campaign/home",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 406,
  "location": "campaign.ts",
  "maintainers": [
    "cssxsh"
  ],
  "name": "Discounted Works",
  "parameters": {
    "free": {
      "description": "免费",
      "options": [
        {
          "label": "是",
          "value": "1"
        }
      ]
    },
    "type": {
      "description": "类型",
      "options": [
        {
          "label": "「DLsite 同人」",
          "value": "home"
        },
        {
          "label": "「DLsite コミック」",
          "value": "comic"
        },
        {
          "label": "「DLsite PCソフト」",
          "value": "soft"
        },
        {
          "label": "「DLsite 同人 - R18」",
          "value": "maniax"
        },
        {
          "label": "「DLsite 成年コミック - R18」",
          "value": "books"
        },
        {
          "label": "「DLsite 美少女ゲーム」",
          "value": "pro"
        },
        {
          "label": "「DLsite 乙女」",
          "value": "girls"
        },
        {
          "label": "「DLsite BL」",
          "value": "bl"
        }
      ]
    }
  },
  "path": "/campaign/:type/:free?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "「DLsite 成年コミック - R18」はエロマンガ・アダルトマンガのダウンロードショップ。お気に入りの作品をすぐダウンロードできてすぐ楽しめる！毎日更新しているのであなたが探している作品にきっと出会えます。国内最大級の二次元総合ダウンロードショップ「DLsite」！ - 日本語作品 言語不問作品 検索結果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72497415352780800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dlsite.com/books/fsr/=/campaign/campaign/work_category[0]/books/order[0]/cstart_d/per_page/30/show_type/1/is_free/1/",
      "title": "「DLsite 成年コミック - R18」 | 割引中の作品",
      "type": "feed",
      "url": "rsshub://dlsite/campaign/books/1"
    },
    {
      "description": "「DLsite 同人 - R18」は同人誌・同人ゲーム・同人ボイス・ASMRのダウンロードショップ。お気に入りの作品をすぐダウンロードできてすぐ楽しめる！毎日更新しているのであなたが探している作品にきっと出会えます。国内最大級の二次元総合ダウンロードショップ「DLsite」！ - 日本語作品 言語不問作品 検索結果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72511789595944960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dlsite.com/maniax/fsr/=/campaign/campaign/work_category[0]/doujin/order[0]/cstart_d/per_page/30/show_type/1/is_free/1/",
      "title": "「DLsite 同人 - R18」 | 割引中の作品",
      "type": "feed",
      "url": "rsshub://dlsite/campaign/maniax/1"
    }
  ]
}
```
