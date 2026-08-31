# MyFigureCollection - Activity

## Coverage
`index-only`

## Route
- Namespace: `myfigurecollection`
- Namespace Name: `MyFigureCollection`
- Route Path: `/myfigurecollection/activity/:category?/:language?/:latestAdditions?/:latestEdits?/:latestAlerts?/:latestPictures?`
- Route Name: `Activity`
- Example: `/myfigurecollection/activity`
- URL: `zh.myfigurecollection.net/browse`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `activity.tsx`
- Source Module: `_None_`

## Description
Category

| Figures | Goods | Media |
| ------- | ----- | ----- |
| 0       | 1     | 2     |

Language

| Id | Language   |
| -- | ---------- |
|    | en         |
| de | Deutsch    |
| es | Español    |
| fi | Suomeksi   |
| fr | Français   |
| it | Italiano   |
| ja | 日本語     |
| nl | Nederlands |
| no | Norsk      |
| pl | Polski     |
| pt | Português  |
| ru | Русский    |
| sv | Svenska    |
| zh | 中文       |

## Parameters
- `category`: Category, Figures by default
- `language`: Language, as above, `en` by default
- `latestAdditions`: Latest Additions, on as `1` by default, off as `0`
- `latestEdits`: Changes, on as `1` by default, off as `0`
- `latestAlerts`: Alerts, on as `1` by default, off as `0`
- `latestPictures`: Pictures, on as `1` by default, off as `0`


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
  - `zh.myfigurecollection.net/browse`
  - `zh.myfigurecollection.net/`
- `target`: `/:category?/:language?`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Category\n\n| Figures | Goods | Media |\n| ------- | ----- | ----- |\n| 0       | 1     | 2     |\n\nLanguage\n\n| Id | Language   |\n| -- | ---------- |\n|    | en         |\n| de | Deutsch    |\n| es | Español    |\n| fi | Suomeksi   |\n| fr | Français   |\n| it | Italiano   |\n| ja | 日本語     |\n| nl | Nederlands |\n| no | Norsk      |\n| pl | Polski     |\n| pt | Português  |\n| ru | Русский    |\n| sv | Svenska    |\n| zh | 中文       |",
  "example": "/myfigurecollection/activity",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "activity.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Activity",
  "parameters": {
    "category": "Category, Figures by default",
    "language": "Language, as above, `en` by default",
    "latestAdditions": "Latest Additions, on as `1` by default, off as `0`",
    "latestAlerts": "Alerts, on as `1` by default, off as `0`",
    "latestEdits": "Changes, on as `1` by default, off as `0`",
    "latestPictures": "Pictures, on as `1` by default, off as `0`"
  },
  "path": "/activity/:category?/:language?/:latestAdditions?/:latestEdits?/:latestAlerts?/:latestPictures?",
  "radar": [
    {
      "source": [
        "zh.myfigurecollection.net/browse",
        "zh.myfigurecollection.net/"
      ],
      "target": "/:category?/:language?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "zh.myfigurecollection.net/browse"
}
```
