# Sankei Shimbun 産経新聞 - Topic

## Coverage
`index-only`

## Route
- Namespace: `sankei`
- Namespace Name: `Sankei Shimbun 産経新聞`
- Route Path: `/sankei/topics/:topic`
- Route Name: `Topic`
- Example: `/sankei/topics/etc_100`
- URL: `sankei.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `yuikisaito`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic name (format included in URL). For example, for "Expo 2025 Osaka, Kansai, Japan Special Feature" https://www.sankei.com/tag/topic/etc_100, the value would be etc_100.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sankei.com/tag/topic/:topic`
- `target`: `/topics/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/sankei/topics/etc_100",
  "heat": 0,
  "location": "topics.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "name": "Topic",
  "parameters": {
    "topic": "Topic name (format included in URL). For example, for \"Expo 2025 Osaka, Kansai, Japan Special Feature\" https://www.sankei.com/tag/topic/etc_100, the value would be etc_100."
  },
  "path": "/topics/:topic",
  "radar": [
    {
      "source": [
        "www.sankei.com/tag/topic/:topic"
      ],
      "target": "/topics/:topic"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
