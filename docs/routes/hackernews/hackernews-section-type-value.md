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
- Categories: `programming`
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
    "programming"
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
  "heat": 281,
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
    "code": 0
  },
  "topFeeds": [
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
    },
    {
      "description": "Hacker News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54068749119767552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ycombinator.com/news",
      "title": "Hacker News",
      "type": "feed",
      "url": "rsshub://hackernews/news"
    }
  ],
  "view": 0
}
```
