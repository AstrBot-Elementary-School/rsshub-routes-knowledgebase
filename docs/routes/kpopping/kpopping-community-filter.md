# kpopping - Community

## Coverage
`index-only`

## Route
- Namespace: `kpopping`
- Namespace Name: `kpopping`
- Route Path: `/kpopping/community/:filter{.+}?`
- Route Name: `Community`
- Example: `/kpopping/community/category=news&idolId=7d8f48d4-97c4-4164-9f04-11febc9c8ac1`
- URL: `kpopping.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, pinapelz`
- Source Location: `community.ts`
- Source Module: `_None_`

## Description
::: tip
Query community posts using filter parameters found on kpopping such as `idolId`, `groupId`, `gender`, `category`, `sort`, etc.
:::

## Parameters
- `filter`: Filter parameters in `key=value&key2=value2` format. Supported keys: `category`, `gender`, `sort`, `entityType`, `idolId`, `groupId`


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
  - `kpopping.com/community`
- `target`: `/community`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nQuery community posts using filter parameters found on kpopping such as `idolId`, `groupId`, `gender`, `category`, `sort`, etc.\n:::",
  "example": "/kpopping/community/category=news&idolId=7d8f48d4-97c4-4164-9f04-11febc9c8ac1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "community.ts",
  "maintainers": [
    "nczitzk",
    "pinapelz"
  ],
  "name": "Community",
  "parameters": {
    "filter": "Filter parameters in `key=value&key2=value2` format. Supported keys: `category`, `gender`, `sort`, `entityType`, `idolId`, `groupId`"
  },
  "path": "/community/:filter{.+}?",
  "radar": [
    {
      "source": [
        "kpopping.com/community"
      ],
      "target": "/community"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "kpopping.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n支持通过 `idolId`、`groupId`、`gender`、`category`、`sort` 等过滤条件获取新闻与社区帖子。\n:::",
    "name": "Community",
    "parameters": {
      "filter": "以 `key=value&key2=value2` 格式传递的过滤参数。支持的 key 包括 `category`、`gender`、`sort`、`entityType`、`idolId`、`groupId`"
    }
  }
}
```
