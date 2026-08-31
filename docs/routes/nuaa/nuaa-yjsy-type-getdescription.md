# 南京航空航天大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nuaa`
- Namespace Name: `南京航空航天大学`
- Route Path: `/nuaa/yjsy/:type/:getDescription?`
- Route Name: `研究生院`
- Example: `/nuaa/yjsy/tzgg/getDescription`
- URL: `aao.nuaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `junfengP, Seiry, Xm798`
- Source Location: `yjsy/yjsy.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻动态 | 学术信息 | 师生风采 |
| -------- | -------- | -------- | -------- |
| tzgg     | xwdt     | xsxx     | ssfc     |

## Parameters
- `type`: 分类名，见下表
- `getDescription`: 是否获取全文


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻动态 | 学术信息 | 师生风采 |\n| -------- | -------- | -------- | -------- |\n| tzgg     | xwdt     | xsxx     | ssfc     |",
  "example": "/nuaa/yjsy/tzgg/getDescription",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yjsy/yjsy.ts",
  "maintainers": [
    "junfengP",
    "Seiry",
    "Xm798"
  ],
  "name": "研究生院",
  "parameters": {
    "getDescription": "是否获取全文",
    "type": "分类名，见下表"
  },
  "path": "/yjsy/:type/:getDescription?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
