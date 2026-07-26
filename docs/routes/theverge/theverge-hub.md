# The Verge - Category

## Coverage
`index-only`

## Route
- Namespace: `theverge`
- Namespace Name: `The Verge`
- Route Path: `/theverge/:hub?`
- Route Name: `Category`
- Example: `/theverge`
- URL: `theverge.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW, vbali`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Hub         | Hub name            |
| ----------- | ------------------- |
|             | All Posts           |
| android     | Android             |
| apple       | Apple               |
| apps        | Apps & Software     |
| blackberry  | BlackBerry          |
| culture     | Culture             |
| gaming      | Gaming              |
| hd          | HD & Home           |
| microsoft   | Microsoft           |
| photography | Photography & Video |
| policy      | Policy & Law        |
| web         | Web & Social        |

Provides a better reading experience (full text articles) over the official one.

## Parameters
- `hub`: Hub, see below, All Posts by default


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
  - `theverge.com/:hub`
  - `theverge.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Hub         | Hub name            |\n| ----------- | ------------------- |\n|             | All Posts           |\n| android     | Android             |\n| apple       | Apple               |\n| apps        | Apps & Software     |\n| blackberry  | BlackBerry          |\n| culture     | Culture             |\n| gaming      | Gaming              |\n| hd          | HD & Home           |\n| microsoft   | Microsoft           |\n| photography | Photography & Video |\n| policy      | Policy & Law        |\n| web         | Web & Social        |\n\nProvides a better reading experience (full text articles) over the official one.",
  "example": "/theverge",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 301,
  "location": "index.ts",
  "maintainers": [
    "HenryQW",
    "vbali"
  ],
  "name": "Category",
  "parameters": {
    "hub": "Hub, see below, All Posts by default"
  },
  "path": "/:hub?",
  "radar": [
    {
      "source": [
        "theverge.com/:hub",
        "theverge.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The Verge - Powered by RSSHub",
      "errorAt": "2025-09-24T13:58:17.013Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "56165613279845376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theverge.com/",
      "title": "The Verge",
      "type": "feed",
      "url": "rsshub://theverge"
    },
    {
      "description": "Apps | The Verge - Powered by RSSHub",
      "errorAt": "2025-09-24T18:37:54.873Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "52982633246101506",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theverge.com/apps",
      "title": "Apps | The Verge",
      "type": "feed",
      "url": "rsshub://theverge/apps"
    }
  ]
}
```
