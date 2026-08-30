# LeetCode - Articles

## Coverage
`index-only`

## Route
- Namespace: `leetcode`
- Namespace Name: `LeetCode`
- Route Path: `/leetcode/articles`
- Route Name: `Articles`
- Example: `/leetcode/articles`
- URL: `leetcode.com/articles`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `LogicJake`
- Source Location: `articles.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `leetcode.com/articles`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/leetcode/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "articles.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "Articles",
  "parameters": {},
  "path": "/articles",
  "radar": [
    {
      "source": [
        "leetcode.com/articles"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-07T21:05:40.512Z",
      "errorMessage": "502 \n[GET] \"https://leetcode.com/articles/\": 403 Forbidden\n",
      "id": "187621803897127940",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://leetcode/articles"
    }
  ],
  "url": "leetcode.com/articles"
}
```
