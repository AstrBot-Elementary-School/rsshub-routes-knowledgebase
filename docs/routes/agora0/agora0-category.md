# AG⓪RA - 零博客

## Coverage
`index-only`

## Route
- Namespace: `agora0`
- Namespace Name: `AG⓪RA`
- Route Path: `/agora0/:category?`
- Route Name: `零博客`
- Example: `/agora0/initium`
- URL: `agorahub.github.io`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| muitinⒾ | aidemnⒾ | srettaⓂ | qⓅ | sucoⓋ |
| ------- | ------- | ------- | -- | ----- |
| initium | inmedia | matters | pq | vocus |

## Parameters
- `category`: 分类，见下表，默认为 initium，即端传媒


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
  - `agora0.gitlab.io/blog/:category`
  - `agora0.gitlab.io/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| muitinⒾ | aidemnⒾ | srettaⓂ | qⓅ | sucoⓋ |\n| ------- | ------- | ------- | -- | ----- |\n| initium | inmedia | matters | pq | vocus |",
  "example": "/agora0/initium",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "零博客",
  "parameters": {
    "category": "分类，见下表，默认为 initium，即端传媒"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "agora0.gitlab.io/blog/:category",
        "agora0.gitlab.io/"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "muitinⒾ | 零博客 - Powered by RSSHub",
      "errorAt": "2024-12-17T17:08:27.527Z",
      "errorMessage": "[GET] \"https://agora0.gitlab.io/blog/initium\": 403 Forbidden\n",
      "id": "52721325092269085",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://agora0.gitlab.io/blog/initium",
      "title": "muitinⒾ | 零博客",
      "type": "feed",
      "url": "rsshub://agora0/initium"
    },
    {
      "description": "srettaⓂ | 零博客 - Powered by RSSHub",
      "errorAt": "2024-12-17T18:31:45.795Z",
      "errorMessage": "[GET] \"https://agora0.gitlab.io/blog/matters\": 403 Forbidden\n",
      "id": "52721325092269086",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://agora0.gitlab.io/blog/matters",
      "title": "srettaⓂ | 零博客",
      "type": "feed",
      "url": "rsshub://agora0/matters"
    }
  ]
}
```
