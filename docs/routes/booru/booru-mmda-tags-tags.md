# Booru - MMDArchive 标签查询

## Coverage
`index-only`

## Route
- Namespace: `booru`
- Namespace Name: `Booru`
- Route Path: `/booru/mmda/tags/:tags?`
- Route Name: `MMDArchive 标签查询`
- Example: `/booru/mmda/tags/full_body%20blue_eyes`
- URL: `mmda.booru.org`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `N78Wy`
- Source Location: `mmda.ts`
- Source Module: `_None_`

## Description
For example:

- 默认查询 (什么 tag 都不加)：`/booru/mmda/tags`
- 默认查询单个 tag：`/booru/mmda/tags/full_body`
- 默认查询多个 tag：`/booru/mmda/tags/full_body%20blue_eyes`
- 默认查询根据作者查询：`/booru/mmda/tags/user:xxxx`

## Parameters
- `tags`: 标签，多个标签使用 `%20` 连接，如需根据作者查询则在 `user:` 后接上作者名，如：`user:xxxx`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mmda.booru.org/index.php`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "For example:\n\n- 默认查询 (什么 tag 都不加)：`/booru/mmda/tags`\n- 默认查询单个 tag：`/booru/mmda/tags/full_body`\n- 默认查询多个 tag：`/booru/mmda/tags/full_body%20blue_eyes`\n- 默认查询根据作者查询：`/booru/mmda/tags/user:xxxx`",
  "example": "/booru/mmda/tags/full_body%20blue_eyes",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 16,
  "location": "mmda.ts",
  "maintainers": [
    "N78Wy"
  ],
  "name": "MMDArchive 标签查询",
  "parameters": {
    "tags": "标签，多个标签使用 `%20` 连接，如需根据作者查询则在 `user:` 后接上作者名，如：`user:xxxx`"
  },
  "path": "/mmda/tags/:tags?",
  "radar": [
    {
      "source": [
        "mmda.booru.org/index.php"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": " - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63500086553914368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mmda.booru.org/index.php?page=post&s=list",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://booru/mmda/tags"
    },
    {
      "description": "blue_archive - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84529539746481152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mmda.booru.org/index.php?page=post&s=list&tags=blue_archive",
      "title": "blue_archive",
      "type": "feed",
      "url": "rsshub://booru/mmda/tags/blue_archive"
    }
  ]
}
```
