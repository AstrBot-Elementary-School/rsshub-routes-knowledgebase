# Macau Independent Commission Against Corruption 澳门廉政公署 - Latest News

## Coverage
`index-only`

## Route
- Namespace: `ccac`
- Namespace Name: `Macau Independent Commission Against Corruption 澳门廉政公署`
- Route Path: `/ccac/news/:type/:lang?`
- Route Name: `Latest News`
- Example: `/ccac/news/all`
- URL: `ccac.org.mo`
- Language: `_None_`
- Categories: `government`
- Maintainers: `linbuxiao`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Category

| All | Detected Cases | Investigation Reports or Recommendations | Annual Reports | CCAC's Updates |
| --- | -------------- | ---------------------------------------- | -------------- | -------------- |
| all | case           | Persuasion                               | AnnualReport   | PCANews        |

## Parameters
- `type`: Category
- `lang`: Language, default to `sc`. Supprot `en`(English), `sc`(Simplified Chinese), `tc`(Traditional Chinese) and `pt`(Portuguese)


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "government"
  ],
  "description": "Category\n\n| All | Detected Cases | Investigation Reports or Recommendations | Annual Reports | CCAC's Updates |\n| --- | -------------- | ---------------------------------------- | -------------- | -------------- |\n| all | case           | Persuasion                               | AnnualReport   | PCANews        |",
  "example": "/ccac/news/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "linbuxiao"
  ],
  "name": "Latest News",
  "parameters": {
    "lang": "Language, default to `sc`. Supprot `en`(English), `sc`(Simplified Chinese), `tc`(Traditional Chinese) and `pt`(Portuguese)",
    "type": "Category"
  },
  "path": "/news/:type/:lang?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
