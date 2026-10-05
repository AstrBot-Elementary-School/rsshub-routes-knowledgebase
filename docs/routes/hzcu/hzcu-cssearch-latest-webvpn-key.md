# 浙大城市学院 - 计算分院全站搜索

## Coverage
`index-only`

## Route
- Namespace: `hzcu`
- Namespace Name: `浙大城市学院`
- Route Path: `/hzcu/cssearch/latest/:webVpn/:key`
- Route Name: `计算分院全站搜索`
- Example: `/hzcu/cssearch/latest/0/白卡`
- URL: `www.hzcu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `zhang-wangz`
- Source Location: `cssearch.ts`
- Source Module: `_None_`

## Description
| 0                  | 1                    |
| ------------------ | -------------------- |
| 文章地址为正常地址 | 获取的是 webvpn 地址 |

## Parameters
- `webVpn`: 见下表(默认为0)
- `key`: 关键词(默认为白卡)


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 0                  | 1                    |\n| ------------------ | -------------------- |\n| 文章地址为正常地址 | 获取的是 webvpn 地址 |",
  "example": "/hzcu/cssearch/latest/0/白卡",
  "heat": 0,
  "location": "cssearch.ts",
  "maintainers": [
    "zhang-wangz"
  ],
  "name": "计算分院全站搜索",
  "parameters": {
    "key": "关键词(默认为白卡)",
    "webVpn": "见下表(默认为0)"
  },
  "path": "/cssearch/latest/:webVpn/:key",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
