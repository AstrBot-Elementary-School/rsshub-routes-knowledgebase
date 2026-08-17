# Cool Papers - Topic

## Coverage
`index-only`

## Route
- Namespace: `papers`
- Namespace Name: `Cool Papers`
- Route Path: `/papers/query/:keyword{.+}?`
- Route Name: `Topic`
- Example: `/papers/query/Detection`
- URL: `papers.cool`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Muyun99`
- Source Location: `query.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscibe to [arXiv Paper queryed by Detection](https://papers.cool/arxiv/search?highlight=1\&query=Detection), where the URL is `https://papers.cool/arxiv/search?highlight=1&query=Detection`, extract the part `https://papers.cool/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/papers/query/Detection`](https://rsshub.app/papers/query/Detection).
:::

| Category                            | id                 |
| ----------------------------------- | ------------------ |
| arXiv Paper queryed by Detection    | query/Detection    |
| arXiv Paper queryed by Segmentation | query/Segmentation |

## Parameters
- `keyword`: Keyword to search for papers, e.g., Detection, Segmentation, etc.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `title`: `arXiv Paper queryed by Keyword`
- `source`:
  - `papers.cool/arxiv/search?highlight=1&query=*&sort=0`
- `target`: `/papers/query/:keyword`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: tip\nIf you subscibe to [arXiv Paper queryed by Detection](https://papers.cool/arxiv/search?highlight=1\\&query=Detection), where the URL is `https://papers.cool/arxiv/search?highlight=1&query=Detection`, extract the part `https://papers.cool/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/papers/query/Detection`](https://rsshub.app/papers/query/Detection).\n:::\n\n| Category                            | id                 |\n| ----------------------------------- | ------------------ |\n| arXiv Paper queryed by Detection    | query/Detection    |\n| arXiv Paper queryed by Segmentation | query/Segmentation |",
  "example": "/papers/query/Detection",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": true
  },
  "heat": 22,
  "location": "query.ts",
  "maintainers": [
    "Muyun99"
  ],
  "name": "Topic",
  "parameters": {
    "keyword": "Keyword to search for papers, e.g., Detection, Segmentation, etc."
  },
  "path": "/query/:keyword{.+}?",
  "radar": [
    {
      "source": [
        "papers.cool/arxiv/search?highlight=1&query=*&sort=0"
      ],
      "target": "/papers/query/:keyword",
      "title": "arXiv Paper queryed by Keyword"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "llms for scientific discovery - Powered by RSSHub",
      "errorAt": "2026-08-15T16:43:24.350Z",
      "errorMessage": "Failed to fetch\n",
      "id": "191737387979350016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://papers.cool/arxiv/search?highlight=1&query=LLMs%20for%20Scientific%20Discovery&sort=0",
      "title": "llms for scientific discovery",
      "type": "feed",
      "url": "rsshub://papers/query/LLMs%20for%20Scientific%20Discovery"
    },
    {
      "description": "query detection - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "199876342948952064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://papers.cool/arxiv/search?highlight=1&query=query/Detection&sort=0",
      "title": "query detection",
      "type": "feed",
      "url": "rsshub://papers/query"
    }
  ],
  "url": "papers.cool"
}
```
