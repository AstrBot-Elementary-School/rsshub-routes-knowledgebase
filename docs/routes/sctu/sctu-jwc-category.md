# 四川旅游学院 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `sctu`
- Namespace Name: `四川旅游学院`
- Route Path: `/sctu/jwc/:category?`
- Route Name: `教务处`
- Example: `/sctu/jwc/tzgg`
- URL: `www.sctu.edu.cn/jwc/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `talenHuang`
- Source Location: `jwc/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "tzgg", "description": "分类", "options": [{"label": "通知公告", "value": "tzgg"}, {"label": "新闻动态", "value": "xwdt"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sctu.edu.cn/jwc/wenzhangg/:category.htm`
- `target`: `/jwc/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/sctu/jwc/tzgg",
  "heat": 0,
  "location": "jwc/index.ts",
  "maintainers": [
    "talenHuang"
  ],
  "name": "教务处",
  "parameters": {
    "category": {
      "default": "tzgg",
      "description": "分类",
      "options": [
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "新闻动态",
          "value": "xwdt"
        }
      ]
    }
  },
  "path": "/jwc/:category?",
  "radar": [
    {
      "source": [
        "www.sctu.edu.cn/jwc/wenzhangg/:category.htm"
      ],
      "target": "/jwc/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.sctu.edu.cn/jwc/"
}
```
