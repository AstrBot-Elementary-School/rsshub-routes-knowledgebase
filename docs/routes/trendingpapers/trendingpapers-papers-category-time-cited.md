# Trending Papers - Trending Papers on arXiv

## Coverage
`index-only`

## Route
- Namespace: `trendingpapers`
- Namespace Name: `Trending Papers`
- Route Path: `/trendingpapers/papers/:category?/:time?/:cited?`
- Route Name: `Trending Papers on arXiv`
- Example: `/trendingpapers/papers`
- URL: `trendingpapers.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `CookiePieWw`
- Source Location: `papers.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category of papers, can be found in URL. `All categories` by default.
- `time`: Time like `24 hours` to specify the duration of ranking, can be found in URL. `Since beginning` by default.
- `cited`: Cited or uncited papers, can be found in URL. `Cited and uncited papers` by default.


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
  "example": "/trendingpapers/papers",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 129,
  "location": "papers.ts",
  "maintainers": [
    "CookiePieWw"
  ],
  "name": "Trending Papers on arXiv",
  "parameters": {
    "category": "Category of papers, can be found in URL. `All categories` by default.",
    "cited": "Cited or uncited papers, can be found in URL. `Cited and uncited papers` by default.",
    "time": "Time like `24 hours` to specify the duration of ranking, can be found in URL. `Since beginning` by default."
  },
  "path": "/papers/:category?/:time?/:cited?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:101:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Trending Papers on arXiv.org | Computer Science - Computer Vision and Pattern Recognition | 7 days | Only cited papers | - Powered by RSSHub",
      "errorAt": "2025-07-03T16:14:02.595Z",
      "errorMessage": "[GET] \"https://trendingpapers.com/api/papers?p=1&o=pagerank_growth&pd=7 days&cc=Only cited papers&c=Computer Science - Computer Vision and Pattern Recognition\": <no response> fetch failed\n[GET] \"https://trendingpapers.com/api/papers?p=1&o=pagerank_growth&pd=7 days&cc=Only cited papers&c=Computer Science - Computer Vision and Pattern Recognition\": 522 <none>\n",
      "id": "98721121066834944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://trendingpapers.com/api/papers?p=1&o=pagerank_growth&pd=7%20days&cc=Only%20cited%20papers&c=Computer%20Science%20-%20Computer%20Vision%20and%20Pattern%20Recognition",
      "title": "Trending Papers on arXiv.org | Computer Science - Computer Vision and Pattern Recognition | 7 days | Only cited papers |",
      "type": "feed",
      "url": "rsshub://trendingpapers/papers/Computer%20Science%20-%20Computer%20Vision%20and%20Pattern%20Recognition/7%20days/Only%20cited%20papers"
    },
    {
      "description": "Trending Papers on arXiv.org | All categories | Since beginning | Cited and uncited papers | - Powered by RSSHub",
      "errorAt": "2025-07-03T16:12:00.755Z",
      "errorMessage": "[GET] \"https://trendingpapers.com/api/papers?p=1&o=pagerank_growth&pd=Since beginning&cc=Cited and uncited papers&c=All categories\": 522 <none>\n",
      "id": "54930355946094592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://trendingpapers.com/api/papers?p=1&o=pagerank_growth&pd=Since%20beginning&cc=Cited%20and%20uncited%20papers&c=All%20categories",
      "title": "Trending Papers on arXiv.org | All categories | Since beginning | Cited and uncited papers |",
      "type": "feed",
      "url": "rsshub://trendingpapers/papers"
    }
  ]
}
```
