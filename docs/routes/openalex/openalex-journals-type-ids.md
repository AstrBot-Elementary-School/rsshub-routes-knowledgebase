# OpenAlex - Works

## Coverage
`index-only`

## Route
- Namespace: `openalex`
- Namespace Name: `OpenAlex`
- Route Path: `/openalex/:journals/:type?/:ids?`
- Route Name: `Works`
- Example: `/openalex/s64187185/subfield/2604`
- URL: `openalex.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `emdoe`
- Source Location: `works.ts`
- Source Module: `_None_`

## Description
Get recent scientific publications from OpenAlex filtered by journal and optionally by topic classification (last 2 weeks).

Examples:

- /openalex/s64187185 - All works from a journal (no topic filter)
- /openalex/s64187185/subfield/2604 - Filter by subfield
- /openalex/s64187185|s123456/topic/T10001|T10002 - Filter by topic with multiple journals
- /openalex/s64187185/field/19 - Filter by field
- /openalex/s64187185/domain/1 - Filter by domain

## Parameters
- `journals`: Pipe-separated journal source IDs (e.g., s64187185|s123456789)
- `type`: Optional filter type: subfield, topic, field, or domain
- `ids`: Optional pipe-separated filter IDs matching the type (e.g., 2604|2605 for subfields)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `openalex.org/works`
- `target`: `/:journals/:type?/:ids?`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Get recent scientific publications from OpenAlex filtered by journal and optionally by topic classification (last 2 weeks).\n\nExamples:\n\n- /openalex/s64187185 - All works from a journal (no topic filter)\n- /openalex/s64187185/subfield/2604 - Filter by subfield\n- /openalex/s64187185|s123456/topic/T10001|T10002 - Filter by topic with multiple journals\n- /openalex/s64187185/field/19 - Filter by field\n- /openalex/s64187185/domain/1 - Filter by domain",
  "example": "/openalex/s64187185/subfield/2604",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "works.ts",
  "maintainers": [
    "emdoe"
  ],
  "name": "Works",
  "parameters": {
    "ids": "Optional pipe-separated filter IDs matching the type (e.g., 2604|2605 for subfields)",
    "journals": "Pipe-separated journal source IDs (e.g., s64187185|s123456789)",
    "type": "Optional filter type: subfield, topic, field, or domain"
  },
  "path": "/:journals/:type?/:ids?",
  "radar": [
    {
      "source": [
        "openalex.org/works"
      ],
      "target": "/:journals/:type?/:ids?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "openalex.org"
}
```
