# GitCode - 仓库提交

## Coverage
`index-only`

## Route
- Namespace: `gitcode`
- Namespace Name: `GitCode`
- Route Path: `/gitcode/commits/:owner/:repo/:branch?`
- Route Name: `仓库提交`
- Example: `/gitcode/commits/openharmony-sig/flutter_flutter`
- URL: `gitcode.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `JiZhi-Error`
- Source Location: `repos/commits.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `owner`: 用户名/组织名
- `repo`: 仓库名
- `branch`: 分支名，可选，默认为主分支


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
  - `gitcode.com/:owner/:repo/commits`
  - `gitcode.com/:owner/:repo/commits/:branch`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitcode/commits/openharmony-sig/flutter_flutter",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "repos/commits.ts",
  "maintainers": [
    "JiZhi-Error"
  ],
  "name": "仓库提交",
  "parameters": {
    "branch": "分支名，可选，默认为主分支",
    "owner": "用户名/组织名",
    "repo": "仓库名"
  },
  "path": "/commits/:owner/:repo/:branch?",
  "radar": [
    {
      "source": [
        "gitcode.com/:owner/:repo/commits",
        "gitcode.com/:owner/:repo/commits/:branch"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
