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
    }
  ]
}
```
