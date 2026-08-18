# Eagle - Changelog

## Coverage
`index-only`

## Route
- Namespace: `eagle`
- Namespace Name: `Eagle`
- Route Path: `/eagle/changelog/:language?`
- Route Name: `Changelog`
- Example: `/eagle/changelog/en`
- URL: `cn.eagle.cool`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `tigercubden`
- Source Location: `changelog.ts`
- Source Module: `_None_`

## Description
Language

| Simplified Chinese | Traditional Chinese | English |
| ------------------ | ------------------- | ------- |
| cn                 | tw                  | en      |

## Parameters
- `language`: Language, see list, default to be `cn`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Language\n\n| Simplified Chinese | Traditional Chinese | English |\n| ------------------ | ------------------- | ------- |\n| cn                 | tw                  | en      |",
  "example": "/eagle/changelog/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 37,
  "location": "changelog.ts",
  "maintainers": [
    "tigercubden"
  ],
  "name": "Changelog",
  "parameters": {
    "language": "Language, see list, default to be `cn`"
  },
  "path": "/changelog/:language?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Eagle 更新日志 - Powered by RSSHub",
      "errorAt": "2025-06-01T01:52:40.601Z",
      "errorMessage": "[GET] \"https://cn.eagle.cool/changelog\": 404 Not Found\n[GET] \"https://cn.eagle.cool/changelog\": 404 Not Found\n",
      "id": "41147805276726367",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.eagle.cool/changelog",
      "title": "Eagle 更新日志",
      "type": "feed",
      "url": "rsshub://eagle/changelog"
    },
    {
      "description": "Eagle Release Notes - Powered by RSSHub",
      "errorAt": "2025-06-01T02:36:50.835Z",
      "errorMessage": "[GET] \"https://en.eagle.cool/changelog\": 404 Not Found\n",
      "id": "84654326956328960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://en.eagle.cool/changelog",
      "title": "Eagle Release Notes",
      "type": "feed",
      "url": "rsshub://eagle/changelog/en"
    }
  ]
}
```
