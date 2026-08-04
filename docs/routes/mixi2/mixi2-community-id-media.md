# mixi2 - コミュニティ

## Coverage
`index-only`

## Route
- Namespace: `mixi2`
- Namespace Name: `mixi2`
- Route Path: `/mixi2/community/:id/:media?`
- Route Name: `コミュニティ`
- Example: `/mixi2/community/62e7e813-d242-4c54-a0ee-0aab5b2bbad2`
- URL: `mixi.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `community.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: {"description": "コミュニティID"}
- `media`: {"description": "`media`を入力するとメディアを含むポストのみを取得、デフォルトは空で全てのポストを取得"}


## Features
- `supportRadar`: true
- `requireConfig`: [{"description": "mixi2ログイン後の情報。ブラウザのコンソールでクッキーから `auth_token` の値を取得してください", "name": "MIXI2_AUTH_TOKEN"}, {"description": "mixi2ログイン後の情報。ブラウザのコンソールでリクエストヘッダーから `x-auth-key` の値を取得してください", "name": "MIXI2_AUTH_KEY"}]

## Radar
### Rule 1
- `source`:
  - `mixi.social/communities/:id`
  - `mixi.social/communities/:id/about`
- `target`: `/community/:id`
- `title`: `コミュニティ - ポスト`
### Rule 2
- `source`:
  - `mixi.social/communities/:id`
  - `mixi.social/communities/:id/about`
- `target`: `/community/:id/media`
- `title`: `コミュニティ - メディア`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mixi2/community/62e7e813-d242-4c54-a0ee-0aab5b2bbad2",
  "features": {
    "requireConfig": [
      {
        "description": "mixi2ログイン後の情報。ブラウザのコンソールでクッキーから `auth_token` の値を取得してください",
        "name": "MIXI2_AUTH_TOKEN"
      },
      {
        "description": "mixi2ログイン後の情報。ブラウザのコンソールでリクエストヘッダーから `x-auth-key` の値を取得してください",
        "name": "MIXI2_AUTH_KEY"
      }
    ],
    "supportRadar": true
  },
  "heat": 5,
  "location": "community.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "コミュニティ",
  "parameters": {
    "id": {
      "description": "コミュニティID"
    },
    "media": {
      "description": "`media`を入力するとメディアを含むポストのみを取得、デフォルトは空で全てのポストを取得"
    }
  },
  "path": "/community/:id/:media?",
  "radar": [
    {
      "source": [
        "mixi.social/communities/:id",
        "mixi.social/communities/:id/about"
      ],
      "target": "/community/:id",
      "title": "コミュニティ - ポスト"
    },
    {
      "source": [
        "mixi.social/communities/:id",
        "mixi.social/communities/:id/about"
      ],
      "target": "/community/:id/media",
      "title": "コミュニティ - メディア"
    }
  ],
  "topFeeds": [
    {
      "description": "#にゃー 📢管理人からのお知らせ 過去のお知らせもあります。ご一読ください。 https://mixi.social/@swkn40/posts/6c6baea4-87ba-4a62-a8fb-659a0ced6c7d 🙅‍♂️猫部では以下はご遠慮ください。 巨大コミュなので、好き嫌い、楽しいや不快、も様々あるので、最低限のルールとコミュニティ内で楽しんでもらうことが基本です。 ・mixi2外への投稿や誘導 ・猫部外への投稿や誘導 ・猫と関係のない投稿や行為 ・宣伝行為 💁‍♀️その他、管理人から見て、参加者が不快に感じるだろうこと、個人間トラブルに発展しそうなこと、やりすぎだと感じた投稿やアカウントは制限します。 - Powered by RSSHub",
      "errorAt": "2026-06-09T11:47:05.363Z",
      "errorMessage": "522 \nMIXI2_AUTH_TOKEN and MIXI2_AUTH_KEY are required\n",
      "id": "157312116099007488",
      "image": "https://media.mixi.social/c/62e7e813-d242-4c54-a0ee-0aab5b2bbad2/i/1b22036a-d603-4cc6-ad41-3fa9c228ba09/image.webp",
      "ownerUserId": null,
      "siteUrl": "https://mixi.social/communities/62e7e813-d242-4c54-a0ee-0aab5b2bbad2/about",
      "title": "猫部 - メディア",
      "type": "feed",
      "url": "rsshub://mixi2/community/62e7e813-d242-4c54-a0ee-0aab5b2bbad2/media"
    }
  ],
  "view": 1
}
```
