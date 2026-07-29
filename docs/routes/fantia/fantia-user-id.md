# Fantia - User Posts

## Coverage
`index-only`

## Route
- Namespace: `fantia`
- Namespace Name: `Fantia`
- Route Path: `/fantia/user/:id`
- Route Name: `User Posts`
- Example: `/fantia/user/3498`
- URL: `fantia.jp`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: User id, can be found in user profile URL


## Features
- `requireConfig`: [{"description": "The `cookie` after login can be obtained by viewing the request header in the console, If not filled in will cause some posts that require login to read to get exceptions", "name": "FANTIA_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `fantia.jp/fanclubs/:id`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/fantia/user/3498",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "The `cookie` after login can be obtained by viewing the request header in the console, If not filled in will cause some posts that require login to read to get exceptions",
        "name": "FANTIA_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 211,
  "location": "user.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "User Posts",
  "parameters": {
    "id": "User id, can be found in user profile URL"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "fantia.jp/fanclubs/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Fantia - かほてぃあ (夏帆) - Powered by RSSHub",
      "errorAt": "2025-04-30T18:31:32.447Z",
      "errorMessage": "[GET] \"https://fantia.jp/api/v1/fanclubs/496365\": 404 Not Found\n",
      "id": "41147805276726313",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fantia.jp/fanclubs/496365",
      "title": "Fantia - かほてぃあ (夏帆)",
      "type": "feed",
      "url": "rsshub://fantia/user/496365"
    },
    {
      "description": "🕊【大切なお知らせ】 9月以降のファンクラブ運営について ▶︎ https://fantia.jp/posts/4128306 『ありすほりっく』の Fantia へようこそ🪄🐇 毎月コスプレえっち作品を投稿しています💕 ❤️ 完全コスプレ × シチュエーション ❤️ 生◯メ 中◯し 淫語 女性優位 フェチプレイ etc…💗⸝⸝⸝ 🔽 お気に入りの作品をぜひ探してみてください⋆｡ﾟ☁ 🩷【 https://x.gd/lKhNp 】🩷 🔺 配信中の最新作品一覧はこちら🎬 🔺 ॰ॱ୨୧┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈୨୧ॱ॰ 🐇 ありすほりっくのこだわりpoint 🪄✨ ⚫︎ コス衣装はもちろん着たまま‼️ ⚫︎ シチュエーションプレイ ⚫︎ 生◯メ・中◯し 発射シーンあり！ ⚫︎ 完全 パイパン 宣言✨ ⚫︎ 毎月初出しコスあり ⚫︎ 淫語セリフ動画あり❤️ ⚫︎ 女性上位や性癖プレイのレア動画あり❤️ and more… いろんなプレイに挑戦中💕 ॰ॱ୨୧┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈୨୧ॱ॰ ☑️ 男優・モデルのプライバシー保護のため 『作品本編』でも顔にぼかしを入れています！ ☑️ また、予告なく投稿動画や写真等を削除する可能性もございます、何卒ご了承ください。 ☑️ 当サークルでは動画‧画像等、投稿コンテンツの切り抜き含む無断転載を固く禁⽌しております。 ❗️ Fantiaの規約上、決済済みのプランご加入料金・商品等のご購入代金はいかなる場合にもサークルよりご返金はできません。何卒ご了承ください。 ⚠️ 撮影者・男優の募集は現在行っておりません。 💌 応援メッセージ・コメント大変励みになっております✨ 制作時間確保のため、 個別メッセージへの返信は原則行っておりません💦 なお、動画の不具合などに関するお問い合わせには対応いたします📩 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66192437247858688",
      "image": "https://c.fantia.jp/uploads/fanclub/icon_image/404572/73d6bc55-86d2-4c82-86be-d3132ff1bbb5.jpg",
      "ownerUserId": null,
      "siteUrl": "https://fantia.jp/fanclubs/404572",
      "title": "Fantia - ありすほりっく (ありすほりっく)",
      "type": "feed",
      "url": "rsshub://fantia/user/404572"
    }
  ],
  "view": 2
}
```
