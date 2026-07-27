# 幻之羁绊动漫网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `005`
- Namespace Name: `幻之羁绊动漫网`
- Route Path: `/005/:category?`
- Route Name: `资讯`
- Example: `/005/zx`
- URL: `005.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| 二次元资讯 | 慢慢说 | 道听途说 | 展会资讯 |
| ---------- | ------ | -------- | -------- |
| zx         | zwh    | dtts     | zh       |

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，默认为二次元资讯


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
  - `005.tv/:category`
### Rule 2
- `title`: `二次元资讯`
- `source`:
  - `005.tv/zx/`
- `target`: `/005/zx`
### Rule 3
- `title`: `慢慢说`
- `source`:
  - `005.tv/zwh/`
- `target`: `/005/zwh`
### Rule 4
- `title`: `道听途说`
- `source`:
  - `005.tv/dtts/`
- `target`: `/005/dtts`
### Rule 5
- `title`: `展会资讯`
- `source`:
  - `005.tv/zh/`
- `target`: `/005/zh`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 二次元资讯 | 慢慢说 | 道听途说 | 展会资讯 |\n| ---------- | ------ | -------- | -------- |\n| zx         | zwh    | dtts     | zh       |",
  "example": "/005/zx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，默认为二次元资讯"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "005.tv/:category"
      ]
    },
    {
      "source": [
        "005.tv/zx/"
      ],
      "target": "/005/zx",
      "title": "二次元资讯"
    },
    {
      "source": [
        "005.tv/zwh/"
      ],
      "target": "/005/zwh",
      "title": "慢慢说"
    },
    {
      "source": [
        "005.tv/dtts/"
      ],
      "target": "/005/dtts",
      "title": "道听途说"
    },
    {
      "source": [
        "005.tv/zh/"
      ],
      "target": "/005/zh",
      "title": "展会资讯"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "005.tv - Powered by RSSHub",
      "errorAt": "2026-06-21T15:38:10.927Z",
      "errorMessage": "[GET] \"https://005.tv/zh/\": <no response> fetch failed (getaddrinfo ENOTFOUND 005.tv)\n",
      "id": "74361174122203136",
      "image": "https://005.tv/templets/muban/style/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://005.tv/zh/",
      "title": "005.tv",
      "type": "feed",
      "url": "rsshub://005/zh"
    }
  ],
  "url": "005.tv"
}
```
