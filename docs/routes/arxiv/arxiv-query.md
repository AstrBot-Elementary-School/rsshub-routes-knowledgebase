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
  "heat": 2,
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
    "message": "AssertionError: expected 400791651969 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "arXiv (search_query=cat:cs.AI&sortBy=submittedDate) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "250564935356404745",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://export.arxiv.org/api/query?search_query=cat:cs.AI&sortBy=submittedDate",
      "title": "arXiv (search_query=cat:cs.AI&sortBy=submittedDate)",
      "type": "feed",
      "url": "rsshub://arxiv/search_query=cat:cs.AI&sortBy=submittedDate"
    },
    {
      "description": "arXiv (search_query=cat:cs.AI AND (all:evolution OR all:evolutionary OR all:\"artificial evolution\" OR all:\"AI evolution\" OR all:\"self-improvement\" OR all:\"recursive self-improvement\")&start=0&max_results=100&sortBy=relevance&sortOrder=descending) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1308088789733605376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://export.arxiv.org/api/query?search_query=cat:cs.AI%20AND%20(all:evolution%20OR%20all:evolutionary%20OR%20all:%22artificial%20evolution%22%20OR%20all:%22AI%20evolution%22%20OR%20all:%22self-improvement%22%20OR%20all:%22recursive%20self-improvement%22)&start=0&max_results=100&sortBy=relevance&sortOrder=descending",
      "title": "arXiv (search_query=cat:cs.AI AND (all:evolution OR all:evolutionary OR all:\"artificial evolution\" OR all:\"AI evolution\" OR all:\"self-improvement\" OR all:\"recursive self-improvement\")&start=0&max_results=100&sortBy=relevance&sortOrder=descending)",
      "type": "feed",
      "url": "rsshub://arxiv/search_query%3Dcat%3Acs.AI%20AND%20(all%3Aevolution%20OR%20all%3Aevolutionary%20OR%20all%3A%22artificial%20evolution%22%20OR%20all%3A%22AI%20evolution%22%20OR%20all%3A%22self-improvement%22%20OR%20all%3A%22recursive%20self-improvement%22)%26start%3D0%26max_results%3D100%26sortBy%3Drelevance%26sortOrder%3Ddescending"
    }
  ]
}
```
