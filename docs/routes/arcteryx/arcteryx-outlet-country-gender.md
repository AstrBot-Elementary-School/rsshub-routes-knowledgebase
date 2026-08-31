# Arcteryx - Outlet

## Coverage
`index-only`

## Route
- Namespace: `arcteryx`
- Namespace Name: `Arcteryx`
- Route Path: `/arcteryx/outlet/:country/:gender`
- Route Name: `Outlet`
- Example: `/arcteryx/outlet/us/mens`
- URL: `arcteryx.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `IvanWng97`
- Source Location: `outlet.ts`
- Source Module: `_None_`

## Description
Country

| United States | Canada | United Kingdom |
| ------------- | ------ | -------------- |
| us            | ca     | gb             |

gender

| male | female |
| ---- | ------ |
| mens | womens |

::: tip
Parameter `country` can be found within the url of `Arcteryx` website.
:::

## Parameters
- `country`: country
- `gender`: gender


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `outlet.arcteryx.com/:country/en/c/:gender`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Country\n\n| United States | Canada | United Kingdom |\n| ------------- | ------ | -------------- |\n| us            | ca     | gb             |\n\ngender\n\n| male | female |\n| ---- | ------ |\n| mens | womens |\n\n::: tip\nParameter `country` can be found within the url of `Arcteryx` website.\n:::",
  "example": "/arcteryx/outlet/us/mens",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "outlet.ts",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Outlet",
  "parameters": {
    "country": "country",
    "gender": "gender"
  },
  "path": "/outlet/:country/:gender",
  "radar": [
    {
      "source": [
        "outlet.arcteryx.com/:country/en/c/:gender"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
