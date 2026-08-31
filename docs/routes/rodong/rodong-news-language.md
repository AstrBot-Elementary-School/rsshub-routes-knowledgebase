# Rodong Sinmun 劳动新闻 - News

## Coverage
`index-only`

## Route
- Namespace: `rodong`
- Namespace Name: `Rodong Sinmun 劳动新闻`
- Route Path: `/rodong/news/:language?`
- Route Name: `News`
- Example: `/rodong/news`
- URL: `rodong.rep.kp/cn/index.php`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 조선어 | English | 中文 |
| ------ | ------- | ---- |
| ko     | en      | cn   |

## Parameters
- `language`: Language, see below, `ko` by default


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
  - `rodong.rep.kp/cn/index.php`
  - `rodong.rep.kp/en/index.php`
  - `rodong.rep.kp/ko/index.php`
  - `rodong.rep.kp/cn`
  - `rodong.rep.kp/en`
  - `rodong.rep.kp/ko`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 조선어 | English | 中文 |\n| ------ | ------- | ---- |\n| ko     | en      | cn   |",
  "example": "/rodong/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "language": "Language, see below, `ko` by default"
  },
  "path": "/news/:language?",
  "radar": [
    {
      "source": [
        "rodong.rep.kp/cn/index.php",
        "rodong.rep.kp/en/index.php",
        "rodong.rep.kp/ko/index.php",
        "rodong.rep.kp/cn",
        "rodong.rep.kp/en",
        "rodong.rep.kp/ko"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "rodong.rep.kp/cn/index.php"
}
```
