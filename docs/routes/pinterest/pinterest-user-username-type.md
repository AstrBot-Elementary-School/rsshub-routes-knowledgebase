# Pinterest - User

## Coverage
`index-only`

## Route
- Namespace: `pinterest`
- Namespace Name: `Pinterest`
- Route Path: `/pinterest/user/:username/:type?`
- Route Name: `User`
- Example: `/pinterest/user/howieserious`
- URL: `www.pinterest.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Username
- `type`: {"default": "_created", "description": "Type, default to `_created`", "options": [{"label": "Created", "value": "_created"}, {"label": "Saved", "value": "_saved"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.pinterest.com/:id/:type?`
  - `www.pinterest.com/:id`
- `target`: `/user/:id/:type?`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/pinterest/user/howieserious",
  "heat": 125,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User",
  "parameters": {
    "type": {
      "default": "_created",
      "description": "Type, default to `_created`",
      "options": [
        {
          "label": "Created",
          "value": "_created"
        },
        {
          "label": "Saved",
          "value": "_saved"
        }
      ]
    },
    "username": "Username"
  },
  "path": "/user/:username/:type?",
  "radar": [
    {
      "source": [
        "www.pinterest.com/:id/:type?",
        "www.pinterest.com/:id"
      ],
      "target": "/user/:id/:type?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Arts Thread | ARTS THREAD: The Launchpad for New Creatives! 🔥🔥🔥🚀🚀🚀Just launched🔥🔥🔥Global Creative Graduate Showcase 2025 Global Creative Graduate Showcase for Emerging Artists & Designers worldwide 🌍🌏🌎 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "89935265403863040",
      "image": "https://i.pinimg.com/280x280_RS/34/01/e2/3401e2271da83a7df752097e2961576a.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pinterest.com/artsthread/",
      "title": "Arts Thread (artsthread) - Profile | Pinterest",
      "type": "feed",
      "url": "rsshub://pinterest/user/artsthread/_created"
    },
    {
      "description": "EIGHT DESIGN | 名古屋・東京の建築デザイン事務所エイトデザイン。「楽しむ」をデザインしよう！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92345639854744576",
      "image": "https://i.pinimg.com/280x280_RS/c2/c1/92/c2c19222a0f644db0469545bec1bf829.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pinterest.com/8eightdesign/",
      "title": "EIGHT DESIGN (8eightdesign) - Profile | Pinterest",
      "type": "feed",
      "url": "rsshub://pinterest/user/8eightdesign/%E7%8E%84%E9%96%A2-entrance-home"
    }
  ]
}
```
