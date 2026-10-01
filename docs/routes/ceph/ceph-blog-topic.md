# Ceph - Blog

## Coverage
`index-only`

## Route
- Namespace: `ceph`
- Namespace Name: `Ceph`
- Route Path: `/ceph/blog/:topic?`
- Route Name: `Blog`
- Example: `/ceph/blog/a11y`
- URL: `ceph.io`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `pandada8`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: filter blog post by category, return all posts if not specified


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
  - `ceph.io/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/ceph/blog/a11y",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "blog.ts",
  "maintainers": [
    "pandada8"
  ],
  "name": "Blog",
  "parameters": {
    "category": "filter blog post by category, return all posts if not specified"
  },
  "path": "/blog/:topic?",
  "radar": [
    {
      "source": [
        "ceph.io/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Ceph Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76188656176061440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ceph.io/en/news/blog/",
      "title": "Ceph Blog",
      "type": "feed",
      "url": "rsshub://ceph/blog/a11y"
    },
    {
      "description": "Ceph Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71377061043192832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ceph.io/en/news/blog/",
      "title": "Ceph Blog",
      "type": "feed",
      "url": "rsshub://ceph/blog/:topic"
    }
  ],
  "url": "ceph.io"
}
```
