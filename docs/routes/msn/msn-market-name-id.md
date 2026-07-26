# MSN - News

## Coverage
`index-only`

## Route
- Namespace: `msn`
- Namespace Name: `MSN`
- Route Path: `/msn/:market/:name/:id`
- Route Name: `News`
- Example: `/msn/zh-tw/Bloomberg/sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s`
- URL: `msn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `KTachibanaM`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
MSN News

## Parameters
- `market`: Market code. Find it in MSN url, e.g. zh-tw
- `name`: Name of the channel. Find it in MSN url, e.g. Bloomberg
- `id`: ID of the channel (always starts with sr-vid). Find it in MSN url, e.g. sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.msn.com/:market/channel/source/:name/:id`
- `target`: `/:market/:name/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "MSN News",
  "example": "/msn/zh-tw/Bloomberg/sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 26,
  "location": "index.ts",
  "maintainers": [
    "KTachibanaM"
  ],
  "name": "News",
  "parameters": {
    "id": "ID of the channel (always starts with sr-vid). Find it in MSN url, e.g. sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s",
    "market": "Market code. Find it in MSN url, e.g. zh-tw",
    "name": "Name of the channel. Find it in MSN url, e.g. Bloomberg"
  },
  "path": "/:market/:name/:id",
  "radar": [
    {
      "source": [
        "www.msn.com/:market/channel/source/:name/:id"
      ],
      "target": "/:market/:name/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Bloomberg - Powered by RSSHub",
      "errorAt": "2026-07-18T12:25:52.363Z",
      "errorMessage": "Cannot read properties of undefined (reading 'cards')\nCannot read properties of undefined (reading 'cards')\n",
      "id": "99576216016317440",
      "image": "https://www.msn.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.msn.com/zh-tw/channel/source/Bloomberg/sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s",
      "title": "Bloomberg",
      "type": "feed",
      "url": "rsshub://msn/zh-tw/Bloomberg/sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s"
    },
    {
      "description": "Press Trust of India - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95284553009393664",
      "image": "https://www.msn.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.msn.com/en-in/channel/source/Press%20Trust%20of%20India/sr-vid-gnv22w2jk8eqhkww6pjggiv62h2xdehqpe33x067ju77kai629ta",
      "title": "Press Trust of India",
      "type": "feed",
      "url": "rsshub://msn/en-in/Press%20Trust%20of%20India/sr-vid-gnv22w2jk8eqhkww6pjggiv62h2xdehqpe33x067ju77kai629ta"
    }
  ]
}
```
