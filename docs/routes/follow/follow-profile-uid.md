# Follow - User subscriptions

## Coverage
`index-only`

## Route
- Namespace: `follow`
- Namespace Name: `Follow`
- Route Path: `/follow/profile/:uid`
- Route Name: `User subscriptions`
- Example: `/follow/profile/41279032429549568`
- URL: `app.follow.is`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `KarasuShin, DIYgod, DFobain`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: User ID or user handle


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `app.follow.is/profile/:uid`
- `target`: `/profile/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/follow/profile/41279032429549568",
  "features": {
    "supportRadar": true
  },
  "heat": 5136,
  "location": "profile.ts",
  "maintainers": [
    "KarasuShin",
    "DIYgod",
    "DFobain"
  ],
  "name": "User subscriptions",
  "parameters": {
    "uid": "User ID or user handle"
  },
  "path": "/profile/:uid",
  "radar": [
    {
      "source": [
        "app.follow.is/profile/:uid"
      ],
      "target": "/profile/:uid"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Follow's subscriptions - Powered by RSSHub",
      "errorAt": "2026-05-02T05:07:24.820Z",
      "errorMessage": "[GET] \"https://api.follow.is/subscriptions?userId=41469671337837568\": 401 Unauthorized\n[GET] \"https://api.follow.is/subscriptions?userId=41469671337837568\": 401 Unauthorized\n[GET] \"https://api.follow.is/subscriptions?userId=41469671337837568\": 401 \n[GET] \"https://api.follow.is/subscriptions?userId=41469671337837568\": 401 Unauthorized\n",
      "id": "73371743844601856",
      "image": "https://avatars.githubusercontent.com/u/47667850?v=4",
      "ownerUserId": null,
      "siteUrl": "https://app.follow.is/share/users/41469671337837568",
      "title": "Follow's subscriptions",
      "type": "feed",
      "url": "rsshub://follow/profile/41469671337837568"
    },
    {
      "description": "DIYgod's subscriptions - Powered by RSSHub",
      "errorAt": "2026-05-02T04:58:02.716Z",
      "errorMessage": "[GET] \"https://api.follow.is/subscriptions?userId=41125409313095680\": 401 Unauthorized\n[GET] \"https://api.follow.is/subscriptions?userId=41125409313095680\": 401 Unauthorized\n[GET] \"https://api.follow.is/subscriptions?userId=41125409313095680\": 401 Unauthorized\n[GET] \"https://api.follow.is/subscriptions?userId=41125409313095680\": 401 Unauthorized\nAuthentication failed. Access denied.\n/follow/profile/41125409313095680\n[GET] \"https://api.follow.is/subscriptions?userId=41125409313095680\": 401 Unauthorized\n[GET] \"https://api.follow.is/subscriptions?userId=41125409313095680\": 401 Unauthorized\n",
      "id": "58564329155994624",
      "image": "https://assets.folo.is/avatars/fb375d2d6d76367584300836196333fd.jpg",
      "ownerUserId": null,
      "siteUrl": "https://app.follow.is/share/users/41125409313095680",
      "title": "DIYgod's subscriptions",
      "type": "feed",
      "url": "rsshub://follow/profile/41125409313095680"
    }
  ],
  "view": 5
}
```
