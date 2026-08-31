# Hexo - Blog using Fluid theme

## Coverage
`index-only`

## Route
- Namespace: `hexo`
- Namespace Name: `Hexo`
- Route Path: `/hexo/fluid/:url`
- Route Name: `Blog using Fluid theme`
- Example: `/hexo/fluid/hexo.fluid-dev.com`
- URL: `hexo.io`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `gao-keyong`
- Source Location: `fluid.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `url`: the blog URL without the protocol (http:// and https://)


## Features
- `requireConfig`: [{"description": "Allow user supplied domain", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/hexo/fluid/hexo.fluid-dev.com",
  "features": {
    "requireConfig": [
      {
        "description": "Allow user supplied domain",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ]
  },
  "heat": 0,
  "location": "fluid.ts",
  "maintainers": [
    "gao-keyong"
  ],
  "name": "Blog using Fluid theme",
  "parameters": {
    "url": "the blog URL without the protocol (http:// and https://)"
  },
  "path": "/fluid/:url",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
