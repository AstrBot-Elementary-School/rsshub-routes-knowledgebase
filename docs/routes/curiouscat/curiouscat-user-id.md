# CuriousCat - User

## Coverage
`index-only`

## Route
- Namespace: `curiouscat`
- Namespace Name: `CuriousCat`
- Route Path: `/curiouscat/user/:id`
- Route Name: `User`
- Example: `/curiouscat/user/username`
- URL: `curiouscat.live`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `lucasew`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: username that is in the URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `curiouscat.live/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/curiouscat/user/username",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "lucasew"
  ],
  "name": "User",
  "parameters": {
    "id": "username that is in the URL"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "curiouscat.live/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
