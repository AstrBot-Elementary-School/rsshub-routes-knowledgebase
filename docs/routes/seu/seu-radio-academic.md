# 东南大学 - 信息科学与工程学院学术活动

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/seu/radio/academic`
- Route Name: `信息科学与工程学院学术活动`
- Example: `/seu/radio/academic`
- URL: `radio.seu.edu.cn/_s29/15986/list.psp`
- Language: `_None_`
- Categories: `university`
- Maintainers: `HenryQW`
- Source Location: `radio/academic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `radio.seu.edu.cn/_s29/15986/list.psp`
  - `radio.seu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/seu/radio/academic",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "radio/academic.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "信息科学与工程学院学术活动",
  "parameters": {},
  "path": "/radio/academic",
  "radar": [
    {
      "source": [
        "radio.seu.edu.cn/_s29/15986/list.psp",
        "radio.seu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "radio.seu.edu.cn/_s29/15986/list.psp"
}
```
