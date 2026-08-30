# Behance - User Works

## Coverage
`index-only`

## Route
- Namespace: `behance`
- Namespace Name: `Behance`
- Route Path: `/behance/:user/:type?`
- Route Name: `User Works`
- Example: `/behance/mishapetrick`
- URL: `www.behance.net`
- Language: `_None_`
- Categories: `design, popular`
- Maintainers: `MisteryMonster`
- Source Location: `user.tsx`
- Source Module: `_None_`

## Description
Behance user's profile URL, like <https://www.behance.net/mishapetrick> the username will be `mishapetrick`。

## Parameters
- `user`: username
- `type`: {"default": "projects", "description": "type", "options": [{"label": "projects", "value": "projects"}, {"label": "appreciated", "value": "appreciated"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "design",
    "popular"
  ],
  "description": "Behance user's profile URL, like <https://www.behance.net/mishapetrick> the username will be `mishapetrick`。",
  "example": "/behance/mishapetrick",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1657,
  "location": "user.tsx",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "User Works",
  "parameters": {
    "type": {
      "default": "projects",
      "description": "type",
      "options": [
        {
          "label": "projects",
          "value": "projects"
        },
        {
          "label": "appreciated",
          "value": "appreciated"
        }
      ]
    },
    "user": "username"
  },
  "path": "/:user/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Rondesignlab ⭐️'s projects - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60616941982567424",
      "image": "https://pps.services.adobe.com/api/profile/070133B04B7456D1992015B9@AdobeID/image/74abc8ee-12d8-4690-8980-fd0681e41ecc/50",
      "ownerUserId": null,
      "siteUrl": "https://www.behance.net/rondesignlab/projects",
      "title": "Rondesignlab ⭐️'s projects",
      "type": "feed",
      "url": "rsshub://behance/rondesignlab"
    },
    {
      "description": "Petrick Animation's projects - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56578471053323264",
      "image": "https://pps.services.adobe.com/api/profile/705741C3536196240A490D45@AdobeID/image/3a1f0f66-ebf9-4480-af90-ed75e7c49829/50",
      "ownerUserId": null,
      "siteUrl": "https://www.behance.net/mishapetrick/projects",
      "title": "Petrick Animation's projects",
      "type": "feed",
      "url": "rsshub://behance/mishapetrick"
    }
  ],
  "view": 2
}
```
