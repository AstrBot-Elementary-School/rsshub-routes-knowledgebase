# Gitpod - Blog

## Coverage
`index-only`

## Route
- Namespace: `gitpod`
- Namespace Name: `Gitpod`
- Route Path: `/gitpod/blog`
- Route Name: `Blog`
- Example: `/gitpod/blog`
- URL: `gitpod.io/blog`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `blog.tsx`
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
  - `gitpod.io/blog`
  - `gitpod.io/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitpod/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "blog.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "gitpod.io/blog",
        "gitpod.io/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The latest news, articles, and opinions around developer experience and remote development in the cloud. - Powered by RSSHub",
      "errorAt": "2024-12-09T13:56:05.950Z",
      "errorMessage": "[GET] \"https://www.gitpod.ioundefined\": <no response> fetch failed (getaddrinfo ENOTFOUND www.gitpod.ioundefined)\n",
      "id": "71838712700015616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gitpod.io/blog",
      "title": "Blog - GitpodGitpod LogoRSS Feed",
      "type": "feed",
      "url": "rsshub://gitpod/blog"
    }
  ],
  "url": "gitpod.io/blog"
}
```
