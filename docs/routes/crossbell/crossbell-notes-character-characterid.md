# Crossbell - Notes of character

## Coverage
`index-only`

## Route
- Namespace: `crossbell`
- Namespace Name: `Crossbell`
- Route Path: `/crossbell/notes/character/:characterId`
- Route Name: `Notes of character`
- Example: `/crossbell/notes/character/10`
- URL: `crossbell.io/*`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `notes/character.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `characterId`: N


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
  - `crossbell.io/*`
- `target`: `/notes`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/crossbell/notes/character/10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "notes/character.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Notes of character",
  "parameters": {
    "characterId": "N"
  },
  "path": "/notes/character/:characterId",
  "radar": [
    {
      "source": [
        "crossbell.io/*"
      ],
      "target": "/notes"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Crossbell Notes from 云野阁 - Powered by RSSHub",
      "errorAt": "2026-01-27T15:26:50.187Z",
      "errorMessage": "[GET] \"https://indexer.crossbell.io/v1/notes?characterId=73369&includeCharacter=true\": <no response> fetch failed (Connect Timeout Error (attempted address: indexer.crossbell.io:443, timeout: 10000ms))\n",
      "id": "146868883707305984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xchar.app/nyyg",
      "title": "Crossbell Notes from 云野阁",
      "type": "feed",
      "url": "rsshub://crossbell/notes/character/73369"
    },
    {
      "description": "Crossbell Notes from 棒无 - Powered by RSSHub",
      "errorAt": "2026-07-23T18:50:07.351Z",
      "errorMessage": "[GET] \"https://indexer.crossbell.io/v1/notes?characterId=69522&includeCharacter=true\": <no response> fetch failed (Connect Timeout Error (attempted address: indexer.crossbell.io:443, timeout: 10000ms))\n",
      "id": "54887751043994624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xchar.app/bangwu",
      "title": "Crossbell Notes from 棒无",
      "type": "feed",
      "url": "rsshub://crossbell/notes/character/69522"
    }
  ],
  "url": "crossbell.io/*"
}
```
