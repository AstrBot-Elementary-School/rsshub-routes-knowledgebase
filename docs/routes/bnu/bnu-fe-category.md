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
`https://fe.bnu.edu.cn/pc/cms1info/list/1/18` 则对应为 \`/bnu/fe/18

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fe.bnu.edu.cn/pc/cms1info/list/1/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "`https://fe.bnu.edu.cn/pc/cms1info/list/1/18` 则对应为 \\`/bnu/fe/18",
  "example": "/bnu/fe/18",
  "heat": 0,
  "location": "fe.ts",
  "maintainers": [
    "etShaw-zh"
  ],
  "name": "教育学部-培养动态",
  "parameters": {},
  "path": "/fe/:category",
  "radar": [
    {
      "source": [
        "fe.bnu.edu.cn/pc/cms1info/list/1/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
