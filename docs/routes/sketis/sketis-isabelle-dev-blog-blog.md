# Sketis | Website of Dr. Makarius Wenzel - Isabelle Development Blogs

## Coverage
`index-only`

## Route
- Namespace: `sketis`
- Namespace Name: `Sketis | Website of Dr. Makarius Wenzel`
- Route Path: `/sketis/isabelle-dev/blog/:blog`
- Route Name: `Isabelle Development Blogs`
- Example: `/sketis/isabelle-dev/blog/1`
- URL: `isabelle-dev.sketis.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Ritsuka314`
- Source Location: `isabelle-dev/blog/index.ts`
- Source Module: `_None_`

## Description
- Isabelle News: `https://isabelle-dev.sketis.net/phame/blog/view/1/`
- Isabelle Release: `https://isabelle-dev.sketis.net/phame/blog/view/2/`

## Parameters
- `blog`: name of blog (1 for NEWS; 2 for Release)


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
  - `isabelle-dev.sketis.net/phame/`
  - `isabelle-dev.sketis.net/phame/blog/`
  - `isabelle-dev.sketis.net/phame/blog/view/:blog/`
  - `isabelle-dev.sketis.net/phame/post/`
  - `isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/`
- `target`: `/isabelle-dev/blog/1`
### Rule 2
- `source`:
  - `isabelle-dev.sketis.net/phame/`
  - `isabelle-dev.sketis.net/phame/blog/`
  - `isabelle-dev.sketis.net/phame/blog/view/:blog/`
  - `isabelle-dev.sketis.net/phame/post/`
  - `isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/`
- `target`: `/isabelle-dev/blog/2`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "- Isabelle News: `https://isabelle-dev.sketis.net/phame/blog/view/1/`\n- Isabelle Release: `https://isabelle-dev.sketis.net/phame/blog/view/2/`",
  "example": "/sketis/isabelle-dev/blog/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "isabelle-dev/blog/index.ts",
  "maintainers": [
    "Ritsuka314"
  ],
  "name": "Isabelle Development Blogs",
  "parameters": {
    "blog": "name of blog (1 for NEWS; 2 for Release)"
  },
  "path": "/isabelle-dev/blog/:blog",
  "radar": [
    {
      "source": [
        "isabelle-dev.sketis.net/phame/",
        "isabelle-dev.sketis.net/phame/blog/",
        "isabelle-dev.sketis.net/phame/blog/view/:blog/",
        "isabelle-dev.sketis.net/phame/post/",
        "isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/"
      ],
      "target": "/isabelle-dev/blog/1"
    },
    {
      "source": [
        "isabelle-dev.sketis.net/phame/",
        "isabelle-dev.sketis.net/phame/blog/",
        "isabelle-dev.sketis.net/phame/blog/view/:blog/",
        "isabelle-dev.sketis.net/phame/post/",
        "isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/"
      ],
      "target": "/isabelle-dev/blog/2"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "isabelle-dev.sketis.net"
}
```
