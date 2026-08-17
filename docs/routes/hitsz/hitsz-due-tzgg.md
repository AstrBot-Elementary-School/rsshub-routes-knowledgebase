# 哈尔滨工业大学（深圳） - 教务部

## Coverage
`index-only`

## Route
- Namespace: `hitsz`
- Namespace Name: `哈尔滨工业大学（深圳）`
- Route Path: `/hitsz/due/tzgg`
- Route Name: `教务部`
- Example: `/hitsz/due/tzgg`
- URL: `due.hitsz.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `guohuiyuan`
- Source Location: `due-tzgg.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [通知公告](http://due.hitsz.edu.cn/index/tzggqb.htm)，其源网址为 `http://due.hitsz.edu.cn/index/tzggqb.htm`，请参考该 URL 指定部分构成参数，此时路由为 [`/hitsz/due/tzgg`](https://rsshub.app/hitsz/due/tzgg)。
:::
如需获取教务学务和学位管理所有栏目的新闻汇总，请使用 [`/hitsz/due/general`](https://rsshub.app/hitsz/due/general) 路由。

<details>
<summary>更多栏目</summary>

| 栏目                                                 | ID                                        |
| ---------------------------------------------------- | ----------------------------------------- |
| [通知公告](http://due.hitsz.edu.cn/index/tzggqb.htm) | [tzgg](https://rsshub.app/hitsz/due/tzgg) |

</details>

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `due.hitsz.edu.cn`
  - `due.hitsz.edu.cn/index/:id/list.htm`
- `target`: `/hitsz/due/:id`
### Rule 2
- `title`: `通知公告`
- `source`:
  - `due.hitsz.edu.cn/index/tzggqb.htm`
- `target`: `/hitsz/due/tzgg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n订阅 [通知公告](http://due.hitsz.edu.cn/index/tzggqb.htm)，其源网址为 `http://due.hitsz.edu.cn/index/tzggqb.htm`，请参考该 URL 指定部分构成参数，此时路由为 [`/hitsz/due/tzgg`](https://rsshub.app/hitsz/due/tzgg)。\n:::\n如需获取教务学务和学位管理所有栏目的新闻汇总，请使用 [`/hitsz/due/general`](https://rsshub.app/hitsz/due/general) 路由。\n\n<details>\n<summary>更多栏目</summary>\n\n| 栏目                                                 | ID                                        |\n| ---------------------------------------------------- | ----------------------------------------- |\n| [通知公告](http://due.hitsz.edu.cn/index/tzggqb.htm) | [tzgg](https://rsshub.app/hitsz/due/tzgg) |\n\n</details>",
  "example": "/hitsz/due/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "due-tzgg.ts",
  "maintainers": [
    "guohuiyuan"
  ],
  "name": "教务部",
  "parameters": {},
  "path": "/due/tzgg",
  "radar": [
    {
      "source": [
        "due.hitsz.edu.cn",
        "due.hitsz.edu.cn/index/:id/list.htm"
      ],
      "target": "/hitsz/due/:id"
    },
    {
      "source": [
        "due.hitsz.edu.cn/index/tzggqb.htm"
      ],
      "target": "/hitsz/due/tzgg",
      "title": "通知公告"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "due.hitsz.edu.cn"
}
```
