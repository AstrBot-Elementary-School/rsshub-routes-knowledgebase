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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "News & Views That Matter - Powered by RSSHub",
      "errorAt": "2026-09-07T10:16:30.919Z",
      "errorMessage": "[GET] \"https://www.malaysiakini.com/api/content/https://www.malaysiakini.com/news/885417-%E4%B8%A5%E7%AB%AF%E6%97%A0%E5%A4%A7%E8%87%A3%E5%8A%9D%E5%91%8A%E4%B8%8B%E7%82%92%E4%BA%BA%E8%BF%9D%E5%AE%AA%E6%A3%AE%E9%80%BC%E5%AE%AB%E6%B4%BE%E8%AE%A4%E5%AE%9A%E6%8C%87%E4%BB%A4%E6%97%A0%E6%95%88\": 404 Not Found\n",
      "id": "69685104073634816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.malaysiakini.com/",
      "title": "Malaysiakini",
      "type": "feed",
      "url": "rsshub://malaysiakini/zh/news"
    },
    {
      "description": "News & Views That Matter - Powered by RSSHub",
      "errorAt": "2026-09-07T09:32:19.566Z",
      "errorMessage": "[GET] \"https://www.malaysiakini.com/api/content/https://www.malaysiakini.com/news/885414-tuanku-muhriz-revokes-exco-appointments-but-reading-of-constitution-disputed\": 404 Not Found\n",
      "id": "61840955600323584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.malaysiakini.com/",
      "title": "Malaysiakini",
      "type": "feed",
      "url": "rsshub://malaysiakini/en"
    }
  ]
}
```
