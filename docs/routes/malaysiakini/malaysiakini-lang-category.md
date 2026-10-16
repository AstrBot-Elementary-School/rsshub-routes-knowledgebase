# Malaysiakini - News

## Coverage
`index-only`

## Route
- Namespace: `malaysiakini`
- Namespace Name: `Malaysiakini`
- Route Path: `/malaysiakini/:lang/:category?`
- Route Name: `News`
- Example: `/malaysiakini/en`
- URL: `malaysiakini.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Language | English | Bahasa Malaysia | 华文 |
| -------- | ------- | --------------- | ---- |
| `:lang`  | `en`    | `my`            | `zh` |

| Category         | `:category` |
| ---------------- | ----------- |
| News             | `news`      |
| Columns          | `columns`   |
| From Our Readers | `letters`   |

## Parameters
- `lang`: Language, see below
- `category`: Category, see below, news by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: [{"description": "Malaysiakini Email or Username", "name": "MALAYSIAKINI_EMAIL", "optional": true}, {"description": "Malaysiakini Password", "name": "MALAYSIAKINI_PASSWORD", "optional": true}, {"description": "To obtain the refresh token, log into Malaysiakini and look for the cookie `nl____refreshToken` within document.cookie in the browser console. The token is the value of the cookie.", "name": "MALAYSIAKINI_REFRESHTOKEN", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `malaysiakini.com/`
- `target`: `/en`
### Rule 2
- `source`:
  - `malaysiakini.com/:lang`
- `target`: `/:lang`
### Rule 3
- `source`:
  - `www.malaysiakini.com/:lang/latest/:category`
- `target`: `/:lang/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Language | English | Bahasa Malaysia | 华文 |\n| -------- | ------- | --------------- | ---- |\n| `:lang`  | `en`    | `my`            | `zh` |\n\n| Category         | `:category` |\n| ---------------- | ----------- |\n| News             | `news`      |\n| Columns          | `columns`   |\n| From Our Readers | `letters`   |",
  "example": "/malaysiakini/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Malaysiakini Email or Username",
        "name": "MALAYSIAKINI_EMAIL",
        "optional": true
      },
      {
        "description": "Malaysiakini Password",
        "name": "MALAYSIAKINI_PASSWORD",
        "optional": true
      },
      {
        "description": "To obtain the refresh token, log into Malaysiakini and look for the cookie `nl____refreshToken` within document.cookie in the browser console. The token is the value of the cookie.",
        "name": "MALAYSIAKINI_REFRESHTOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, see below, news by default",
    "lang": "Language, see below"
  },
  "path": "/:lang/:category?",
  "radar": [
    {
      "source": [
        "malaysiakini.com/"
      ],
      "target": "/en"
    },
    {
      "source": [
        "malaysiakini.com/:lang"
      ],
      "target": "/:lang"
    },
    {
      "source": [
        "www.malaysiakini.com/:lang/latest/:category"
      ],
      "target": "/:lang/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Latest articles from News - Powered by RSSHub",
      "errorAt": "2026-10-15T11:47:38.946Z",
      "errorMessage": "Cannot find the public article content on https://www.malaysiakini.com/news/887193-we-have-done-everything-we-can-anwar-defends-haze-response.\n",
      "id": "61840955600323584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.malaysiakini.com/en/latest/news",
      "title": "News - Malaysiakini",
      "type": "feed",
      "url": "rsshub://malaysiakini/en"
    },
    {
      "description": "Latest articles from 新聞 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69685104073634816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.malaysiakini.com/zh/latest/news",
      "title": "新聞 - Malaysiakini",
      "type": "feed",
      "url": "rsshub://malaysiakini/zh/news"
    }
  ]
}
```
