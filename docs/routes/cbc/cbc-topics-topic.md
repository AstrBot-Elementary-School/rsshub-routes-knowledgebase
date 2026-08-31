# Canadian Broadcasting Corporation - News

## Coverage
`index-only`

## Route
- Namespace: `cbc`
- Namespace Name: `Canadian Broadcasting Corporation`
- Route Path: `/cbc/topics/:topic?`
- Route Name: `News`
- Example: `/cbc/topics`
- URL: `cbc.ca/news`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `wb14123`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Channel,`Top Stories` by default. For secondary channel like `canada/toronto`, use `-` to replace `/`


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
  - `cbc.ca/news`
- `target`: `/topics`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cbc/topics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 50,
  "location": "topics.ts",
  "maintainers": [
    "wb14123"
  ],
  "name": "News",
  "parameters": {
    "topic": "Channel,`Top Stories` by default. For secondary channel like `canada/toronto`, use `-` to replace `/`"
  },
  "path": "/topics/:topic?",
  "radar": [
    {
      "source": [
        "cbc.ca/news"
      ],
      "target": "/topics"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(25) ] to not include 'https://www.cbc.ca/news/politics/cana…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "CBC News - Latest Canada, World, Entertainment and Business NewsMenuTelevisionheadphonePrevious itemNext item - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165818925513194496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cbc.ca/news",
      "title": "CBC News - Latest Canada, World, Entertainment and Business NewsMenuTelevisionheadphonePrevious itemNext item",
      "type": "feed",
      "url": "rsshub://cbc/topics"
    },
    {
      "description": "Ottawa - CBC NewsMenuTelevisionheadphone - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60766614420573184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cbc.ca/news/canada/ottawa",
      "title": "Ottawa - CBC NewsMenuTelevisionheadphone",
      "type": "feed",
      "url": "rsshub://cbc/topics/canada-ottawa"
    }
  ],
  "url": "cbc.ca/news"
}
```
