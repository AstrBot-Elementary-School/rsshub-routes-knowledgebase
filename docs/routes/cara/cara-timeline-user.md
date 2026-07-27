# Cara - Timeline

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/cara/timeline/:user`
- Route Name: `Timeline`
- Example: `/cara/timeline/fengz`
- URL: `cara.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `timeline.ts`
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
- `target`: `/timeline/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/timeline/fengz",
  "heat": 9,
  "location": "timeline.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Timeline",
  "parameters": {
    "user": "username"
  },
  "path": "/timeline/:user",
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/timeline/:user"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Timeline - 127 - Powered by RSSHub",
      "errorAt": "2025-11-26T14:20:48.941Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127386983426590720",
      "image": "https://cdn.cara.app/production/profiles/f1a02228-6fa6-408e-9f03-ce991a568ba1/A1670231-0D18-40F6-A51A-AE28A40F7278.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/alonelee127/all",
      "title": "Timeline - 127",
      "type": "feed",
      "url": "rsshub://cara/timeline/alonelee127"
    },
    {
      "description": "Timeline - Rodrigo Goulao de Sousa - Powered by RSSHub",
      "errorAt": "2025-11-26T14:00:44.455Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127384139525444608",
      "image": "https://cdn.cara.app/production/profiles/34966e18-5684-4d9d-afab-838babacdc30/465BAAB1-DDE7-42C3-9A1F-E078CF2DA69B.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/rodrigogsousa/all",
      "title": "Timeline - Rodrigo Goulao de Sousa",
      "type": "feed",
      "url": "rsshub://cara/timeline/rodrigogsousa"
    }
  ]
}
```
