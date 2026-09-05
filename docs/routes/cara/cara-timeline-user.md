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
      "description": "Timeline - Nathan Fowkes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131922100224243712",
      "image": "https://cdn.cara.app/production/profiles/e3934f00-3471-41dc-9700-11b58cfd4044/facebook-profile2.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/nathanfowkesart/all",
      "title": "Timeline - Nathan Fowkes",
      "type": "feed",
      "url": "rsshub://cara/timeline/nathanfowkesart"
    },
    {
      "description": "Timeline - Requinoesis - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131924534067985408",
      "image": "https://cdn.cara.app/production/profiles/3c4bf5ef-7d4e-4165-b65f-6dc781acf326/pu.png",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/requinoesis/all",
      "title": "Timeline - Requinoesis",
      "type": "feed",
      "url": "rsshub://cara/timeline/requinoesis"
    }
  ]
}
```
