# arXiv - Search Keyword

## Coverage
`index-only`

## Route
- Namespace: `arxiv`
- Namespace Name: `arXiv`
- Route Path: `/arxiv/:query`
- Route Name: `Search Keyword`
- Example: `/arxiv/search_query=all:electron&start=0&max_results=10`
- URL: `arxiv.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `query.ts`
- Source Module: `_None_`

## Description
See [arXiv API User Manual](https://arxiv.org/help/api/user-manual) to find out all query statements.

Fill in parameter `query` with content after `https://export.arxiv.org/api/query?`.

## Parameters
- `query`: query statement


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "See [arXiv API User Manual](https://arxiv.org/help/api/user-manual) to find out all query statements.\n\nFill in parameter `query` with content after `https://export.arxiv.org/api/query?`.",
  "example": "/arxiv/search_query=all:electron&start=0&max_results=10",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "query.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Search Keyword",
  "parameters": {
    "query": "query statement"
  },
  "path": "/:query",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 397765673859 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
