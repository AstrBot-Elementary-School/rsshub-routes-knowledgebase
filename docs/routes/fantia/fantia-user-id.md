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
  "heat": 210,
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
      "description": "🐇 ありすほりっくのFantiaへようこそ 🪄 ありすほりっくは、2026年8月末をもちまして 新作の投稿を無期限でお休みしています これまで公開した作品は、 ファンクラブ内･商品ページから 引き続きお楽しみいただけます🐇🩷 ⟡・········································・⟡ 🎥 作品一覧はこちら ▶︎ https://x.gd/0fI5z ♥️ 有料プラン限定・お得な購入ページはこちら ▶︎ https://x.gd/NWRhy 🎰 お得な限定動画ガチャはこちら ▶︎ https://fantia.jp/products/1033491 ⟡・········································・⟡ ♥️ ありすほりっくについて🪄 🐇 完全コスプレ×シチュエーション作品を中心に、 衣装・セリフ・シナリオ・性癖・プレイまで、 私たちなりの「好き」と「こだわり」を詰め込んだ作品を制作してきました🐇🩷 ありすほりっくとして作ってきた作品を、 これからも楽しんでいただけましたら嬉しいです💕 ⟡・········································・⟡ ☑️ 男優・モデルのプライバシー保護のため、 「作品本編」でも顔にはぼかしを入れています。 ☑️ 予告なく投稿動画・写真等を削除する場合がございます。 あらかじめご了承ください。 ☑️ 当サークルでは、動画・画像・投稿コンテンツを無断転載することを禁止しています。 ⟡・········································・⟡ 新しいお知らせがある際は、 こちらのファンクラブやSNSにてご案内いたします🐇💌 - Powered by RSSHub",
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
