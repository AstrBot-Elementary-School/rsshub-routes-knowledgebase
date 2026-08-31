# Daily.dev - User Posts

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/user/:userId`
- Route Name: `User Posts`
- Example: `/daily/user/kramer`
- URL: `app.daily.dev`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/:userId/posts`
  - `app.daily.dev/:userId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/user/kramer",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Posts",
  "path": "/user/:userId",
  "radar": [
    {
      "source": [
        "app.daily.dev/:userId/posts",
        "app.daily.dev/:userId"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "app.daily.dev"
}
```
