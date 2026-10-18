# S&P Global - Ratings

## Coverage
`index-only`

## Route
- Namespace: `spglobal`
- Namespace Name: `S&P Global`
- Route Path: `/spglobal/ratings/:language?`
- Route Name: `Ratings`
- Example: `/spglobal/ratings/en`
- URL: `www.spglobal.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Cedaric`
- Source Location: `ratings.ts`
- Source Module: `_None_`

## Description
| language | Description |
| -------- | ----------- |
| zh       | 中文        |
| en       | English     |
| es       | Español     |
| pt       | Português   |
| jp       | 日本語      |
| ru       | Русский     |
| ar       | العربية     |

## Parameters
- `language`: {"description": "语言", "options": [{"label": "中文", "value": "zh"}, {"label": "English", "value": "en"}, {"label": "Español", "value": "es"}, {"label": "Português", "value": "pt"}, {"label": "日本語", "value": "jp"}, {"label": "Русский", "value": "ru"}, {"label": "العربية", "value": "ar"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.spglobal.com/ratings/:language`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| language | Description |\n| -------- | ----------- |\n| zh       | 中文        |\n| en       | English     |\n| es       | Español     |\n| pt       | Português   |\n| jp       | 日本語      |\n| ru       | Русский     |\n| ar       | العربية     |",
  "example": "/spglobal/ratings/en",
  "heat": 115,
  "location": "ratings.ts",
  "maintainers": [
    "Cedaric"
  ],
  "name": "Ratings",
  "parameters": {
    "language": {
      "description": "语言",
      "options": [
        {
          "label": "中文",
          "value": "zh"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Português",
          "value": "pt"
        },
        {
          "label": "日本語",
          "value": "jp"
        },
        {
          "label": "Русский",
          "value": "ru"
        },
        {
          "label": "العربية",
          "value": "ar"
        }
      ]
    }
  },
  "path": "/ratings/:language?",
  "radar": [
    {
      "source": [
        "www.spglobal.com/ratings/:language"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "S&P Global Ratings(zh) - Powered by RSSHub",
      "errorAt": "2026-10-17T13:02:38.282Z",
      "errorMessage": "[GET] \"https://www.spglobal.com/ratings/zh/\": 403 Forbidden\n",
      "id": "91850787540336640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.spglobal.com/ratings/zh/",
      "title": "S&P Global Ratings(zh)",
      "type": "feed",
      "url": "rsshub://spglobal/ratings/zh"
    },
    {
      "description": "S&P Global Ratings(en) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150939418810558464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.spglobal.com/ratings/en/",
      "title": "S&P Global Ratings(en)",
      "type": "feed",
      "url": "rsshub://spglobal/ratings"
    }
  ],
  "view": 5
}
```
