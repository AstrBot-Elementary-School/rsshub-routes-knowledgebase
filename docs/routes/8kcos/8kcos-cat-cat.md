# 8KCosplay - 分类

## Coverage
`index-only`

## Route
- Namespace: `8kcos`
- Namespace Name: `8KCosplay`
- Route Path: `/8kcos/cat/:cat?`
- Route Name: `分类`
- Example: `/8kcos/cat/8kasianidol`
- URL: `8kcosplay.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KotoriK`
- Source Location: `cat.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cat`: 默认值为 `8kasianidol`，将目录页面url中 /category/ 后面的部分填入。如：https://www.8kcosplay.com/category/8kchineseidol/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f/ 对应的RSS页面为 /8kcos/cat/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f。


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `8kcosplay.com/category/:mainCategory/:cat/`
  - `8kcosplay.com/category/:cat/`
- `target`: `/cat/:cat`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/8kcos/cat/8kasianidol",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "cat.ts",
  "maintainers": [
    "KotoriK"
  ],
  "name": "分类",
  "parameters": {
    "cat": "默认值为 `8kasianidol`，将目录页面url中 /category/ 后面的部分填入。如：https://www.8kcosplay.com/category/8kchineseidol/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f/ 对应的RSS页面为 /8kcos/cat/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f。"
  },
  "path": "/cat/:cat?",
  "radar": [
    {
      "source": [
        "8kcosplay.com/category/:mainCategory/:cat/",
        "8kcosplay.com/category/:cat/"
      ],
      "target": "/cat/:cat"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "8kcosplay.com/"
}
```
