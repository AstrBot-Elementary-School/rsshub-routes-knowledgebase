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
      "description": "Portfolio - K - Powered by RSSHub",
      "errorAt": "2025-11-26T14:00:09.805Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "126048113294879744",
      "image": "https://cdn.cara.app/production/profiles/9368144b-2ca1-43c9-8ff5-90a6c2e23b4b/1000011565.png",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/heikokuru1224/portfolio",
      "title": "Portfolio - K",
      "type": "feed",
      "url": "rsshub://cara/portfolio/heikokuru1224"
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
