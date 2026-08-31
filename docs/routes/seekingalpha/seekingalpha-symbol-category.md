# Seeking Alpha - Summary

## Coverage
`index-only`

## Route
- Namespace: `seekingalpha`
- Namespace Name: `Seeking Alpha`
- Route Path: `/seekingalpha/:symbol/:category?`
- Route Name: `Summary`
- Example: `/seekingalpha/TSM/transcripts`
- URL: `seekingalpha.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| Analysis | News | Transcripts | Press Releases | Related Analysis |
| -------- | ---- | ----------- | -------------- | ---------------- |
| analysis | news | transcripts | press-releases | related-analysis |

## Parameters
- `symbol`: Stock symbol
- `category`: Category, see below, `news` by default


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `seekingalpha.com/symbol/:symbol/:category`
  - `seekingalpha.com/symbol/:symbol/earnings/:category`
- `target`: `/:symbol/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| Analysis | News | Transcripts | Press Releases | Related Analysis |\n| -------- | ---- | ----------- | -------------- | ---------------- |\n| analysis | news | transcripts | press-releases | related-analysis |",
  "example": "/seekingalpha/TSM/transcripts",
  "features": {
    "antiCrawler": true
  },
  "heat": 8,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Summary",
  "parameters": {
    "category": "Category, see below, `news` by default",
    "symbol": "Stock symbol"
  },
  "path": "/:symbol/:category?",
  "radar": [
    {
      "source": [
        "seekingalpha.com/symbol/:symbol/:category",
        "seekingalpha.com/symbol/:symbol/earnings/:category"
      ],
      "target": "/:symbol/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "All earnings call transcripts on Taiwan Semiconductor Manufacturing Company Limited (TSM) stock. Read or listen to the conference call. Download the investor presentation - earnings call slides. - Powered by RSSHub",
      "errorAt": "2025-06-12T21:58:34.659Z",
      "errorMessage": "[GET] \"https://seekingalpha.com/api/v3/symbols/TSM/transcripts?filter%5Bsince%5D=0&filter%5Buntil%5D=0&id=tsm&include=author,primaryTickers,secondaryTickers,sentiments&page%5Bsize%5D=20&page%5Bnumber%5D=1\": 403 Forbidden\n",
      "id": "88818733465958400",
      "image": "https://seekingalpha.com/samw/static/images/favicon.svg",
      "ownerUserId": null,
      "siteUrl": "https://seekingalpha.com/symbol/TSM/earnings/transcripts",
      "title": "Taiwan Semiconductor Manufacturing Company Limited (TSM) Earnings Transcripts",
      "type": "feed",
      "url": "rsshub://seekingalpha/TSM/transcripts"
    }
  ]
}
```
