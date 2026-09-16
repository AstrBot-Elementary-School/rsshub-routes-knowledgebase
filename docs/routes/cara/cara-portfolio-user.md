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
  "heat": 5,
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
      "description": "Portfolio - Feng Zhu - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63583660353457152",
      "image": "https://cdn.cara.app/production/profiles/d5ba55be-a9af-4ce4-9b3a-0747165de742/feng_headshot_01.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/fengz/portfolio",
      "title": "Portfolio - Feng Zhu",
      "type": "feed",
      "url": "rsshub://cara/portfolio/fengz"
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
