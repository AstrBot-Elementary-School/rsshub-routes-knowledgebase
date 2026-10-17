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
- `language`: {"default": "cn", "description": "Language", "options": [{"label": "cn", "value": "cn"}, {"label": "tw", "value": "tw"}, {"label": "en", "value": "en"}, {"label": "jp", "value": "jp"}, {"label": "kr", "value": "kr"}, {"label": "es", "value": "es"}, {"label": "de", "value": "de"}, {"label": "ru", "value": "ru"}]}


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
### Rule 2
- `source`:
  - `cn.eagle.cool/blog/design-resources`
- `target`: `/blog/design-resources/cn`
### Rule 3
- `source`:
  - `cn.eagle.cool/blog/learn-design`
- `target`: `/blog/learn-design/cn`
### Rule 4
- `source`:
  - `cn.eagle.cool/blog/inside-eagle`
- `target`: `/blog/inside-eagle/cn`
### Rule 5
- `source`:
  - `cn.eagle.cool/blog/why-eagle`
- `target`: `/blog/why-eagle/cn`
### Rule 6
- `source`:
  - `tw.eagle.cool/blog/design-resources`
- `target`: `/blog/design-resources/tw`
### Rule 7
- `source`:
  - `tw.eagle.cool/blog/learn-design`
- `target`: `/blog/learn-design/tw`
### Rule 8
- `source`:
  - `tw.eagle.cool/blog/inside-eagle`
- `target`: `/blog/inside-eagle/tw`
### Rule 9
- `source`:
  - `tw.eagle.cool/blog/why-eagle`
- `target`: `/blog/why-eagle/tw`
### Rule 10
- `source`:
  - `tw.eagle.cool/blog`
- `target`: `/blog/all/tw`
### Rule 11
- `source`:
  - `en.eagle.cool/blog/design-resources`
- `target`: `/blog/design-resources/en`
### Rule 12
- `source`:
  - `en.eagle.cool/blog/learn-design`
- `target`: `/blog/learn-design/en`
### Rule 13
- `source`:
  - `en.eagle.cool/blog/inside-eagle`
- `target`: `/blog/inside-eagle/en`
### Rule 14
- `source`:
  - `en.eagle.cool/blog/why-eagle`
- `target`: `/blog/why-eagle/en`
### Rule 15
- `source`:
  - `en.eagle.cool/blog`
- `target`: `/blog/all/en`

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
      "default": "cn",
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
        },
        {
          "label": "jp",
          "value": "jp"
        },
        {
          "label": "kr",
          "value": "kr"
        },
        {
          "label": "es",
          "value": "es"
        },
        {
          "label": "de",
          "value": "de"
        },
        {
          "label": "ru",
          "value": "ru"
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
    },
    {
      "source": [
        "cn.eagle.cool/blog/design-resources"
      ],
      "target": "/blog/design-resources/cn"
    },
    {
      "source": [
        "cn.eagle.cool/blog/learn-design"
      ],
      "target": "/blog/learn-design/cn"
    },
    {
      "source": [
        "cn.eagle.cool/blog/inside-eagle"
      ],
      "target": "/blog/inside-eagle/cn"
    },
    {
      "source": [
        "cn.eagle.cool/blog/why-eagle"
      ],
      "target": "/blog/why-eagle/cn"
    },
    {
      "source": [
        "tw.eagle.cool/blog/design-resources"
      ],
      "target": "/blog/design-resources/tw"
    },
    {
      "source": [
        "tw.eagle.cool/blog/learn-design"
      ],
      "target": "/blog/learn-design/tw"
    },
    {
      "source": [
        "tw.eagle.cool/blog/inside-eagle"
      ],
      "target": "/blog/inside-eagle/tw"
    },
    {
      "source": [
        "tw.eagle.cool/blog/why-eagle"
      ],
      "target": "/blog/why-eagle/tw"
    },
    {
      "source": [
        "tw.eagle.cool/blog"
      ],
      "target": "/blog/all/tw"
    },
    {
      "source": [
        "en.eagle.cool/blog/design-resources"
      ],
      "target": "/blog/design-resources/en"
    },
    {
      "source": [
        "en.eagle.cool/blog/learn-design"
      ],
      "target": "/blog/learn-design/en"
    },
    {
      "source": [
        "en.eagle.cool/blog/inside-eagle"
      ],
      "target": "/blog/inside-eagle/en"
    },
    {
      "source": [
        "en.eagle.cool/blog/why-eagle"
      ],
      "target": "/blog/why-eagle/en"
    },
    {
      "source": [
        "en.eagle.cool/blog"
      ],
      "target": "/blog/all/en"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "博客 | Eagle - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54136311534796800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.eagle.cool/blog/",
      "title": "博客 | Eagle",
      "type": "feed",
      "url": "rsshub://eagle/blog/cn"
    },
    {
      "description": "博客 | Eagle - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42579624844251158",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.eagle.cool/blog/",
      "title": "博客 | Eagle",
      "type": "feed",
      "url": "rsshub://eagle/blog"
    }
  ],
  "url": "cn.eagle.cool/blog"
}
```
