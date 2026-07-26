# Greasy Fork - Script Update

## Coverage
`index-only`

## Route
- Namespace: `greasyfork`
- Namespace Name: `Greasy Fork`
- Route Path: `/greasyfork/:language/:domain?`
- Route Name: `Script Update`
- Example: `/greasyfork/en/google.com`
- URL: `greasyfork.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `imlonghao, miles170`
- Source Location: `scripts.ts`
- Source Module: `_None_`

## Description
| Sort            | Description    |
| --------------- | -------------- |
| today           | Daily installs |
| total\_installs | Total installs |
| ratings         | Ratings        |
| created         | Created date   |
| updated         | Updated date   |
| name            | Name           |

## Parameters
- `language`: language, located on the top right corner of Greasy Fork's search page, set to `all` for including all languages
- `domain`: the script's target domain


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
  - `greasyfork.org/:language`
  - `greasyfork.org/:language/scripts/by-site/:domain?`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "| Sort            | Description    |\n| --------------- | -------------- |\n| today           | Daily installs |\n| total\\_installs | Total installs |\n| ratings         | Ratings        |\n| created         | Created date   |\n| updated         | Updated date   |\n| name            | Name           |",
  "example": "/greasyfork/en/google.com",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23,
  "location": "scripts.ts",
  "maintainers": [
    "imlonghao",
    "miles170"
  ],
  "name": "Script Update",
  "parameters": {
    "domain": "the script's target domain",
    "language": "language, located on the top right corner of Greasy Fork's search page, set to `all` for including all languages"
  },
  "path": [
    "/:language/:domain?",
    "/scripts/sort/:sort/:language?"
  ],
  "radar": [
    {
      "source": [
        "greasyfork.org/:language",
        "greasyfork.org/:language/scripts/by-site/:domain?"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "用户脚本 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70371597455258625",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://greasyfork.org/zh-CN/scripts",
      "title": "用户脚本",
      "type": "feed",
      "url": "rsshub://greasyfork/zh-CN"
    },
    {
      "description": "User scripts for google.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126248223506523136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://greasyfork.org/en/scripts/by-site/google.com",
      "title": "User scripts for google.com",
      "type": "feed",
      "url": "rsshub://greasyfork/en/google.com"
    }
  ]
}
```
