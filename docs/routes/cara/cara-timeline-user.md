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
  "heat": 5,
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
      "description": "Timeline - Feng Zhu - Powered by RSSHub",
      "errorAt": "2025-11-26T12:33:50.034Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "63189426042807297",
      "image": "https://cdn.cara.app/production/profiles/d5ba55be-a9af-4ce4-9b3a-0747165de742/feng_headshot_01.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/fengz/all",
      "title": "Timeline - Feng Zhu",
      "type": "feed",
      "url": "rsshub://cara/timeline/fengz"
    },
    {
      "description": "Timeline - Victor Sales - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131925929537537024",
      "image": "https://cdn.cara.app/production/profiles/c0bf0283-3381-4128-81e1-706b580b8ddf/The_Dhow_Rostos7.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/vsalesv/all",
      "title": "Timeline - Victor Sales",
      "type": "feed",
      "url": "rsshub://cara/timeline/vsalesv"
    }
  ]
}
```
