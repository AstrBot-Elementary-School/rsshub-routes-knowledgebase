# Eagle - Blog

## Coverage
`index-only`

## Route
- Namespace: `eagle`
- Namespace Name: `Eagle`
- Route Path: `/eagle/blog/:cate?/:language?`
- Route Name: `Blog`
- Example: `/eagle/blog/en`
- URL: `cn.eagle.cool/blog`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Fatpandac`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cate`: Category, get by URL, `all` by default
- `language`: {"default": "en", "description": "Language", "options": [{"label": "cn", "value": "cn"}, {"label": "tw", "value": "tw"}, {"label": "en", "value": "en"}]}


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
  - `cn.eagle.cool/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/eagle/blog/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "blog.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Blog",
  "parameters": {
    "cate": "Category, get by URL, `all` by default",
    "language": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "cn",
          "value": "cn"
        },
        {
          "label": "tw",
          "value": "tw"
        },
        {
          "label": "en",
          "value": "en"
        }
      ]
    }
  },
  "path": "/blog/:cate?/:language?",
  "radar": [
    {
      "source": [
        "cn.eagle.cool/blog"
      ],
      "target": "/blog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "eagle - 全部 - Powered by RSSHub",
      "errorAt": "2025-06-01T02:42:47.366Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "42579624844251158",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.eagle.cool/blog/",
      "title": "eagle - 全部",
      "type": "feed",
      "url": "rsshub://eagle/blog"
    },
    {
      "description": "eagle - 全部 - Powered by RSSHub",
      "errorAt": "2025-06-01T03:50:16.899Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "54136311534796800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.eagle.cool/blog/",
      "title": "eagle - 全部",
      "type": "feed",
      "url": "rsshub://eagle/blog/cn"
    }
  ],
  "url": "cn.eagle.cool/blog"
}
```
