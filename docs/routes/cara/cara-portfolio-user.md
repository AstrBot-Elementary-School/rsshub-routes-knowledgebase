# Cara - Portfolio

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/cara/portfolio/:user`
- Route Name: `Portfolio`
- Example: `/cara/portfolio/fengz`
- URL: `cara.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `portfolio.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cara.app/:user`
  - `cara.app/:user/*`
- `target`: `/portfolio/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/portfolio/fengz",
  "heat": 26,
  "location": "portfolio.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Portfolio",
  "parameters": {
    "user": "username"
  },
  "path": "/portfolio/:user",
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/portfolio/:user"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Portfolio - YUE - Powered by RSSHub",
      "errorAt": "2025-11-26T12:19:07.802Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127387638857893888",
      "image": "https://cdn.cara.app/production/profiles/04fb2142-fc7a-4a11-9e5a-8035b5267327/27029931-E30C-4C04-B673-0375C5EDD112.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/yue-art/portfolio",
      "title": "Portfolio - YUE",
      "type": "feed",
      "url": "rsshub://cara/portfolio/yue-art"
    },
    {
      "description": "Portfolio - Anton Skeor - Powered by RSSHub",
      "errorAt": "2025-11-26T12:40:09.550Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127386290009904128",
      "image": "https://cdn.cara.app/production/profiles/d0ff88c0-9327-43d1-9bc0-6d8cdad500a8/130250239_3682129068510144_4368625358048921473_n.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/tonyskeor/portfolio",
      "title": "Portfolio - Anton Skeor",
      "type": "feed",
      "url": "rsshub://cara/portfolio/tonyskeor"
    }
  ]
}
```
