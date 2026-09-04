# アイドルマスター THE IDOLM@STER - ニュース News

## Coverage
`index-only`

## Route
- Namespace: `idolmaster`
- Namespace Name: `アイドルマスター THE IDOLM@STER`
- Route Path: `/idolmaster/news/:routeParams?`
- Route Name: `ニュース News`
- Example: `/idolmaster/news/brand=MILLIONLIVE&brand=SHINYCOLORS&category=GAME&category=ANIME`
- URL: `idolmaster-official.jp/news`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `keocheung`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
**Brand**

| THE IDOLM\@STER | シンデレラガールズ | ミリオンライブ！ | SideM | シャイニーカラーズ | 学園アイドルマスター | その他 |
| --------------- | ------------------ | ---------------- | ----- | ------------------ | -------------------- | ------ |
| IDOLMASTER      | CINDERELLAGIRLS    | MILLIONLIVE      | SIDEM | SHINYCOLORS        | GAKUEN               | OTHER  |

**Category**

| ゲーム | ライブ・イベント | アニメ | 配信番組   | ラジオ | グッズ | コラボ・キャンペーン | ミュージック | ブック・コミック | メディア | その他 |
| ------ | ---------------- | ------ | ---------- | ------ | ------ | -------------------- | ------------ | ---------------- | -------- | ------ |
| GAME   | LIVE-EVENT       | ANIME  | LIVESTREAM | RADIO  | GOODS  | COLLABO-CAMP         | CD           | BOOK             | MEDIA    | OTHER  |

## Parameters
- `routeParams`: The `brand` and `category` params in the path. The available values are as follows.


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
  - `idolmaster-official.jp/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "**Brand**\n\n| THE IDOLM\\@STER | シンデレラガールズ | ミリオンライブ！ | SideM | シャイニーカラーズ | 学園アイドルマスター | その他 |\n| --------------- | ------------------ | ---------------- | ----- | ------------------ | -------------------- | ------ |\n| IDOLMASTER      | CINDERELLAGIRLS    | MILLIONLIVE      | SIDEM | SHINYCOLORS        | GAKUEN               | OTHER  |\n\n**Category**\n\n| ゲーム | ライブ・イベント | アニメ | 配信番組   | ラジオ | グッズ | コラボ・キャンペーン | ミュージック | ブック・コミック | メディア | その他 |\n| ------ | ---------------- | ------ | ---------- | ------ | ------ | -------------------- | ------------ | ---------------- | -------- | ------ |\n| GAME   | LIVE-EVENT       | ANIME  | LIVESTREAM | RADIO  | GOODS  | COLLABO-CAMP         | CD           | BOOK             | MEDIA    | OTHER  |",
  "example": "/idolmaster/news/brand=MILLIONLIVE&brand=SHINYCOLORS&category=GAME&category=ANIME",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "news.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "ニュース News",
  "parameters": {
    "routeParams": "The `brand` and `category` params in the path. The available values are as follows."
  },
  "path": "/news/:routeParams?",
  "radar": [
    {
      "source": [
        "idolmaster-official.jp/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "NEWS | アイドルマスター - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81966897349713920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://idolmaster-official.jp/news",
      "title": "NEWS | アイドルマスター",
      "type": "feed",
      "url": "rsshub://idolmaster/news"
    },
    {
      "description": "NEWS | アイドルマスター - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82051945166265344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://idolmaster-official.jp/news",
      "title": "NEWS | アイドルマスター",
      "type": "feed",
      "url": "rsshub://idolmaster/news/brand=MILLIONLIVE&brand=SHINYCOLORS&category=GAME&category=ANIME"
    }
  ],
  "url": "idolmaster-official.jp/news"
}
```
