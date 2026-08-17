# FC Bayern München - News

## Coverage
`index-only`

## Route
- Namespace: `fcbayern`
- Namespace Name: `FC Bayern München`
- Route Path: `/fcbayern/news/:language?`
- Route Name: `News`
- Example: `/fcbayern/news`
- URL: `fcbayern.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: {"default": "en", "description": "Language", "options": [{"label": "English", "value": "en"}, {"label": "Español", "value": "es"}, {"label": "Deutsch", "value": "de"}, {"label": "中文", "value": "zh"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fcbayern.com/:language/news`
  - `fcbayern.com/:language`
- `target`: `/news/:language`
### Rule 2
- `source`:
  - `www.fcbayern.cn/news`
  - `www.fcbayern.cn`
- `target`: `/news/zh`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/fcbayern/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "language": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Deutsch",
          "value": "de"
        },
        {
          "label": "中文",
          "value": "zh"
        }
      ]
    }
  },
  "path": "/news/:language?",
  "radar": [
    {
      "source": [
        "fcbayern.com/:language/news",
        "fcbayern.com/:language"
      ],
      "target": "/news/:language"
    },
    {
      "source": [
        "www.fcbayern.cn/news",
        "www.fcbayern.cn"
      ],
      "target": "/news/zh"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "fcbayern.com"
}
```
