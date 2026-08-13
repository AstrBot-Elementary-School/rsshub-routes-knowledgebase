# Coomer - Posts

## Coverage
`index-only`

## Route
- Namespace: `coomer`
- Namespace Name: `Coomer`
- Route Path: `/coomer/:source?/:id?`
- Route Name: `Posts`
- Example: `/coomer`
- URL: `coomer.st`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk, AiraNadih`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
Sources

| Posts | OnlyFans | Fansly | CandFans |
| ----- | -------- | ------ | -------- |
| posts | onlyfans | fansly | candfans |

::: tip
When `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.
There is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.
:::

## Parameters
- `source`: Source, see below, Posts by default
- `id`: User id, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `coomer.st/`
- `target`: ``
### Rule 2
- `source`:
  - `coomer.st/:source/user/:id`
- `target`: `/:source/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Sources\n\n| Posts | OnlyFans | Fansly | CandFans |\n| ----- | -------- | ------ | -------- |\n| posts | onlyfans | fansly | candfans |\n\n::: tip\nWhen `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.\nThere is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.\n:::",
  "example": "/coomer",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 336,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk",
    "AiraNadih"
  ],
  "name": "Posts",
  "parameters": {
    "id": "User id, can be found in URL",
    "source": "Source, see below, Posts by default"
  },
  "path": "/:source?/:id?",
  "radar": [
    {
      "source": [
        "coomer.st/"
      ],
      "target": ""
    },
    {
      "source": [
        "coomer.st/:source/user/:id"
      ],
      "target": "/:source/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Posts of hentai-tv from OnlyFans | Coomer - Powered by RSSHub",
      "errorAt": "2024-11-26T03:46:23.897Z",
      "errorMessage": "[GET] \"https://coomer.st/api/v1/artist/user/hentai-tv/posts\": 503 Backend fetch failed\n[GET] \"https://coomer.st/api/v1/artist/user/hentai-tv/posts\": 503 Backend fetch failed\n",
      "id": "74486459000853504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://coomer.su/onlyfans/user/hentai-tv",
      "title": "Posts of hentai-tv from OnlyFans | Coomer",
      "type": "feed",
      "url": "rsshub://coomer/artist/hentai-tv"
    },
    {
      "description": "Coomer Posts - Powered by RSSHub",
      "errorAt": "2026-08-04T12:38:46.523Z",
      "errorMessage": "[GET] \"https://coomer.st/api/v1/posts\": 503 Backend fetch failed\n",
      "id": "59850686115931136",
      "image": "https://coomer.st/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://coomer.st/posts",
      "title": "Coomer Posts",
      "type": "feed",
      "url": "rsshub://coomer/posts"
    }
  ]
}
```
