# 赣南医科大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `gmu`
- Namespace Name: `赣南医科大学`
- Route Path: `/gmu/yjs/:type/:subtype`
- Route Name: `研究生院`
- Example: `/gmu/yjs/zsgz/tzgg`
- URL: `gmu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FrankFahey`
- Source Location: `yjs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "分类，见下表", "options": [{"label": "招生工作", "value": "zsgz"}, {"label": "培养工作", "value": "pygz"}, {"label": "学位工作", "value": "xwgz"}, {"label": "学生工作", "value": "xsgz"}, {"label": "下载中心", "value": "xzzx"}]}
- `subtype`: {"description": "子分类，见下表", "options": [{"label": "通知公告", "value": "tzgg"}, {"label": "新闻速递", "value": "xwsd"}, {"label": "规章制度", "value": "gzzd"}, {"label": "导师管理", "value": "dsgl"}, {"label": "学位管理", "value": "xwgl"}, {"label": "评估工作", "value": "pggz"}, {"label": "学生活动", "value": "xshd"}, {"label": "奖助工作", "value": "jzgz"}, {"label": "招生下载", "value": "zsxz"}, {"label": "培养下载", "value": "pyxz"}, {"label": "学位下载", "value": "xwxz"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yjs.gmu.cn/:type/:subtype.htm`
  - `yjs.gmu.cn/`
- `target`: `/yjs/:type/:subtype`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/gmu/yjs/zsgz/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yjs.ts",
  "maintainers": [
    "FrankFahey"
  ],
  "name": "研究生院",
  "parameters": {
    "subtype": {
      "description": "子分类，见下表",
      "options": [
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "新闻速递",
          "value": "xwsd"
        },
        {
          "label": "规章制度",
          "value": "gzzd"
        },
        {
          "label": "导师管理",
          "value": "dsgl"
        },
        {
          "label": "学位管理",
          "value": "xwgl"
        },
        {
          "label": "评估工作",
          "value": "pggz"
        },
        {
          "label": "学生活动",
          "value": "xshd"
        },
        {
          "label": "奖助工作",
          "value": "jzgz"
        },
        {
          "label": "招生下载",
          "value": "zsxz"
        },
        {
          "label": "培养下载",
          "value": "pyxz"
        },
        {
          "label": "学位下载",
          "value": "xwxz"
        }
      ]
    },
    "type": {
      "description": "分类，见下表",
      "options": [
        {
          "label": "招生工作",
          "value": "zsgz"
        },
        {
          "label": "培养工作",
          "value": "pygz"
        },
        {
          "label": "学位工作",
          "value": "xwgz"
        },
        {
          "label": "学生工作",
          "value": "xsgz"
        },
        {
          "label": "下载中心",
          "value": "xzzx"
        }
      ]
    }
  },
  "path": "/yjs/:type/:subtype",
  "radar": [
    {
      "source": [
        "yjs.gmu.cn/:type/:subtype.htm",
        "yjs.gmu.cn/"
      ],
      "target": "/yjs/:type/:subtype"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
