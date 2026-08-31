# DLsite - Current Release

## Coverage
`index-only`

## Route
- Namespace: `dlsite`
- Namespace Name: `DLsite`
- Route Path: `/dlsite/new/:type`
- Route Name: `Current Release`
- Example: `/dlsite/new/home`
- URL: `dlsite.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `cssxsh`
- Source Location: `new.ts`
- Source Module: `_None_`

## Description
| Doujin | Comics | PC Games | Doujin (R18) | Adult Comics | H Games | Otome | BL |
| ------ | ------ | -------- | ------------ | ------------ | ------- | ----- | -- |
| home   | comic  | soft     | maniax       | books        | pro     | girls | bl |

## Parameters
- `type`: {"description": "类型", "options": [{"label": "「DLsite 同人」", "value": "home"}, {"label": "「DLsite コミック」", "value": "comic"}, {"label": "「DLsite PCソフト」", "value": "soft"}, {"label": "「DLsite 同人 - R18」", "value": "maniax"}, {"label": "「DLsite 成年コミック - R18」", "value": "books"}, {"label": "「DLsite 美少女ゲーム」", "value": "pro"}, {"label": "「DLsite 乙女」", "value": "girls"}, {"label": "「DLsite BL」", "value": "bl"}]}


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
  "description": "| Doujin | Comics | PC Games | Doujin (R18) | Adult Comics | H Games | Otome | BL |\n| ------ | ------ | -------- | ------------ | ------------ | ------- | ----- | -- |\n| home   | comic  | soft     | maniax       | books        | pro     | girls | bl |",
  "example": "/dlsite/new/home",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 157,
  "location": "new.ts",
  "maintainers": [
    "cssxsh"
  ],
  "name": "Current Release",
  "parameters": {
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
  "path": "/new/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "「DLsite 同人 - R18」は同人誌・同人ゲーム・同人ボイス・ASMRのダウンロードショップ。お気に入りの作品をすぐダウンロードできてすぐ楽しめる！毎日更新しているのであなたが探している作品にきっと出会えます。国内最大級の二次元総合ダウンロードショップ「DLsite」！ - 発売カレンダー - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72604834390187008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "rsshub://dlsite/new/maniax/new",
      "title": "発売カレンダー: 同人誌・同人ゲーム・同人ボイス・ASMRのダウンロードなら「DLsite 同人 - R18」",
      "type": "feed",
      "url": "rsshub://dlsite/new/maniax"
    },
    {
      "description": "「DLsite 成年コミック - R18」はエロマンガ・アダルトマンガのダウンロードショップ。お気に入りの作品をすぐダウンロードできてすぐ楽しめる！毎日更新しているのであなたが探している作品にきっと出会えます。国内最大級の二次元総合ダウンロードショップ「DLsite」！ - 発売カレンダー - Powered by RSSHub",
      "errorAt": "2026-08-29T14:35:17.619Z",
      "errorMessage": "Failed to fetch\n",
      "id": "72513516125018112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "rsshub://dlsite/new/books/new",
      "title": "発売カレンダー: エロマンガ・アダルトマンガのダウンロードなら「DLsite 成年コミック - R18」",
      "type": "feed",
      "url": "rsshub://dlsite/new/books"
    }
  ],
  "view": 0
}
```
