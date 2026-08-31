# Hacking8 - 信息流

## Coverage
`index-only`

## Route
- Namespace: `hacking8`
- Namespace Name: `Hacking8`
- Route Path: `/hacking8/:category?`
- Route Name: `信息流`
- Example: `/hacking8`
- URL: `hacking8.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 推荐  | 最近更新 | 漏洞 / PoC 监控 | PDF |
| ----- | -------- | --------------- | --- |
| likes | index    | vul-poc         | pdf |

## Parameters
- `category`: 分类，见下表，默认为最近更新


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
  - `hacking8.com/index/:category`
  - `hacking8.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 推荐  | 最近更新 | 漏洞 / PoC 监控 | PDF |\n| ----- | -------- | --------------- | --- |\n| likes | index    | vul-poc         | pdf |",
  "example": "/hacking8",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "信息流",
  "parameters": {
    "category": "分类，见下表，默认为最近更新"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "hacking8.com/index/:category",
        "hacking8.com/"
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
