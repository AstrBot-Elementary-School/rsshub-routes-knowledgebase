# Cursor - Blog

## Coverage
`index-only`

## Route
- Namespace: `cursor`
- Namespace Name: `Cursor`
- Route Path: `/cursor/blog/:topic?/:locale?`
- Route Name: `Blog`
- Example: `/cursor/blog`
- URL: `cursor.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `johan456789`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `locale`: Locale appended to the route path, e.g. `ja`
- `topic`: Topic: all | product | research | company | news


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cursor.com/blog`
- `target`: `/blog`
### Rule 2
- `source`:
  - `cursor.com/blog/topic/:topic`
- `target`: `/blog/:topic`
### Rule 3
- `source`:
  - `cursor.com/:locale/blog`
- `target`: `/blog/all/:locale`
### Rule 4
- `source`:
  - `cursor.com/:locale/blog/topic/:topic`
- `target`: `/blog/:topic/:locale`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/cursor/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 43,
  "location": "blog.ts",
  "maintainers": [
    "johan456789"
  ],
  "name": "Blog",
  "parameters": {
    "locale": "Locale appended to the route path, e.g. `ja`",
    "topic": "Topic: all | product | research | company | news"
  },
  "path": "/blog/:topic?/:locale?",
  "radar": [
    {
      "source": [
        "cursor.com/blog"
      ],
      "target": "/blog"
    },
    {
      "source": [
        "cursor.com/blog/topic/:topic"
      ],
      "target": "/blog/:topic"
    },
    {
      "source": [
        "cursor.com/:locale/blog"
      ],
      "target": "/blog/all/:locale"
    },
    {
      "source": [
        "cursor.com/:locale/blog/topic/:topic"
      ],
      "target": "/blog/:topic/:locale"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected { '$': { isPermaLink: 'false' } } to deeply equal Any<String>\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:84:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Latest updates and insights from the Cursor team. Learn about AI-powered coding, product updates, and development tips. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "194403390016990208",
      "image": "https://ptht05hbb1ssoooe.public.blob.vercel-storage.com/assets/blog/og/opengraph-blog.png",
      "ownerUserId": null,
      "siteUrl": "https://cursor.com/blog",
      "title": "Blog · Cursor",
      "type": "feed",
      "url": "rsshub://cursor/blog"
    }
  ],
  "url": "cursor.com",
  "view": 0
}
```
