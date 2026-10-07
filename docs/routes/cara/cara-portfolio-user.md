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
      "description": "Portfolio - Tonyartist - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131925308972938240",
      "image": "https://cdn.cara.app/production/profiles/b1d3b6d2-9a25-430f-bef7-52bf4e845c91/AC66513D-A6ED-4050-ABB0-C3AE0F681733.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/tonyartstudio/portfolio",
      "title": "Portfolio - Tonyartist",
      "type": "feed",
      "url": "rsshub://cara/portfolio/tonyartstudio"
    },
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
    }
  ]
}
```
