# Engineering.fyi - Tag

## Coverage
`index-only`

## Route
- Namespace: `engineering`
- Namespace Name: `Engineering.fyi`
- Route Path: `/engineering/tag/:tag`
- Route Name: `Tag`
- Example: `/engineering/tag/javascript`
- URL: `engineering.fyi`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `suhang-only`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
| JSON | Javascript | Java | Apache | AWS | SQL | React | Golang |
| ---- | ---------- | ---- | ------ | --- | --- | ----- | ------ |
| json | javascript | java | apache | aws | sql | react | golang |

## Parameters
- `tag`: Browse programming languages, frameworks, and technologies


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
  - `engineering.fyi/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| JSON | Javascript | Java | Apache | AWS | SQL | React | Golang |\n| ---- | ---------- | ---- | ------ | --- | --- | ----- | ------ |\n| json | javascript | java | apache | aws | sql | react | golang |",
  "example": "/engineering/tag/javascript",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "tag.ts",
  "maintainers": [
    "suhang-only"
  ],
  "name": "Tag",
  "parameters": {
    "tag": "Browse programming languages, frameworks, and technologies"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "engineering.fyi/tag/:tag"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "engineering.fyi javascript - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "201977155428993024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://engineering.fyi/tag/javascript",
      "title": "engineering.fyi javascript",
      "type": "feed",
      "url": "rsshub://engineering/tag/javascript"
    }
  ]
}
```
