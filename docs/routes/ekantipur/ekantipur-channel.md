# Ekantipur / कान्तिपुर (Nepal) - Full Article RSS

## Coverage
`index-only`

## Route
- Namespace: `ekantipur`
- Namespace Name: `Ekantipur / कान्तिपुर (Nepal)`
- Route Path: `/ekantipur/:channel?`
- Route Name: `Full Article RSS`
- Example: `/ekantipur/news`
- URL: `ekantipur.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `maniche04`
- Source Location: `issue.ts`
- Source Module: `_None_`

## Description
Channels:

| समाचार | अर्थ / वाणिज्य | विचार     | खेलकुद   | उपत्यका    | मनोरञ्जन        | फोटोफिचर          | फिचर     | विश्व   | ब्लग  |
| ---- | ---------- | ------- | ------ | -------- | ------------- | -------------- | ------- | ----- | ---- |
| news | business   | opinion | sports | national | entertainment | photo\_feature | feature | world | blog |

## Parameters
- `channel`: Find it in the ekantipur.com menu or pick from the list below:


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
  - `ekantipur.com/:channel`
- `target`: `/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Channels:\n\n| समाचार | अर्थ / वाणिज्य | विचार     | खेलकुद   | उपत्यका    | मनोरञ्जन        | फोटोफिचर          | फिचर     | विश्व   | ब्लग  |\n| ---- | ---------- | ------- | ------ | -------- | ------------- | -------------- | ------- | ----- | ---- |\n| news | business   | opinion | sports | national | entertainment | photo\\_feature | feature | world | blog |",
  "example": "/ekantipur/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "issue.ts",
  "maintainers": [
    "maniche04"
  ],
  "name": "Full Article RSS",
  "parameters": {
    "channel": "Find it in the ekantipur.com menu or pick from the list below:"
  },
  "path": "/:channel?",
  "radar": [
    {
      "source": [
        "ekantipur.com/:channel"
      ],
      "target": "/:channel"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Ekantipur - news - Powered by RSSHub",
      "errorAt": "2026-02-08T10:59:41.504Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "74038006711254016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ekantipur.com/news",
      "title": "Ekantipur - news",
      "type": "feed",
      "url": "rsshub://ekantipur/news"
    }
  ]
}
```
