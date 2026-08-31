# Telecompaper - News

## Coverage
`index-only`

## Route
- Namespace: `telecompaper`
- Namespace Name: `Telecompaper`
- Route Path: `/telecompaper/news/:caty/:year?/:country?/:type?`
- Route Name: `News`
- Example: `/telecompaper/news/mobile/2020/China/News`
- URL: `telecompaper.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Category

| WIRELESS | BROADBAND | VIDEO     | GENERAL | IT | INDUSTRY RESOURCES |
| -------- | --------- | --------- | ------- | -- | ------------------ |
| mobile   | internet  | boardcast | general | it | industry-resources |

::: tip
If `country` or `type` includes empty space, use `-` instead. For example, `United States` needs to be replaced with `United-States`, `White paper` needs to be replaced with `White-paper`

Filters in [INDUSTRY RESOURCES](https://www.telecompaper.com/industry-resources) only provides `Content Type` which corresponds to `type`. `year` and `country` are not supported.
:::

## Parameters
- `caty`: Category, see table below
- `year`: Year. The year in respective category page filter, `all` for unlimited year, empty by default
- `country`: Country or continent, `all` for unlimited country or continent, empty by default
- `type`: Type, can be found in the `Types` filter, `all` for unlimited type, unlimited by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Category\n\n| WIRELESS | BROADBAND | VIDEO     | GENERAL | IT | INDUSTRY RESOURCES |\n| -------- | --------- | --------- | ------- | -- | ------------------ |\n| mobile   | internet  | boardcast | general | it | industry-resources |\n\n::: tip\nIf `country` or `type` includes empty space, use `-` instead. For example, `United States` needs to be replaced with `United-States`, `White paper` needs to be replaced with `White-paper`\n\nFilters in [INDUSTRY RESOURCES](https://www.telecompaper.com/industry-resources) only provides `Content Type` which corresponds to `type`. `year` and `country` are not supported.\n:::",
  "example": "/telecompaper/news/mobile/2020/China/News",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "caty": "Category, see table below",
    "country": "Country or continent, `all` for unlimited country or continent, empty by default",
    "type": "Type, can be found in the `Types` filter, `all` for unlimited type, unlimited by default",
    "year": "Year. The year in respective category page filter, `all` for unlimited year, empty by default"
  },
  "path": "/news/:caty/:year?/:country?/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
