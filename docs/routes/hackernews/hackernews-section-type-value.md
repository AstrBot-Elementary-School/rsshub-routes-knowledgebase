# Hacker News - Stories

## Coverage
`index-only`

## Route
- Namespace: `hackernews`
- Namespace Name: `Hacker News`
- Route Path: `/hackernews/:section?/:type?/:value?`
- Route Name: `Stories`
- Example: `/hackernews/threads/comments_list/dang`
- URL: `ycombinator.com`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `nczitzk, xie-dongping`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Subscribe to Hacker News content by section, user, or minimum points

Examples:

| HN100              | User submitted                       | User threads                       | Comments list                            |
| ------------------ | ------------------------------------ | ---------------------------------- | ---------------------------------------- |
| `/hackernews/over` | `/hackernews/submitted/sources/dang` | `/hackernews/threads/sources/dang` | `/hackernews/threads/comments_list/dang` |

## Parameters
- `section`: {"description": "Content section, default to `index`. Common sections: `index`, `newest`, `ask`, `show`, `jobs`, `over`, `threads`, `submitted`. Any valid HN section (e.g. `best`, `front`, `active`) is also accepted"}
- `type`: {"description": "Content format, default to `sources`. `sources` links to original articles, `comments` fetches full comment threads, `comments_list` shows parent story with single comment"}
- `value`: {"description": "For `threads`/`submitted` sections, set user ID. For `over` section, set minimum points threshold (default 100). For other sections, appended as `?id=<value>` (e.g. `value=dang` → `?id=dang`)"}


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
  - `news.ycombinator.com/:section`
  - `news.ycombinator.com/`

## Raw JSON
```json
{
  "categories": [
    "programming",
    "popular"
  ],
  "description": "Subscribe to Hacker News content by section, user, or minimum points\n\nExamples:\n\n| HN100              | User submitted                       | User threads                       | Comments list                            |\n| ------------------ | ------------------------------------ | ---------------------------------- | ---------------------------------------- |\n| `/hackernews/over` | `/hackernews/submitted/sources/dang` | `/hackernews/threads/sources/dang` | `/hackernews/threads/comments_list/dang` |",
  "example": "/hackernews/threads/comments_list/dang",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6635,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "xie-dongping"
  ],
  "name": "Stories",
  "parameters": {
    "section": {
      "description": "Content section, default to `index`. Common sections: `index`, `newest`, `ask`, `show`, `jobs`, `over`, `threads`, `submitted`. Any valid HN section (e.g. `best`, `front`, `active`) is also accepted"
    },
    "type": {
      "description": "Content format, default to `sources`. `sources` links to original articles, `comments` fetches full comment threads, `comments_list` shows parent story with single comment"
    },
    "value": {
      "description": "For `threads`/`submitted` sections, set user ID. For `over` section, set minimum points threshold (default 100). For other sections, appended as `?id=<value>` (e.g. `value=dang` → `?id=dang`)"
    }
  },
  "path": "/:section?/:type?/:value?",
  "radar": [
    {
      "source": [
        "news.ycombinator.com/:section",
        "news.ycombinator.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Hacker News - Powered by RSSHub",
      "errorAt": "2026-08-23T14:43:44.570Z",
      "errorMessage": "200 ",
      "id": "52325519371718656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ycombinator.com/",
      "title": "Hacker News",
      "type": "feed",
      "url": "rsshub://hackernews"
    },
    {
      "description": "Hacker News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61780263784145920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ycombinator.com/",
      "title": "Hacker News",
      "type": "feed",
      "url": "rsshub://hackernews/index"
    }
  ],
  "view": 0
}
```
