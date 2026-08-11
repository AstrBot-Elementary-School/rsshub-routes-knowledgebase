# 哈尔滨工业大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `hit`
- Namespace Name: `哈尔滨工业大学`
- Route Path: `/hit/hitgs/:id?`
- Route Name: `研究生院`
- Example: `/hit/hitgs/tzgg`
- URL: `hitgs.hit.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `hlmu, nczitzk`
- Source Location: `hitgs.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [通知公告](https://hitgs.hit.edu.cn/tzgg/list.htm)，其源网址为 `https://hitgs.hit.edu.cn/tzgg/list.htm`，请参考该 URL 指定部分构成参数，此时路由为 [`/hit/hitgs/tzgg`](https://rsshub.app/hit/hitgs/tzgg)。
:::

<details>
  <summary>更多栏目</summary>

| 栏目                                                                 | ID                                                    |
| -------------------------------------------------------------------- | ----------------------------------------------------- |
| [通知公告](https://hitgs.hit.edu.cn/tzgg/list.htm)                   | [tzgg](https://rsshub.app/hit/hitgs/tzgg)             |
| [综合新闻](https://hitgs.hit.edu.cn/zhxw/list.htm)                   | [zhxw](https://rsshub.app/hit/hitgs/zhxw)             |
| [高水平课程与学术交流](https://hitgs.hit.edu.cn/gspkcyxsjl/list.htm) | [gspkcyxsjl](https://rsshub.app/hit/hitgs/gspkcyxsjl) |
| [国家政策](https://hitgs.hit.edu.cn/gjzc/list.htm)                   | [gjzc](https://rsshub.app/hit/hitgs/gjzc)             |
| [规章制度](https://hitgs.hit.edu.cn/17546/list.htm)                  | [17546](https://rsshub.app/hit/hitgs/17546)           |
| [办事流程](https://hitgs.hit.edu.cn/17547/list.htm)                  | [17547](https://rsshub.app/hit/hitgs/17547)           |
| [常见问题](https://hitgs.hit.edu.cn/17548/list.htm)                  | [17548](https://rsshub.app/hit/hitgs/17548)           |
| [常见下载](https://hitgs.hit.edu.cn/17549/list.htm)                  | [17549](https://rsshub.app/hit/hitgs/17549)           |

</details>

## Parameters
- `category`: {"description": "分类，默认为 `tzgg`，即通知公告，可在对应分类页 URL 中找到", "options": [{"label": "通知公告", "value": "tzgg"}, {"label": "综合新闻", "value": "zhxw"}, {"label": "高水平课程与学术交流", "value": "gspkcyxsjl"}, {"label": "国家政策", "value": "gjzc"}, {"label": "规章制度", "value": "17546"}, {"label": "办事流程", "value": "17547"}, {"label": "常见问题", "value": "17548"}, {"label": "常见下载", "value": "17549"}]}


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
  - `hitgs.hit.edu.cn`
  - `hitgs.hit.edu.cn/:id/list.htm`
### Rule 2
- `title`: `通知公告`
- `source`:
  - `hitgs.hit.edu.cn/tzgg/list.htm`
- `target`: `/hitgs/tzgg`
### Rule 3
- `title`: `综合新闻`
- `source`:
  - `hitgs.hit.edu.cn/zhxw/list.htm`
- `target`: `/hitgs/zhxw`
### Rule 4
- `title`: `高水平课程与学术交流`
- `source`:
  - `hitgs.hit.edu.cn/gspkcyxsjl/list.htm`
- `target`: `/hitgs/gspkcyxsjl`
### Rule 5
- `title`: `国家政策`
- `source`:
  - `hitgs.hit.edu.cn/gjzc/list.htm`
- `target`: `/hitgs/gjzc`
### Rule 6
- `title`: `规章制度`
- `source`:
  - `hitgs.hit.edu.cn/17546/list.htm`
- `target`: `/hitgs/17546`
### Rule 7
- `title`: `办事流程`
- `source`:
  - `hitgs.hit.edu.cn/17547/list.htm`
- `target`: `/hitgs/17547`
### Rule 8
- `title`: `常见问题`
- `source`:
  - `hitgs.hit.edu.cn/17548/list.htm`
- `target`: `/hitgs/17548`
### Rule 9
- `title`: `常见下载`
- `source`:
  - `hitgs.hit.edu.cn/17549/list.htm`
- `target`: `/hitgs/17549`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n订阅 [通知公告](https://hitgs.hit.edu.cn/tzgg/list.htm)，其源网址为 `https://hitgs.hit.edu.cn/tzgg/list.htm`，请参考该 URL 指定部分构成参数，此时路由为 [`/hit/hitgs/tzgg`](https://rsshub.app/hit/hitgs/tzgg)。\n:::\n\n<details>\n  <summary>更多栏目</summary>\n\n| 栏目                                                                 | ID                                                    |\n| -------------------------------------------------------------------- | ----------------------------------------------------- |\n| [通知公告](https://hitgs.hit.edu.cn/tzgg/list.htm)                   | [tzgg](https://rsshub.app/hit/hitgs/tzgg)             |\n| [综合新闻](https://hitgs.hit.edu.cn/zhxw/list.htm)                   | [zhxw](https://rsshub.app/hit/hitgs/zhxw)             |\n| [高水平课程与学术交流](https://hitgs.hit.edu.cn/gspkcyxsjl/list.htm) | [gspkcyxsjl](https://rsshub.app/hit/hitgs/gspkcyxsjl) |\n| [国家政策](https://hitgs.hit.edu.cn/gjzc/list.htm)                   | [gjzc](https://rsshub.app/hit/hitgs/gjzc)             |\n| [规章制度](https://hitgs.hit.edu.cn/17546/list.htm)                  | [17546](https://rsshub.app/hit/hitgs/17546)           |\n| [办事流程](https://hitgs.hit.edu.cn/17547/list.htm)                  | [17547](https://rsshub.app/hit/hitgs/17547)           |\n| [常见问题](https://hitgs.hit.edu.cn/17548/list.htm)                  | [17548](https://rsshub.app/hit/hitgs/17548)           |\n| [常见下载](https://hitgs.hit.edu.cn/17549/list.htm)                  | [17549](https://rsshub.app/hit/hitgs/17549)           |\n\n</details>",
  "example": "/hit/hitgs/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 6,
  "location": "hitgs.ts",
  "maintainers": [
    "hlmu",
    "nczitzk"
  ],
  "name": "研究生院",
  "parameters": {
    "category": {
      "description": "分类，默认为 `tzgg`，即通知公告，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "综合新闻",
          "value": "zhxw"
        },
        {
          "label": "高水平课程与学术交流",
          "value": "gspkcyxsjl"
        },
        {
          "label": "国家政策",
          "value": "gjzc"
        },
        {
          "label": "规章制度",
          "value": "17546"
        },
        {
          "label": "办事流程",
          "value": "17547"
        },
        {
          "label": "常见问题",
          "value": "17548"
        },
        {
          "label": "常见下载",
          "value": "17549"
        }
      ]
    }
  },
  "path": "/hitgs/:id?",
  "radar": [
    {
      "source": [
        "hitgs.hit.edu.cn",
        "hitgs.hit.edu.cn/:id/list.htm"
      ]
    },
    {
      "source": [
        "hitgs.hit.edu.cn/tzgg/list.htm"
      ],
      "target": "/hitgs/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "hitgs.hit.edu.cn/zhxw/list.htm"
      ],
      "target": "/hitgs/zhxw",
      "title": "综合新闻"
    },
    {
      "source": [
        "hitgs.hit.edu.cn/gspkcyxsjl/list.htm"
      ],
      "target": "/hitgs/gspkcyxsjl",
      "title": "高水平课程与学术交流"
    },
    {
      "source": [
        "hitgs.hit.edu.cn/gjzc/list.htm"
      ],
      "target": "/hitgs/gjzc",
      "title": "国家政策"
    },
    {
      "source": [
        "hitgs.hit.edu.cn/17546/list.htm"
      ],
      "target": "/hitgs/17546",
      "title": "规章制度"
    },
    {
      "source": [
        "hitgs.hit.edu.cn/17547/list.htm"
      ],
      "target": "/hitgs/17547",
      "title": "办事流程"
    },
    {
      "source": [
        "hitgs.hit.edu.cn/17548/list.htm"
      ],
      "target": "/hitgs/17548",
      "title": "常见问题"
    },
    {
      "source": [
        "hitgs.hit.edu.cn/17549/list.htm"
      ],
      "target": "/hitgs/17549",
      "title": "常见下载"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "172677342256609280",
      "image": "/_upload/tpl/03/b7/951/template951/images/logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://hitgs.hit.edu.cn/tzgg/list.htm",
      "title": "哈尔滨工业大学研究生院 - 通知公告",
      "type": "feed",
      "url": "rsshub://hit/hitgs"
    }
  ],
  "url": "hitgs.hit.edu.cn",
  "view": 0
}
```
