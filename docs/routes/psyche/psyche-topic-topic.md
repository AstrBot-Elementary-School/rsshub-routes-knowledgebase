# Psyche - Topics

## Coverage
`index-only`

## Route
- Namespace: `psyche`
- Namespace Name: `Psyche`
- Route Path: `/psyche/topic/:topic`
- Route Name: `Topics`
- Example: `/psyche/topic/therapeia`
- URL: `psyche.co`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
Supported categories: Therapeia, Eudaimonia, and Poiesis.

## Parameters
- `topic`: Topic


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `psyche.co/:topic`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Supported categories: Therapeia, Eudaimonia, and Poiesis.",
  "example": "/psyche/topic/therapeia",
  "heat": 2,
  "location": "topic.ts",
  "maintainers": [
    "emdoe"
  ],
  "name": "Topics",
  "parameters": {
    "topic": "Topic"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "psyche.co/:topic"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Expert insights and practical help from psychologists, therapists and other professionals who can help you deal with the emotional and psychological challenges of life. - Powered by RSSHub",
      "errorAt": "2025-01-09T00:35:57.859Z",
      "errorMessage": "[GET] \"https://psyche.co/therapeia\": 429 Too Many Requests\n",
      "id": "73541535521044480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://psyche.co/therapeia",
      "title": "Psyche | Therapeia",
      "type": "feed",
      "url": "rsshub://psyche/topic/therapeia"
    }
  ]
}
```
