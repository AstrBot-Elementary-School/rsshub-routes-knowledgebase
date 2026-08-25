# 成都信息工程大学 - 成信新闻网

## Coverage
`index-only`

## Route
- Namespace: `cuit`
- Namespace Name: `成都信息工程大学`
- Route Path: `/cuit/cxxww/:category{.+}?`
- Route Name: `成信新闻网`
- Example: `/cuit/cxxww/zhxw`
- URL: `www.cuit.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `luojunyuan`
- Source Location: `cxxww.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "zhxw", "description": "分类", "options": [{"label": "综合新闻", "value": "zhxw"}, {"label": "通知公告", "value": "tzgg"}, {"label": "成信要闻", "value": "cxyw"}, {"label": "成信学术", "value": "cxxs"}, {"label": "媒体成信", "value": "mtcx"}, {"label": "文化活动", "value": "cxwh/whhd"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cuit.edu.cn/index/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cuit/cxxww/zhxw",
  "heat": 0,
  "location": "cxxww.ts",
  "maintainers": [
    "luojunyuan"
  ],
  "name": "成信新闻网",
  "parameters": {
    "category": {
      "default": "zhxw",
      "description": "分类",
      "options": [
        {
          "label": "综合新闻",
          "value": "zhxw"
        },
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "成信要闻",
          "value": "cxyw"
        },
        {
          "label": "成信学术",
          "value": "cxxs"
        },
        {
          "label": "媒体成信",
          "value": "mtcx"
        },
        {
          "label": "文化活动",
          "value": "cxwh/whhd"
        }
      ]
    }
  },
  "path": "/cxxww/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.cuit.edu.cn/index/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.cuit.edu.cn"
}
```
