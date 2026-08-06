# iwara - User

## Coverage
`index-only`

## Route
- Namespace: `iwara`
- Namespace Name: `iwara`
- Route Path: `/iwara/users/:username/:type?`
- Route Name: `User`
- Example: `/iwara/users/kelpie/video`
- URL: `www.iwara.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: username, can find in userpage
- `type`: content type, can be video or image, default is video


## Features
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/iwara/users/kelpie/video",
  "features": {
    "nsfw": true
  },
  "heat": 157,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "User",
  "parameters": {
    "type": "content type, can be video or image, default is video",
    "username": "username, can find in userpage"
  },
  "path": "/users/:username/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "user1263963's iwara - Videos - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60202923086415884",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iwara.tv/users/user1263963",
      "title": "user1263963's iwara - Videos",
      "type": "feed",
      "url": "rsshub://iwara/users/user1263963"
    },
    {
      "description": "inwerwm's iwara - Videos - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60202923086415887",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iwara.tv/users/inwerwm",
      "title": "inwerwm's iwara - Videos",
      "type": "feed",
      "url": "rsshub://iwara/users/inwerwm"
    }
  ]
}
```
