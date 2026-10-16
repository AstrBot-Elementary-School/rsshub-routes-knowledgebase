# Cara - Likes

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/cara/likes/:user`
- Route Name: `Likes`
- Example: `/cara/likes/fengz`
- URL: `cara.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `likes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: username


## Features
- `requireConfig`: [{"description": "A logged-in cara.app Cookie containing __Secure-next-auth.session-token. Obtain it from your own browser session; it is only sent to https://cara.app.", "name": "CARA_COOKIE"}]

## Radar
### Rule 1
- `source`:
  - `cara.app/:user`
  - `cara.app/:user/*`
- `target`: `/likes/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/likes/fengz",
  "features": {
    "requireConfig": [
      {
        "description": "A logged-in cara.app Cookie containing __Secure-next-auth.session-token. Obtain it from your own browser session; it is only sent to https://cara.app.",
        "name": "CARA_COOKIE"
      }
    ]
  },
  "heat": 8,
  "location": "likes.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Likes",
  "parameters": {
    "user": "username"
  },
  "path": "/likes/:user",
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/likes/:user"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Likes - Feng Zhu - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62800521326571520",
      "image": "https://cdn.cara.app/production/profiles/d5ba55be-a9af-4ce4-9b3a-0747165de742/feng_headshot_01.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/fengz/likes",
      "title": "Likes - Feng Zhu",
      "type": "feed",
      "url": "rsshub://cara/likes/fengz"
    },
    {
      "description": "Likes - Ksenia Palchikova - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "100895480425924620",
      "image": "https://cdn.cara.app/production/profiles/3f45aefb-396a-4518-9986-7e6b69e30c5b/logo.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/kotartist/likes",
      "title": "Likes - Ksenia Palchikova",
      "type": "feed",
      "url": "rsshub://cara/likes/kotartist"
    }
  ]
}
```
