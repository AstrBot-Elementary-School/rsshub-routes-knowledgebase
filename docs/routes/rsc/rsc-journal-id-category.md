# Royal Society of Chemistry - Journal

## Coverage
`index-only`

## Route
- Namespace: `rsc`
- Namespace Name: `Royal Society of Chemistry`
- Route Path: `/rsc/journal/:id/:category?`
- Route Name: `Journal`
- Example: `/rsc/journal/ta`
- URL: `pubs.rsc.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.tsx`
- Source Module: `_None_`

## Description
::: tip
All journals at [Current journals](https://pubs.rsc.org/en/journals)
:::

| All Recent Articles | Advance Articles |
| ------------------- | ---------------- |
| allrecentarticles   | advancearticles  |

## Parameters
- `id`: Journal id, can be found in URL
- `category`: Category, see below, All Recent Articles by default


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
  "description": "::: tip\nAll journals at [Current journals](https://pubs.rsc.org/en/journals)\n:::\n\n| All Recent Articles | Advance Articles |\n| ------------------- | ---------------- |\n| allrecentarticles   | advancearticles  |",
  "example": "/rsc/journal/ta",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "journal.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Journal",
  "parameters": {
    "category": "Category, see below, All Recent Articles by default",
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Journal of Materials Chemistry A - Powered by RSSHub",
      "errorAt": "2026-06-30T15:27:29.359Z",
      "errorMessage": "[POST] \"https://pubs.rsc.org/en/journals/getrecentarticles\": 403 Forbidden\n[POST] \"https://pubs.rsc.org/en/journals/getrecentarticles\": 403 Forbidden\n",
      "id": "175094017782230016",
      "image": "https://pubs.rsc.org/en/Image/Get?imageInfo.ImageType=CoverIssue&imageInfo.ImageIdentifier.SerCode=ta&imageInfo.ImageIdentifier.IssueId=TA014037&imageInfo.ImageIdentifier.Year=2026",
      "ownerUserId": null,
      "siteUrl": "https://pubs.rsc.org/en/journals/journalissues/ta#!recentarticles",
      "title": "Journal of Materials Chemistry A",
      "type": "feed",
      "url": "rsshub://rsc/journal/ta"
    },
    {
      "description": "Energy & Environmental Science - Powered by RSSHub",
      "errorAt": "2026-06-30T13:22:56.537Z",
      "errorMessage": "[POST] \"https://pubs.rsc.org/en/journals/getrecentarticles\": 403 Forbidden\n[POST] \"https://pubs.rsc.org/en/journals/getrecentarticles\": 403 Forbidden\n",
      "id": "159483253180956672",
      "image": "https://pubs.rsc.org/en/Image/Get?imageInfo.ImageType=CoverIssue&imageInfo.ImageIdentifier.SerCode=ee&imageInfo.ImageIdentifier.IssueId=EE019012&imageInfo.ImageIdentifier.Year=2026",
      "ownerUserId": null,
      "siteUrl": "https://pubs.rsc.org/en/journals/journalissues/ee#!recentarticles",
      "title": "Energy & Environmental Science",
      "type": "feed",
      "url": "rsshub://rsc/journal/ee"
    }
  ]
}
```
