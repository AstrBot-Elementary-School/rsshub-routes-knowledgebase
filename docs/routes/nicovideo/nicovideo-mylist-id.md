# Niconico - Mylist

## Coverage
`index-only`

## Route
- Namespace: `nicovideo`
- Namespace Name: `Niconico`
- Route Path: `/nicovideo/mylist/:id`
- Route Name: `Mylist`
- Example: `/nicovideo/mylist/2973737`
- URL: `www.nicovideo.jp`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `esperecyan`
- Source Location: `mylist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Mylist ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nicovideo.jp/user/:user/mylist/:id`
- `target`: `/mylist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/nicovideo/mylist/2973737",
  "heat": 0,
  "location": "mylist.ts",
  "maintainers": [
    "esperecyan"
  ],
  "name": "Mylist",
  "parameters": {
    "id": "Mylist ID"
  },
  "path": "/mylist/:id",
  "radar": [
    {
      "source": [
        "www.nicovideo.jp/user/:user/mylist/:id"
      ],
      "target": "/mylist/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 419253438208 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
