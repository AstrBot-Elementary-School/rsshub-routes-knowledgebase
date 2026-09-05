# The Strait Times - News

## Coverage
`index-only`

## Route
- Namespace: `straitstimes`
- Namespace Name: `The Strait Times`
- Route Path: `/straitstimes/:category?/:section?`
- Route Name: `News`
- Example: `/straitstimes/singapore`
- URL: `straitstimes.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| Category              | `:category`               |   |
| --------------------- | ------------------------- | - |
| Singapore             | `singapore`               |   |
| Asia                  | `asia`                    |   |
| World                 | `world`                   |   |
| Opinion               | `opinion`                 |   |
| Life                  | `life`                    |   |
| Business              | `business`                |   |
| Jobs                  | `jobs`                    |   |
| Parenting & Education | `parenting-and-education` |   |
| Food                  | `food`                    |   |
| Tech                  | `tech`                    |   |
| Sport                 | `sport`                   |   |
| Podcasts              | `podcasts`                | , |

| Section     | `:section`    |
| ----------- | ------------- |
| Top Stories | `top-stories` |
| Latest      | `latest`      |

## Parameters
- `category`: Category, see below for more information
- `section`: Section, see below for more information


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `www.straitstimes.com/:category`
- `target`: `/:category`
### Rule 2
- `source`:
  - `www.straitstimes.com`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Category              | `:category`               |   |\n| --------------------- | ------------------------- | - |\n| Singapore             | `singapore`               |   |\n| Asia                  | `asia`                    |   |\n| World                 | `world`                   |   |\n| Opinion               | `opinion`                 |   |\n| Life                  | `life`                    |   |\n| Business              | `business`                |   |\n| Jobs                  | `jobs`                    |   |\n| Parenting & Education | `parenting-and-education` |   |\n| Food                  | `food`                    |   |\n| Tech                  | `tech`                    |   |\n| Sport                 | `sport`                   |   |\n| Podcasts              | `podcasts`                | , |\n\n| Section     | `:section`    |\n| ----------- | ------------- |\n| Top Stories | `top-stories` |\n| Latest      | `latest`      |",
  "example": "/straitstimes/singapore",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 66,
  "location": "index.tsx",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, see below for more information",
    "section": "Section, see below for more information"
  },
  "path": "/:category?/:section?",
  "radar": [
    {
      "source": [
        "www.straitstimes.com/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.straitstimes.com"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The Strait Times - SINGAPORE - Powered by RSSHub",
      "errorAt": "2025-10-30T15:54:24.353Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "76598839880708096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.straitstimes.com/singapore",
      "title": "The Strait Times - SINGAPORE",
      "type": "feed",
      "url": "rsshub://straitstimes"
    },
    {
      "description": "The Strait Times - WORLD - Powered by RSSHub",
      "errorAt": "2025-11-06T09:45:21.790Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "70061661043605504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.straitstimes.com/world",
      "title": "The Strait Times - WORLD",
      "type": "feed",
      "url": "rsshub://straitstimes/world"
    }
  ]
}
```
