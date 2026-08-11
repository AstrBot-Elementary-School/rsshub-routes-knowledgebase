# PubMed - Trending articles

## Coverage
`index-only`

## Route
- Namespace: `pubmed`
- Namespace Name: `PubMed`
- Route Path: `/pubmed/trending/:filters?`
- Route Name: `Trending articles`
- Example: `/pubmed/trending`
- URL: `pubmed.ncbi.nlm.nih.gov`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, nczitzk`
- Source Location: `trending.tsx`
- Source Module: `_None_`

## Description
::: tip
For the parameter **filter**, the `filter` parameter in the URL should be split into a string by `,`, here is an example.

In `https://pubmed.ncbi.nlm.nih.gov/trending/?filter=simsearch1.fha&filter=pubt.clinicaltrial&filter=pubt.randomizedcontrolledtrial`, the filter parameters are `simsearch1.fha`, `pubt.clinicaltrial`, and `pubt.randomizedcontrolledtrial`. Therefore, the filter corresponding to the route should be filled with `simsearch1.fha,pubt.clinicaltrial,pubt.randomizedcontrolledtrial`, and the route is [`/pubmed/trending/simsearch1.fha,pubt.clinicaltrial,pubt.randomizedcontrolledtrial`](https://rsshub.app/pubmed/trending/simsearch1.fha,pubt.clinicaltrial,pubt.randomizedcontrolledtrial)
:::

## Parameters
- `filters`: Filters, can be found in URL


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: tip\nFor the parameter **filter**, the `filter` parameter in the URL should be split into a string by `,`, here is an example.\n\nIn `https://pubmed.ncbi.nlm.nih.gov/trending/?filter=simsearch1.fha&filter=pubt.clinicaltrial&filter=pubt.randomizedcontrolledtrial`, the filter parameters are `simsearch1.fha`, `pubt.clinicaltrial`, and `pubt.randomizedcontrolledtrial`. Therefore, the filter corresponding to the route should be filled with `simsearch1.fha,pubt.clinicaltrial,pubt.randomizedcontrolledtrial`, and the route is [`/pubmed/trending/simsearch1.fha,pubt.clinicaltrial,pubt.randomizedcontrolledtrial`](https://rsshub.app/pubmed/trending/simsearch1.fha,pubt.clinicaltrial,pubt.randomizedcontrolledtrial)\n:::",
  "example": "/pubmed/trending",
  "heat": 5,
  "location": "trending.tsx",
  "maintainers": [
    "y9c",
    "nczitzk"
  ],
  "name": "Trending articles",
  "parameters": {
    "filters": "Filters, can be found in URL"
  },
  "path": "/trending/:filters?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 487041937939 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Trending page - PubMed - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84477021375684608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pubmed.ncbi.nlm.nih.gov/trending",
      "title": "Trending page - PubMed",
      "type": "feed",
      "url": "rsshub://pubmed/trending"
    }
  ]
}
```
