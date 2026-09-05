# DeepMind - Blog

## Coverage
`index-only`

## Route
- Namespace: `deepmind`
- Namespace Name: `DeepMind`
- Route Path: `/deepmind/blog`
- Route Name: `Blog`
- Example: `/deepmind/blog`
- URL: `deepmind.com/blog`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `nczitzk, TonyRL`
- Source Location: `blog.ts`
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
  - `deepmind.com/blog`
  - `deepmind.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "example": "/deepmind/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1417,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk",
    "TonyRL"
  ],
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "deepmind.com/blog",
        "deepmind.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Read the latest articles and stories from DeepMind and find out more about our latest breakthroughs in cutting-edge AI research. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42584858677137408",
      "image": "https://assets-global.website-files.com/621d30e84caf0be3291dbf1c/621d336835a91420c6a8dcf2_webclip.png",
      "ownerUserId": null,
      "siteUrl": "https://deepmind.google/blog//blog",
      "title": "Google DeepMind News",
      "type": "feed",
      "url": "rsshub://deepmind/blog"
    }
  ],
  "url": "deepmind.com/blog"
}
```
