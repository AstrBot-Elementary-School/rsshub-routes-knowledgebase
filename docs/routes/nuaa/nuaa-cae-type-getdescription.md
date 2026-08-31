# 南京航空航天大学 - 自动化学院

## Coverage
`index-only`

## Route
- Namespace: `nuaa`
- Namespace Name: `南京航空航天大学`
- Route Path: `/nuaa/cae/:type/:getDescription?`
- Route Name: `自动化学院`
- Example: `/nuaa/cae/zhxw`
- URL: `aao.nuaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Xm798`
- Source Location: `college/cae.ts`
- Source Module: `_None_`

## Description
| 综合新闻 | 党委行政 | 人事 / 合作 | 研究生培养 | 本科生培养 | 学生工作 | 通知公告 | 学术信息 | 答辩公告 |
| -------- | -------- | ----------- | ---------- | ---------- | -------- | -------- | -------- | -------- |
| zhxw     | dwxz     | rshz        | yjs        | bks        | xsgz     | tzgg     | xsxx     | dbgg     |

## Parameters
- `type`: 分类名，见下表
- `getDescription`: 是否获取全文


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
  "description": "| 综合新闻 | 党委行政 | 人事 / 合作 | 研究生培养 | 本科生培养 | 学生工作 | 通知公告 | 学术信息 | 答辩公告 |\n| -------- | -------- | ----------- | ---------- | ---------- | -------- | -------- | -------- | -------- |\n| zhxw     | dwxz     | rshz        | yjs        | bks        | xsgz     | tzgg     | xsxx     | dbgg     |",
  "example": "/nuaa/cae/zhxw",
  "heat": 0,
  "location": "college/cae.ts",
  "maintainers": [
    "Xm798"
  ],
  "name": "自动化学院",
  "parameters": {
    "getDescription": "是否获取全文",
    "type": "分类名，见下表"
  },
  "path": "/cae/:type/:getDescription?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
