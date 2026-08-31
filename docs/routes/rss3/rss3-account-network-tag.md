# RSS3 - Account Activities

## Coverage
`index-only`

## Route
- Namespace: `rss3`
- Namespace Name: `RSS3`
- Route Path: `/rss3/:account/:network?/:tag?`
- Route Name: `Account Activities`
- Example: `/rss3/vitalik.eth`
- URL: `docs.rss3.io/api-reference#tag/decentralized/GET/decentralized/%7Baccount%7D`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Retrieve the activities associated with a specified account in the decentralized system.

## Parameters
- `account`: {"description": "Retrieve activities from the specified account. This account is a unique identifier within the decentralized system."}
- `network`: {"default": "all", "description": "Retrieve activities from the specified network.", "options": [{"label": "All", "value": "all"}, {"label": "Arbitrum", "value": "arbitrum"}, {"label": "Arweave", "value": "arweave"}, {"label": "Avax", "value": "avax"}, {"label": "Base", "value": "base"}, {"label": "Binance Smart Chain", "value": "binance-smart-chain"}, {"label": "Crossbell", "value": "crossbell"}, {"label": "Ethereum", "value": "ethereum"}, {"label": "Farcaster", "value": "farcaster"}, {"label": "Gnosis", "value": "gnosis"}, {"label": "Linea", "value": "linea"}, {"label": "Optimism", "value": "optimism"}, {"label": "Polygon", "value": "polygon"}, {"label": "VSL", "value": "vsl"}]}
- `tag`: {"default": "all", "description": "Retrieve activities from the specified tag.", "options": [{"label": "All", "value": "all"}, {"label": "collectible", "value": "collectible"}, {"label": "exchange", "value": "exchange"}, {"label": "metaverse", "value": "metaverse"}, {"label": "rss", "value": "rss"}, {"label": "social", "value": "social"}, {"label": "transaction", "value": "transaction"}, {"label": "unknown", "value": "unknown"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Retrieve the activities associated with a specified account in the decentralized system.",
  "example": "/rss3/vitalik.eth",
  "heat": 133,
  "location": "index.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "name": "Account Activities",
  "parameters": {
    "account": {
      "description": "Retrieve activities from the specified account. This account is a unique identifier within the decentralized system."
    },
    "network": {
      "default": "all",
      "description": "Retrieve activities from the specified network.",
      "options": [
        {
          "label": "All",
          "value": "all"
        },
        {
          "label": "Arbitrum",
          "value": "arbitrum"
        },
        {
          "label": "Arweave",
          "value": "arweave"
        },
        {
          "label": "Avax",
          "value": "avax"
        },
        {
          "label": "Base",
          "value": "base"
        },
        {
          "label": "Binance Smart Chain",
          "value": "binance-smart-chain"
        },
        {
          "label": "Crossbell",
          "value": "crossbell"
        },
        {
          "label": "Ethereum",
          "value": "ethereum"
        },
        {
          "label": "Farcaster",
          "value": "farcaster"
        },
        {
          "label": "Gnosis",
          "value": "gnosis"
        },
        {
          "label": "Linea",
          "value": "linea"
        },
        {
          "label": "Optimism",
          "value": "optimism"
        },
        {
          "label": "Polygon",
          "value": "polygon"
        },
        {
          "label": "VSL",
          "value": "vsl"
        }
      ]
    },
    "tag": {
      "default": "all",
      "description": "Retrieve activities from the specified tag.",
      "options": [
        {
          "label": "All",
          "value": "all"
        },
        {
          "label": "collectible",
          "value": "collectible"
        },
        {
          "label": "exchange",
          "value": "exchange"
        },
        {
          "label": "metaverse",
          "value": "metaverse"
        },
        {
          "label": "rss",
          "value": "rss"
        },
        {
          "label": "social",
          "value": "social"
        },
        {
          "label": "transaction",
          "value": "transaction"
        },
        {
          "label": "unknown",
          "value": "unknown"
        }
      ]
    }
  },
  "path": "/:account/:network?/:tag?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "vitalik.eth activities - Powered by RSSHub",
      "errorAt": "2025-07-28T19:05:53.202Z",
      "errorMessage": "Cannot find module '/app/node_modules/.pnpm/@rss3+api-core@0.0.25/node_modules/@rss3/api-core/dist/types/component-aliases' imported from /app/node_modules/.pnpm/@rss3+api-core@0.0.25/node_modules/@rss3/api-core/dist/index.js\nCannot find module '/app/node_modules/.pnpm/@rss3+api-core@0.0.25/node_modules/@rss3/api-core/dist/types/component-aliases' imported from /app/node_modules/.pnpm/@rss3+api-core@0.0.25/node_modules/@rss3/api-core/dist/index.js\n",
      "id": "41384138793719808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rss3.io/",
      "title": "vitalik.eth activities",
      "type": "feed",
      "url": "rsshub://rss3/vitalik.eth/all/all"
    },
    {
      "description": "0xf79f21c74a1E53c5eb148EB0C6E64196a30D439c activities - Powered by RSSHub",
      "errorAt": "2025-06-10T21:12:10.682Z",
      "errorMessage": "Cannot find module '/app/node_modules/.pnpm/@rss3+api-core@0.0.25/node_modules/@rss3/api-core/dist/types/component-aliases' imported from /app/node_modules/.pnpm/@rss3+api-core@0.0.25/node_modules/@rss3/api-core/dist/index.js\n",
      "id": "41948023876312064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rss3.io/",
      "title": "0xf79f21c74a1E53c5eb148EB0C6E64196a30D439c activities",
      "type": "feed",
      "url": "rsshub://rss3/0xf79f21c74a1E53c5eb148EB0C6E64196a30D439c/ethereum/transaction"
    }
  ],
  "url": "docs.rss3.io/api-reference#tag/decentralized/GET/decentralized/%7Baccount%7D"
}
```
