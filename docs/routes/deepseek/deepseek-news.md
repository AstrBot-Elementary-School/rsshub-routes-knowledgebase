# Deepseek - 新闻

## Coverage
`index-only`

## Route
- Namespace: `deepseek`
- Namespace Name: `Deepseek`
- Route Path: `/deepseek/news`
- Route Name: `新闻`
- Example: `/deepseek/news`
- URL: `api-docs.deepseek.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `1837634311`
- Source Location: `news.ts`
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
  - `api-docs.deepseek.com`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/deepseek/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 402,
  "location": "news.ts",
  "maintainers": [
    "1837634311"
  ],
  "name": "新闻",
  "path": "/news",
  "radar": [
    {
      "source": [
        "api-docs.deepseek.com"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "DeepSeek 新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "94620391342854144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://api-docs.deepseek.com/zh-cn",
      "title": "DeepSeek 新闻",
      "type": "feed",
      "url": "rsshub://deepseek/news"
    }
  ]
}
```
