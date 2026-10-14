# 北京师范大学 - 教育学部-培养动态

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/bnu/fe/:category`
- Route Name: `教育学部-培养动态`
- Example: `/bnu/fe/18`
- URL: `bs.bnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `etShaw-zh`
- Source Location: `fe.ts`
- Source Module: `_None_`

## Description
订阅教育学部当前网站的培养动态栏目。旧网站分类编号 `18` 保持兼容；其他旧分类编号尚未确认对应栏目。

## Parameters
- `category`: 分类编号，目前支持 `18`（培养动态）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fe.bnu.edu.cn/jyjx/pydt/index.htm`
- `target`: `/fe/18`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "订阅教育学部当前网站的培养动态栏目。旧网站分类编号 `18` 保持兼容；其他旧分类编号尚未确认对应栏目。",
  "example": "/bnu/fe/18",
  "heat": 0,
  "location": "fe.ts",
  "maintainers": [
    "etShaw-zh"
  ],
  "name": "教育学部-培养动态",
  "parameters": {
    "category": "分类编号，目前支持 `18`（培养动态）"
  },
  "path": "/fe/:category",
  "radar": [
    {
      "source": [
        "fe.bnu.edu.cn/jyjx/pydt/index.htm"
      ],
      "target": "/fe/18"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
