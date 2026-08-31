# QuestN - Events

## Coverage
`index-only`

## Route
- Namespace: `questn`
- Namespace Name: `QuestN`
- Route Path: `/questn/events/:filter?`
- Route Name: `Events`
- Example: `/questn/events`
- URL: `app.questn.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `events.ts`
- Source Module: `_None_`

## Description
::: tip

Filter parameters:

- category: 100: trending, 200: newest, 300: top
- status\_filter: 0: all, 100: available, 400: missed
- community\_filter: 0: all community, 100: verified, 200: followed
- rewards\_filter: 0: all rewards, 100: nft, 200: token, 400: whitelist
- chain\_filter: 0: all chains, 1: ethereum, 56: bsc, 137: polygon, 42161: arb, 10: op, 324: zksync, 43114: avax
- search: 'Search keyword',
- count: 'Number of events to fetch',
- page: 'Page number',

:::

## Parameters
- `filter`: Filter string


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `app.questn.com/explore`
- `target`: `/events/:category?/:status_filter?/:community_filter?/:reward_filter?/:chain_filter?/:search?/:count?/:page?`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\n\nFilter parameters:\n\n- category: 100: trending, 200: newest, 300: top\n- status\\_filter: 0: all, 100: available, 400: missed\n- community\\_filter: 0: all community, 100: verified, 200: followed\n- rewards\\_filter: 0: all rewards, 100: nft, 200: token, 400: whitelist\n- chain\\_filter: 0: all chains, 1: ethereum, 56: bsc, 137: polygon, 42161: arb, 10: op, 324: zksync, 43114: avax\n- search: 'Search keyword',\n- count: 'Number of events to fetch',\n- page: 'Page number',\n\n:::",
  "example": "/questn/events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "events.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Events",
  "parameters": {
    "filter": "Filter string"
  },
  "path": "/events/:filter?",
  "radar": [
    {
      "source": [
        "app.questn.com/explore"
      ],
      "target": "/events/:category?/:status_filter?/:community_filter?/:reward_filter?/:chain_filter?/:search?/:count?/:page?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "A Quest Protocol Dedicated to DePIN and AI Training - Powered by RSSHub",
      "errorAt": "2024-12-24T13:16:45.787Z",
      "errorMessage": "[GET] \"https://api.questn.com/consumer/explore/list/?category=200&status_filter=100&community_filter=0&rewards_filter=0&chain_filter=0&search=&count=20&page=1\": 403 Forbidden\n",
      "id": "59145487772061696",
      "image": "https://app.questn.com/static/svgs/logo-white.svg",
      "ownerUserId": null,
      "siteUrl": "https://app.questn.com/explore",
      "title": "QuestN Events",
      "type": "feed",
      "url": "rsshub://questn/events"
    }
  ],
  "url": "app.questn.com"
}
```
