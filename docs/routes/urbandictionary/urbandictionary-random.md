# Urban Dictionary - Random words

## Coverage
`index-only`

## Route
- Namespace: `urbandictionary`
- Namespace Name: `Urban Dictionary`
- Route Path: `/urbandictionary/random`
- Route Name: `Random words`
- Example: `/urbandictionary/random`
- URL: `urbandictionary.com/random.php`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `random.tsx`
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
  - `urbandictionary.com/random.php`
  - `urbandictionary.com/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/urbandictionary/random",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "random.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Random words",
  "parameters": {},
  "path": "/random",
  "radar": [
    {
      "source": [
        "urbandictionary.com/random.php",
        "urbandictionary.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 549075364281 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Urban Dictionary: Random words - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148054920761453568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.urbandictionary.com/random.php",
      "title": "Urban Dictionary: Random words",
      "type": "feed",
      "url": "rsshub://urbandictionary/random"
    }
  ],
  "url": "urbandictionary.com/random.php"
}
```
