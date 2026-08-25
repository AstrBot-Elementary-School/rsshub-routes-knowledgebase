# Gab - User's Posts

## Coverage
`index-only`

## Route
- Namespace: `gab`
- Namespace Name: `Gab`
- Route Path: `/gab/user/:username`
- Route Name: `User's Posts`
- Example: `/gab/user/AmericanFamAssc`
- URL: `gab.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `zphw`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Username


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/gab/user/AmericanFamAssc",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "User's Posts",
  "parameters": {
    "username": "Username"
  },
  "path": "/user/:username",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
