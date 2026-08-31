# UK Parliament - House of Lords Library

## Coverage
`index-only`

## Route
- Namespace: `parliament.uk`
- Namespace Name: `UK Parliament`
- Route Path: `/parliament.uk/lordslibrary/type/:topic?`
- Route Name: `House of Lords Library`
- Example: `/parliament.uk/lordslibrary/type/research-briefing`
- URL: `parliament.uk`
- Language: `_None_`
- Categories: `government`
- Maintainers: `AntiKnot`
- Source Location: `lordslibrary.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: research by topic, string, example: [research-briefing|buisness|economy]


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "government"
  ],
  "example": "/parliament.uk/lordslibrary/type/research-briefing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "lordslibrary.ts",
  "maintainers": [
    "AntiKnot"
  ],
  "name": "House of Lords Library",
  "parameters": {
    "topic": "research by topic, string, example: [research-briefing|buisness|economy]"
  },
  "path": "/lordslibrary/type/:topic?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
