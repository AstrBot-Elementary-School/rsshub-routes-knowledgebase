# Civitai - User Article

## Coverage
`index-only`

## Route
- Namespace: `civitai`
- Namespace Name: `Civitai`
- Route Path: `/civitai/user/:username/articles`
- Route Name: `User Article`
- Example: `/civitai/user/Chenkin/articles`
- URL: `civitai.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Username


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `civitai.com/user/:username`
  - `civitai.com/user/:username/articles`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/civitai/user/Chenkin/articles",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Article",
  "parameters": {
    "username": "Username"
  },
  "path": "/user/:username/articles",
  "radar": [
    {
      "source": [
        "civitai.com/user/:username",
        "civitai.com/user/:username/articles"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
