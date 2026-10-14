# mixi2 - ユーザー

## Coverage
`index-only`

## Route
- Namespace: `mixi2`
- Namespace Name: `mixi2`
- Route Path: `/mixi2/user/:name/:media?`
- Route Name: `ユーザー`
- Example: `/mixi2/user/@deyo`
- URL: `mixi.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: {"description": "@で始まるユーザー名"}
- `media`: {"description": "`media`を入力するとメディアを含むポストのみを取得、デフォルトは空で全てのポストを取得"}


## Features
- `requireConfig`: [{"description": "mixi2ログイン後の情報。ブラウザのコンソールでクッキーから `auth_token` の値を取得してください", "name": "MIXI2_AUTH_TOKEN"}, {"description": "mixi2ログイン後の情報。ブラウザのコンソールでリクエストヘッダーから `x-auth-key` の値を取得してください", "name": "MIXI2_AUTH_KEY"}]
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `mixi.social/:name`
- `target`: `/user/:name`
- `title`: `ユーザー - ポスト`
### Rule 2
- `source`:
  - `mixi.social/:name`
- `target`: `/user/:name/media`
- `title`: `ユーザー - メディア`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mixi2/user/@deyo",
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
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "ユーザー",
  "parameters": {
    "media": {
      "description": "`media`を入力するとメディアを含むポストのみを取得、デフォルトは空で全てのポストを取得"
    },
    "name": {
      "description": "@で始まるユーザー名"
    }
  },
  "path": "/user/:name/:media?",
  "radar": [
    {
      "source": [
        "mixi.social/:name"
      ],
      "target": "/user/:name",
      "title": "ユーザー - ポスト"
    },
    {
      "source": [
        "mixi.social/:name"
      ],
      "target": "/user/:name/media",
      "title": "ユーザー - メディア"
    }
  ],
  "topFeeds": [],
  "view": 1
}
```
