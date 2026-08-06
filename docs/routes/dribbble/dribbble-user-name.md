# Dribbble - User (or team)

## Coverage
`index-only`

## Route
- Namespace: `dribbble`
- Namespace Name: `Dribbble`
- Route Path: `/dribbble/user/:name`
- Route Name: `User (or team)`
- Example: `/dribbble/user/google`
- URL: `dribbble.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `DIYgod, loganrockmore`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: username, available in user's homepage URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `dribbble.com/:name`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/dribbble/user/google",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 477,
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "loganrockmore"
  ],
  "name": "User (or team)",
  "parameters": {
    "name": "username, available in user's homepage URL"
  },
  "path": "/user/:name",
  "radar": [
    {
      "source": [
        "dribbble.com/:name"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "𝔅𝔢𝔰𝔱𝔖𝔢𝔯𝔳𝔢𝔡𝔅𝔬𝔩𝔡 | Growing brands driven by Bold™ ideas. Design, Motion, 3D & Art Direction. | Connect with them on Dribbble; the global community for designers and creative professionals. - Powered by RSSHub",
      "errorAt": "2025-08-14T07:04:02.550Z",
      "errorMessage": "Cannot read properties of undefined (reading 'name')\n",
      "id": "56130033776808974",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dribbble.com/BestServedBold",
      "title": "Dribbble - user BestServedBold",
      "type": "feed",
      "url": "rsshub://dribbble/user/BestServedBold"
    },
    {
      "description": "Gleb Kuznetsov ✈ | A designer transforms ideas into reality. As technology gets smarter, reality is exploding. Today, it takes an artist to make human and product interaction awe-inspiring. Connection is key. Gleb is crafting the future of digital experiences through emotional design. 🇺🇸🇨🇭 | Connect with them on Dribbble; the global community for designers and creative professionals. - Powered by RSSHub",
      "errorAt": "2025-06-03T14:17:45.714Z",
      "errorMessage": "Cannot read properties of undefined (reading 'name')\n",
      "id": "56130033776808982",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dribbble.com/glebich",
      "title": "Dribbble - user glebich",
      "type": "feed",
      "url": "rsshub://dribbble/user/glebich"
    }
  ]
}
```
