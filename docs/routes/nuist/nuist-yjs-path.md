# 南京信息工程大学 - 研究生院学科建设处

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/nuist/yjs/:path{.+}?`
- Route Name: `研究生院学科建设处`
- Example: `/nuist/yjs/index/tzgg`
- URL: `bulletin.nuist.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gylidian, nczitzk`
- Source Location: `yjs.ts`
- Source Module: `_None_`

## Description
路径字段处填写的是对应南京信息工程大学研究生院学科建设处分类页网址中介于 **<https://yjs.nuist.edu.cn/>** 和 **.htm** 中间的一段。

如 [南京信息工程大学研究生院学科建设处工作动态](https://yjs.nuist.edu.cn/index/gzdt.htm) 的网址为 <https://yjs.nuist.edu.cn/index/gzdt.htm，其中介于> **<https://yjs.nuist.edu.cn/>** 和 **.htm** 中间的一段为 `index/gzdt`。可以得到路由为 [`/nuist/yjs/index/gzdt`](https://rsshub.app/nuist/yjs/index/gzdt)

以下为部分分类：

| 工作动态   | 通知公告   | 招生工作  | 培养与学位 | 学生工作   |
| ---------- | ---------- | --------- | ---------- | ---------- |
| index/gzdt | index/tzgg | zsgz/sszs | xwgz/xwtz  | xsgz1/xzfc |

## Parameters
- `path`: 默认为通知公告


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
  "description": "路径字段处填写的是对应南京信息工程大学研究生院学科建设处分类页网址中介于 **<https://yjs.nuist.edu.cn/>** 和 **.htm** 中间的一段。\n\n如 [南京信息工程大学研究生院学科建设处工作动态](https://yjs.nuist.edu.cn/index/gzdt.htm) 的网址为 <https://yjs.nuist.edu.cn/index/gzdt.htm，其中介于> **<https://yjs.nuist.edu.cn/>** 和 **.htm** 中间的一段为 `index/gzdt`。可以得到路由为 [`/nuist/yjs/index/gzdt`](https://rsshub.app/nuist/yjs/index/gzdt)\n\n以下为部分分类：\n\n| 工作动态   | 通知公告   | 招生工作  | 培养与学位 | 学生工作   |\n| ---------- | ---------- | --------- | ---------- | ---------- |\n| index/gzdt | index/tzgg | zsgz/sszs | xwgz/xwtz  | xsgz1/xzfc |",
  "example": "/nuist/yjs/index/tzgg",
  "heat": 0,
  "location": "yjs.ts",
  "maintainers": [
    "gylidian",
    "nczitzk"
  ],
  "name": "研究生院学科建设处",
  "parameters": {
    "path": "默认为通知公告"
  },
  "path": "/yjs/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
